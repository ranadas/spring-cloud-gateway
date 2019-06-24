### Spring cloud gateway example

This is a example using Spring cloud gateway and its features! This example contains:
+ Bookstore microservice: port 8089
+ MoviesStore microservice: port 8090
+ API Gateway (Srpring Cloud gateway): port 8087
+ Service Discovery (Eureka): 8088
+ Hystrix dashboard: port 8099

You'll also need a redis instance running (on port 6379) in order to enable the request limiter of the gateway. 
The easiest way is to spin up a redis instance on docker container:
` docker run --name some-redis -p 6379:6379 -d redis`

You can read more about it here: https://aboullaite.me/spring-cloud-gateway/
https://github.com/spring-cloud-samples

https://spring.io/blog/2019/01/23/spring-cloud-greenwich-release-is-now-available
TODOs : 
+ Investigate REDIS for rate limiting, substitute?
+ Convert into reactive services with Routes.
+ Kotlin?
+ Config server
+ Sleuth/Zipkin - https://github.com/spring-cloud/spring-cloud-sleuth
+ Admin dashboard - https://github.com/yidongnan/spring-cloud-netflix-example
+ Ribbon-> Spring Cloud Loadbalancer  -https://dzone.com/articles/microservice-architecture-with-spring-cloud-and-do
+ resilience4j - Hysterix - https://github.com/resilience4j/resilience4j
(https://spring.io/blog/2019/01/23/spring-cloud-greenwich-release-is-now-available) 