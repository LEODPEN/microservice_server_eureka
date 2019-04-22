# microservice_server_eureka
 use only two instances.
 
 ## 使用eureka作服务注册和发现
 
 + 双模式实际应用到为相互注册，端口分别为8761和8762
 
 + 开启了自我发现，投入使用考虑关闭
 
 + 版本为 Greenwich.SR1(RELEASE)
 
 
```
跳过一切，直接使用？
使用docker pull到本地
    docker pull leodpen/eureka:latest
    
    docker run -p 8761:8761 -d leodpen/eureka
    (端口自行选择映射)

```
