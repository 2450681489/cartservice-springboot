FROM swr.cn-north-4.myhuaweicloud.com/ddn-k8s/docker.io/openjdk:17
ADD cartstore-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]