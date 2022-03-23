# CI-CD Workflow Project

App:

* Made with Quarkus (with Java 11 and Maven)

CI:

* Jenkins

Container:

Container with Docker

![image](https://miro.medium.com/max/1400/1*bQs7kGuHjLfgXEJPxhzzuw.png)

Container with Jib

![image2](https://miro.medium.com/max/1400/1*qUy0Mpj0_phRwBbo1kxLPg.png)

Default image base for Jib method:

* fabric8/java-alpine-openjdk11-jre

Execute for create the docker image:

`./mvnw clean package -Dquarkus.container-image.build=true`
