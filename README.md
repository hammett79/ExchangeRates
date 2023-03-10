# ExchangeRates
Foreign exchange rate demo API

A demo API with Spring boot that fetches exchange-rates from the publicly available API: https://exchangerate.host.
Spring boot 3, built with Gradle.

### API operations
1. Gets exchange rate from Currency A to Currency B
1. Gets all exchange rates from Currency A
1. Gets value conversion from Currency A to Currency B
1. Gets value conversion from Currency A to a list of supplied currencies

### Caching
Web server Caching mechanism with spring-boot-starter-cache dependency

### Installation guide
Import to your favourite IDE as a gradle project. Requires at least Java 17, gradle 7.6.

### Documentation
Once the application is up, documentation can be accessed from:

1. [http://localhost:8080/swagger-ui/index.html](http://localhost:8080/swagger-ui/index.html)
1. [http://localhost:8080/v3/api-docs](http://localhost:8080/v3/api-docs)

Please update host name and port if needed.