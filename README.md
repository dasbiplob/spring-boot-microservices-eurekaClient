# spring-boot-microservices-eurekaClient
I have build multiple microservices, had them communicate with eachh other using RestTemplate(Syncronize) or WebClient(Asyncronize) with hard coded url's .
To avoid the hard coded url's used concept of server dicovery created Eureka Server and had all the microservice registered as eureka clients by adding them to the classpath
used the LOADBALANCED annotation on rest tempalete to leavege Eureka server by having client side load balancing.
