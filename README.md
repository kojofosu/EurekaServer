# EUREKA SERVER

- Clone project : ``git clone https://github.com/kojofosu/EurekaServer.git``
- Create resource folder in path `src/main/resources`
- Create `application.properties` file in the resource folder
- Add below properties in the properties folder

```properties
spring.application.name=eureka-server
server.port=7850

eureka.client.register-with-eureka=false
eureka.client.fetch-registry=false
```
