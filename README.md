# Hello-Jenkins

## Jenkins/Spring Boot Tutorial
This tutorial steps us through the creation of a Jenkins pipeline for an existing Spring Boot web service project.

We will need:

* A private GitHub repository for this project
* Java 8 (or greater)
* MySQL Server
* MySQL Workbench
* IntelliJ IDEA Community Edition
* Terminal (Mac) or Command Prompt (Windows)
* Jenkins Server (set up as part of this tutorial)

### Background

Jenkins is an open source server that is used to automate continuous integration and continuous delivery tasks in the software development process.

The Pipeline (with a captital P) is the abstraction that Jenkins uses to define and automate continuous integration and continuous delivery processes. A Pipeline consists of various software plugins and a **Jenkinsfile** that defines the Pipeline and specifies its behavior.

### Pipeline Design

We will create and configure a Pipeline for an existing RSVP web service consisting of the following stages:

1. Build - compiles the project
2. Test - runs the unit and integration tests
3. Deliver - packages the project

### Creating the Pipeline

We will create the Jenkins pipeline for this project in the following steps:

1. Jenkins installation
2. Create a new GitHub repo and configure and commit RSVP service source code
3. Pipeline creation
4. Pipeline execution
