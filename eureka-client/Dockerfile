FROM java:8
ADD target/service-registration-and-discovery-client-0.0.1-SNAPSHOT.jar client.jar
#导出端口
EXPOSE 8080
ENTRYPOINT ["java","-jar","client.jar"]
