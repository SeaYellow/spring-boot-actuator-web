# spring-boot-actuator-web
a wrapper for spring-boot-starter-actuator, add a navigation for all actuator urls
##dependency
###clone this project
mvn clean install
###add dependency
```xml
       <dependency>
            <groupId>com.patterncat</groupId>
            <artifactId>spring-boot-starter-actuator-web</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency>
```
##config base path for actuator web
```properties
actuator.web.base:/actuator
```
this is optional,if not set ,default is /nav
##the navigation page is like this
 ![navigation page](https://github.com/patterncat/spring-boot-actuator-web/blob/master/src/main/resources/static/image/actuator.png)
