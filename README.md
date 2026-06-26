# AWS CI/CD Project

A simple Java Maven project created to demonstrate the basics of Continuous Integration (CI) using Maven and JUnit. This project serves as a foundation for building CI/CD pipelines with tools such as GitHub, Jenkins, and AWS.

## Project Overview

This project includes:

* Java 17
* Apache Maven
* JUnit 5 for unit testing
* Simple addition method implementation
* Unit test to validate the functionality

## Project Structure

```text
aws-cicd-project/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       └── com/example/
│   │           └── App.java
│   │
│   └── test/
│       └── java/
│           └── com/example/
│               └── AppTest.java
│
├── pom.xml
└── README.md
```

## Technologies Used

* Java 17
* Apache Maven
* JUnit 5
* Git
* GitHub

## Features

* Maven project structure
* Static `add()` method implementation
* Automated unit testing using JUnit 5
* Easy to integrate into CI/CD pipelines

## App.java

Contains a simple method:

```java
public static int add(int a, int b) {
    return a + b;
}
```

## Unit Test

The project includes a JUnit test that verifies the `add()` method.

Example:

```java
assertEquals(30, App.add(10, 20));
```

## How to Clone

```bash
git clone https://github.com/<your-username>/aws-cicd-project.git
```

## Build the Project

```bash
mvn clean install
```

## Run Unit Tests

```bash
mvn test
```

If the test passes, Maven displays:

```text
BUILD SUCCESS
```

## Learning Outcomes

Through this project, I learned:

* Creating a Maven project
* Managing dependencies using `pom.xml`
* Writing Java methods
* Writing unit tests with JUnit 5
* Executing tests using Maven
* Understanding the role of automated testing in CI/CD pipelines
* Using Git and GitHub for version control

## Future Improvements

* Integrate Jenkins for Continuous Integration
* Deploy artifacts using AWS services
* Add code coverage with JaCoCo
* Configure GitHub Actions
* Containerize the application using Docker

## Author

**Bommena SuryaTeja**
