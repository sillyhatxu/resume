# cloud

## Introduction

### Technology
* Spring
    * [Spring boot](https://projects.spring.io/spring-boot/) - Spring boot
    * [Spring cloud](http://projects.spring.io/spring-cloud/) - Spring cloud
    * [Spring cloud netflix stack](http://cloud.spring.io/spring-cloud-netflix/single/spring-cloud-netflix.html#_router_and_filter_zuul) - Zuul
* [Lombok](https://projectlombok.org/) - Lombok
* Databse
    * [H2](http://www.h2database.com/html/main.html) - H2
    * [Mysql](https://www.docker.com/) - Mysql
* [Swagger](https://swagger.io/) - Swagger
* [Spock](https://www.docker.com/) - Spock
* [Kafka](https://www.docker.com/) - Kafka
* [Redis](https://www.docker.com/) - Redis
* [ELK](https://www.docker.com/) - ELK
* [Docker](https://www.docker.com/) - Docker
* CI/CD
    * Jenkins
    * Gitlab
    * Git
    * jira

## 1、状态定义
### 1.1 所有可变状态，定义为枚举类
```
public enum SyncValidateStatus {

    UN_VALIDATE(0),
    VALIDATE_ERROR(-1),
    VALIDATE_SUCCESS(1);

    private final int code;


    SyncValidateStatus(int code) {
        this.code = code;
    }

    public int getCode() {
        return this.code;
    }

    public String toString() {
        return Integer.toString(this.code);
    }

    public static SyncValidateStatus valueOf(int status) {
        for (SyncValidateStatus syncValidateStatus : values()) {
            if (syncValidateStatus.code == status) {
                return syncValidateStatus;
            }
        }
        throw new IllegalArgumentException("No matching constant for [" + status + "]");
    }
}
```
### 1.2 所有不可变状态定义在常量类中
```
public static final boolean IN_STOCK = true;
public static final boolean OUT_OF_STOCK = false;

不允许任何未经定义的常量直接出现在代码中。 
eg:
String key = "key_" + index;
map.put(key, value);
```

## 2、命名规范

### 2.1 Controller
* XXXController
* XXXAdminController
* XXXClientController

### 2.2 Service
* XXXService
* XXXAdminService
* XXXClientService

### 2.3 ServiceImpl
* XXXServiceImpl
* XXXAdminServiceImpl
* XXXClientServiceImpl

### 2.3 Repository
* XXXRepository

## 3、功能规范

### 3.1 Controller
```
1、对传入参数校验其准确性
2、将传入参数封装为DTO或Filter对象传入Service层
```

### 3.2 Service
```
1、SOA ：暴露出来的服务一定是接口，内部的实现类用 Impl 的后缀与接口区别。
2、Service‰
```

## 8、记录

### 8.1 创建Module
* 创建Module
* 编辑settings.gradle
* 编辑application.yml
* 编辑bootstrap.yml
* 编辑db/migration路径下sql文件
* 登录AWS，Elastic Container Service 创建Repositories [ECS](https://ap-southeast-1.console.aws.amazon.com/ecs/home?region=ap-southeast-1#/repositories)
* Jenkins 配置增加Module
* CI项目中增加Module配置
