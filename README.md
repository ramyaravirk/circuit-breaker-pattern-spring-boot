Circuit Breaker Pattern with Spring Boot
This Spring Boot project demonstrates the implementation of the Circuit Breaker pattern using Spring Cloud.

Overview
The Circuit Breaker pattern is a design pattern used to handle failures and latency issues that may occur when calling remote services or accessing external resources. It helps improve fault tolerance in distributed systems by detecting and isolating failures, thereby preserving system stability.

This project showcases how to implement circuit breakers in a Spring Boot application using Spring Cloud, specifically utilizing the Netflix Hystrix library.

Features
Integration of Circuit Breaker pattern using Spring Cloud and Netflix Hystrix.
Configuration of circuit breakers with fallback options for handling failures.
Monitoring and metrics collection for circuit breaker state and performance insights.
Prerequisites
Java 8 or higher
Maven 3.3 or higher
Spring Boot 2.x
Spring Cloud Hoxton.SR12 (or latest version)
Netflix Hystrix
