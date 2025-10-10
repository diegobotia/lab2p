
[![CI/CD Pipeline](https://github.com/diegobotia/lab2p/actions/workflows/build.yml/badge.svg)](https://github.com/diegobotia/lab2p/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_lab2p&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=diegobotia_lab2p)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_lab2p&metric=bugs)](https://sonarcloud.io/summary/new_code?id=diegobotia_lab2p)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_lab2p&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=diegobotia_lab2p)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_lab2p&metric=coverage)](https://sonarcloud.io/summary/new_code?id=diegobotia_lab2p)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_lab2p&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=diegobotia_lab2p)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_lab2p&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=diegobotia_lab2p)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_lab2p&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=diegobotia_lab2p)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_lab2p&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=diegobotia_lab2p)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_lab2p&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=diegobotia_lab2p)


Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random Aircraft
* Get application version
* health check

Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk

### Folders Structure

In the folder `src` is located the main code of the app

In the folder `test` is located the unit tests

### How to install it

Execute:

```shell
$ mvnw spring-boot:run
```
to download the node dependencies

### How to test it

Execute:

```shell
$ mvnw clean install
```

### How to get coverage test

Execute:

```shell
$ mvwn -B package -DskipTests --file pom.xml
```

