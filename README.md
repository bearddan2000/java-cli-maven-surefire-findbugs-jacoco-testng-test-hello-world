# java-cli-maven-surefire-findbugs-jacoco-testng-test-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using testNg
framework with jacoco and surefire
plugins.

## Tech stack
- java
- maven
	- findbugs
  - testNg
  - jacoco
  - surefire

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
- [Jacoco config](https://www.baeldung.com/jacoco)
