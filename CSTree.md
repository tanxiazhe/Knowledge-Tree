# CS-Tree
## java
### core
- inner class
- class loader sequence
- container
    - collection
    - map
    - tools
        - collections
- hashmap vs concurrenthashmap
- socket
- IO
    - bio
    - aio    
- generic
    - 向上限定
    - 向下限定
- annotation
    - method
    - field
- proxy
    - jdk proxy
    - cglib

### quartz 
### java 8+
- Lambda basics

### concurrent
- 多线程
    - runnable vs callable
    - 线程池
- 并发包工具
    - AQS
    
### jvm
- 内存区域划分
- 垃圾回收算法
- 垃圾收集器
- 双亲委派模型

## framework
### spring
#### springboot
#### springcloud
    - feign
    - eureka
    - hystrix

### mybatis
### play



## db
### mysql
## data structure
## design pattern
## network

## distribution 
### redis
### rabbitmq
### hystrix

## web service
### SOAP
### oDATA
### Restful
### RPC 



## performance
- jconsole
- jmap
- jprofile

## security
- identification
- authorization
- authtication
- oAuth2.0
- SAML
- SSO

## js
## nodejs
## python
## docker
1. container :
    1. docker ps; 查看正在运行的容器
        1. docker ps -l 查看最后的container
    2. docker container -l
    3. docker run -it ubuntu /bin/bash 启动容器，以命令行模式进入该容器
    4. docker start/stop/restart /rm /logs containerid
2. image:
    1. docker images 列出主机上的镜像
    2. docker pull xx 获取新镜像
    3. docker rmi xx 删除镜像
    4. 更新镜像
        1. docker run -t -i  xx /bin/bash   
        2. apt-get update
        3. exit  
        4. docker commit -m="comments" -a="author"  containerid newimagename
    5. 构建镜像

## tomcat 
## k8s
## git 
## uml
## mvn
## groovy
