FROM java:8
#通过配置env来启动时指定启动参数
ENV profile=slav2
ADD target/service-registration-and-discovery-service-0.0.1-SNAPSHOT.jar service.jar
#导出端口
EXPOSE 8761
ENTRYPOINT ["java","-jar","-Dspring.profiles.active=${profile}","service.jar"]
