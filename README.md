# micro-service_and_docker
RestFul Web Services, Micro-services, spring cloud and docker 

#The framework i used in this project are:
- Spring,Spring boot, Maven and Intelij Idea


How the project works?


#Download zip file ,extract it  and import
it in your favourite idea.

I implemented spring cloud load balancing with Feign and i also imlemented a Eureaka naming server
I also implemented an spring cloud gateway gateway and distributed tracing with Zipkin.

I also implemented resilience4j instead as circurt breaker.

AT the end the project was running on docker.

#After importing your project in your Idea, the fist application to run is NamingServer,
so that all your application will be rigistered and tracked.

#The second application to run is CurrencyExchangeService as CurrencyConversionSErvice depents on it.


