# JoinFaces examples for Gradle [![Build Status](https://travis-ci.org/larsgrefer/joinfaces-gradle-example.svg?branch=master)](https://travis-ci.org/larsgrefer/joinfaces-gradle-example)

This repository contains example projects showing how to use [JoinFaces](https://github.com/joinfaces/joinfaces) with [Gradle](https://gradle.org)

## Projects
### `jar-example`
Contains:
 - `jar` packaging
 - Mojarra 2.2.x
 - Primefaces 6.1

Usages:
  - Can be started via its `main`-method using an embedded Tomcat
    - Using `java -jar`
    - Using `./gradlew jar-example:bootRun`
    - Using your IDE
  - Can be tested using `@SpringBootTest(webEnvironment = RANDOM_PORT)`
    - Using `./gradlew jar-example:test`
    - Using your IDE
 
### `war-example`
Contains:
  - `war` packaging with
  - Mojarra 2.2.x
  - Primefaces 6.1
 
Usages:
  - Can be deployed to an existing Tomcat (see Travis tests)
  - Can be started via its `main`-method using an embedded Tomcat
    - _Using `java -jar`_ (See spring-projects/spring-boot#9014)
    - Using `./gradlew jar-example:bootRun`
    - Using your IDE
  - Can be tested using `@SpringBootTest(webEnvironment = RANDOM_PORT)`
    - Using `./gradlew war-example:test`
    - Using your IDE
