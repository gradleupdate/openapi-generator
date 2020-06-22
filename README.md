# openapi-generator

Open API Generator sample repository

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/arthurfnsc/openapi-generator.js/graphs/commit-activity)


## Activity
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/arthurfnsc/openapi-generator.svg?style=popout)
[![HitCount](http://hits.dwyl.io/arthurfnsc/openapi-generator.svg)](http://hits.dwyl.io/arthurfnsc/openapi-generator)
![GitHub last commit](https://img.shields.io/github/last-commit/arthurfnsc/openapi-generator.svg?style=popout)

### Activity master branch
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/arthurfnsc/openapi-generator/master.svg)

### Issues
![GitHub issues](https://img.shields.io/github/issues/arthurfnsc/openapi-generator.svg)
![GitHub closed issues](https://img.shields.io/github/issues-closed/arthurfnsc/openapi-generator.svg)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/arthurfnsc/openapi-generator.svg)](http://isitmaintained.com/project/arthurfnsc/openapi-generator "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/arthurfnsc/openapi-generator.svg)](http://isitmaintained.com/project/arthurfnsc/openapi-generator "Percentage of issues still open")
![GitHub pull requests](https://img.shields.io/github/issues-pr/arthurfnsc/openapi-generator.svg)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/arthurfnsc/openapi-generator.svg)

## Pre-requirements

### Java 11

<details><summary><b>Instructions</b></summary>

Java 11 could be installed through JDK on 
[Oracle](https://www.oracle.com/java/technologies/javase-downloads.html) 
or [OpenJDK](https://jdk.java.net/java-se-ri/11)
 
Alternatively you could use [SDKMan](https://sdkman.io/) 
and install Java through following command:

```sh
foo@bar:~$ sdk install java <version>
```

To list all available Java versions, run the following command:

```sh
foo@bar:~$ sdk list java
```

</details>

### Gradle (opcional)

<details><summary><b>Instructions</b></summary>

The project was designed to Gradle installation was optional,
for this, it is possible to run the project settings after 
installation of Java by **gradlew.bat** files on Windows systems 
and **gradlew** on Unix systems, which interact with the 
**gradle-wrapper.jar** file contained in the folder **gradle/wrapper** 
at the root of the project.

If you want to install Gradle on your machine you could installed 
through [Gradle site](https://gradle.org/).

Alternatively you could use [SDKMan](https://sdkman.io/) 
and install Gradle through following command:

```sh
foo@bar:~$ sdk install gradle
```

To list all available Gradle versions, run the following command:

```sh
foo@bar:~$ sdk list gradle
```

</details>

### Maven (opcional)

<details><summary><b>Instructions</b></summary>

The project was designed to Maven installation was optional,
for this, it is possible to run the project settings after 
installation of Java by **mvnw.cmd** files on Windows systems 
and **mvnw** on Unix systems, which interact with the 
**maven-wrapper.jar** file contained in the folder **.mvn/wrapper** 
at the root of the project.

If you want to install Maven on your machine you could installed 
through [Maven site](https://maven.apache.org/).

Alternatively you could use [SDKMan](https://sdkman.io/) 
and install Maven through following command:

```sh
foo@bar:~$ sdk install maven
```

To list all available Maven versions, run the following command:

```sh
foo@bar:~$ sdk list maven
```

</details>

## Architecture

[![badge-jdk](https://img.shields.io/badge/jdk-11-green.svg)](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
[![Gradle Status](https://gradleupdate.appspot.com/arthurfnsc/openapi-generator/status.svg)](https://gradleupdate.appspot.com/arthurfnsc/openapi-generator/status)
[![badge-maven](https://img.shields.io/badge/maven-3.6.3-green.svg)](https://maven.apache.org/)

- [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator)
- [Spring Boot 2.3](https://projects.spring.io/spring-boot/)

## Execution

### Clone

```sh
foo@bar:~$ git clone https://github.com/arthurfnsc/openapi-generator.git
foo@bar:~$ cd openapi-generator
```

### Gradle Execution Linux | Windows 

```sh
foo@bar:~$ [./gradlew | gradlew.bat] <comando>
```

### Maven Execution Linux | Windows

```sh
foo@bar:~$ [./mvnw | mvnw.cmd] <comando>
```