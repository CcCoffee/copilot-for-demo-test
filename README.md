# Spring Cloud Gateway API Gateway Project

This project provides a library for building an API Gateway on top of Spring WebFlux. Spring Cloud Gateway aims to provide a simple, yet effective way to route to APIs and provide cross-cutting concerns to them such as security, monitoring/metrics, and resiliency.

## Features

Spring Cloud Gateway features:

- Built on Spring Framework 5, Project Reactor and Spring Boot 2.0
- Able to match routes on any request attribute
- Predicates and filters are specific to routes
- Hystrix Circuit Breaker integration
- Spring Cloud DiscoveryClient integration
- Easy to write Predicates and Filters
- Request Rate Limiting
- Path Rewriting

## Advanced Features

This project also includes advanced features such as:

### Permission Verification

The project includes permission verification functionality that allows you to control access to your APIs based on user roles.

### IP Whitelist Verification

The project includes IP whitelist verification functionality that allows you to control access to your APIs based on IP addresses.

### Redis Token Bucket Rate Limiting

The project includes Redis token bucket rate limiting functionality that allows you to limit the number of requests per second.

### Secure File Scanning

The project includes secure file scanning functionality that allows you to scan uploaded files for viruses and other security threats.

## Zero Downtime Deployment

The project supports zero downtime deployment using blue-green deployment techniques.

## High Performance and Throughput

The project is designed for high performance and throughput using reactive programming techniques.
