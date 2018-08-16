# Homework 9

This homework will aiding you in understand some tools and frameworks dedicated to implement Microservices in practice as a preparation for the final project.
	
## Decomposition Recipes

First things first, carefully read the migration for microservices success stories of Soundcloud and Karma. Try to be aware of the anticorruption and [StranglerApplication](https://www.martinfowler.com/bliki/StranglerApplication.html) application characteristics.

- [Building Products at SoundCloud — Part I: Dealing with the Monolith](https://developers.soundcloud.com/blog/building-products-at-soundcloud-part-1-dealing-with-the-monolith)
- [Building Products at SoundCloud—Part II: Breaking the Monolith](https://developers.soundcloud.com/blog/building-products-at-soundcloud-part-2-breaking-the-monolith)
- [How we build microservices at Karma](https://blog.karmawifi.com/how-we-build-microservices-at-karma-71497a89bfb4)

## Distributed Systems Recipes

Undestand the main issues and the the recommended situations where the application of the following frameworks are indicated to attend architectural attributes related to microservices.

- [Spring Boot](https://projects.spring.io/spring-boot/),[Spring Cloud](https://projects.spring.io/spring-cloud/) and [Netflixx OSS](https://netflix.github.io/) projects
- Versioned and Distributed Configuration ~> [Spring Cloud Config](https://cloud.spring.io/spring-cloud-config/) & [Spring Cloud Bus](https://cloud.spring.io/spring-cloud-bus/)
- Service Registration/Discovery ~> [Spring Cloud Netflix](https://cloud.spring.io/spring-cloud-netflix/) & [Eureka](https://github.com/Netflix/eureka)
- Routing and Load Balancing ~> [Ribbon](https://github.com/Netflix/ribbon)
- Fault-Tolerance ~> Circuit breakers and Bulkheads design patterns, [Hystrix](https://github.com/Netflix/Hystrix) & [Turbine](https://github.com/Netflix/Turbine)
- API Gateways/Edge Services ~> [the API Gateways design pattern](microservices.io/patterns/apigateway.html) & [RxJava](https://github.com/ReactiveX/RxJava) (a JVM implementation of [Reactive Extensions](http://reactivex.io/) born at Netflix)

## Testing

Read the article [Testing Strategies in a Microservice Architecture](https://martinfowler.com/articles/microservice-testing/) by Toby Clemson.

## Submit

Telegram channel, <https://t.me/regcin>, a MD file (LOGIN-HW1.md) containing your answer.

**D+7**, 17:00.
