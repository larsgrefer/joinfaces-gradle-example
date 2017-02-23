# JoinFaces examples for Gradle [![Build Status](https://travis-ci.org/larsgrefer/joinfaces-gradle-example.svg?branch=master)](https://travis-ci.org/larsgrefer/joinfaces-gradle-example)

This repository contains example projects showing how to use [JoinFaces](https://github.com/joinfaces/joinfaces) with [Gradle](https://gradle.org)

## Projects
### `jar-example`
Contains:
 - `jar` packaging
 - Mojarra 2.2.x
 - Primefaces 6.0.

Usages:
 - Can be started via its `main`-method using an embedded Tomcat
 - Can be tested using `@SpringBootTest(webEnvironment = RANDOM_PORT)`
 
### `war-example`
Contains:
  - `war` packaging with
  - Mojarra 2.2.x
  - Primefaces 6.0.
 
Usages:
  - Can be started via its `main`-method using an embedded Tomcat
  - Can be deployed to an existing Tomcat (see travis tests)
  - Can be tested using `@SpringBootTest(webEnvironment = RANDOM_PORT)`