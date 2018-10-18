# Spring Boot WAR deployment example

eing able to start the application as standalone jar is great, but sometimes it might not be possible to run an app as jar [environment restrictions, company-wide regulations etc] and you have to build a WAR to be deployed into a traditional web/application server. Spring Boot helps us creating WAR using [SpringBootServletInitializer](https://docs.spring.io/spring-boot/docs/current/api/org/springframework/boot/web/servlet/support/SpringBootServletInitializer.html)

# Following technologies stack being used:
- Spring Boot 1.4.3.RELEASE
- Spring 4.3.5.RELEASE [transitively]
- Maven 3.3.9
- JDK 1.8
- Apache Tomcat 9.0.12
- Inteij Idea