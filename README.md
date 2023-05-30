# configCloud
configurações Servidor
Packaging: jar

Versão Java: 11

# 1 - Configurção para projeto de micro serviço Eureka Server
Dependencies
Eureka Server
Spring Web
Lombok
Spring Boot DevTools
# 2 - Configurção para projeto de micro serviço Config Server
Dependencies
Config Server
Spring Web
Lombok
Spring Boot DevTools
# 3 - Configurção para projeto de micro serviço API Gateway Server
Dependencies
Spring Reactive Web
Config Client
Cloud LoadBalancer
Eureka Discovery Client
Gateway
Spring Boot Actuator
OpenFeign
Lombok
Spring Boot DevTools
# 4 - Configurção para projeto de micro serviço clients
Dependencies
Eureka Discovery Client
Config Client
Spring Boot Actuator
Spring Web
Lombok
OpenFeign
Spring Data JPA -- Opcional
Spring Boot DevTools
