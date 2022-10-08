# javafx-advancedinstaller-example

This project contains some code to show how to create an installer for a JavaFX application with Advanced Installer.

## Prerequisites

You have to have 

- Maven
- Java19 JDK and
- Advanced Installer 

installed and properly configured. 

(The project should compile with Java11 as well, just change the enforcer rules in pom.xml if necessary)

Dont forget to adapt the Advanced Installer path in the pom.xml file. 

## Build

    mvn package

After some compiling, an installer should be created in the target directory.

## Running

The installer should create a shortcut on your desktop which starts a simple JavaFX application.

