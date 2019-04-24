# microservice_server_eureka
 use only two instances.you can use three or more.
 
 ## 使用eureka作服务注册和发现
 
 + 双模式实际应用到为相互注册，端口分别为8761和8762.
 
 + 开启了自我发现，投入使用考虑关闭.
 
 + 版本为 Greenwich.SR1(RELEASE).
 
 + 只于本地使用请修改yml文件相应内容至localhost.
 
 
```
跳过一切，直接使用？
    服务部署：
    docker pull leodpen/eureka:latest
    
    本地使用：
    docker pull leodpen/eureka:local
   
    docker run -p 8761:8761 -d leodpen/eureka:{tag}
    (端口自行选择映射)

```

### 注：如果要进入容器内部查看，使用后缀使用.sh而不是/bin(for use alpine).
  
  一个示范: docker exec -it eureka.jar .sh
  
 btw: Repo仍增加中.(includes java11)
