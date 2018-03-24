# Test Automation Project
Simple Java test automation framework to cover a purchase request in "Konakart" website

## Concepts Included
Page Object Modeling
Data Driven Framework

## Tools
Gradle
TestNG
Selenium Webdriver

## Requirements
In order to utilise this project you need to have the following installed locally:
1-Eclips
2-Google Chrome Installed 
3-Java 1.8

To run all test cases, use the "Main" class.

## Reporting
Reports for each test case is generated through TestNG automatically

##Gradle vs Maven comparison

# 1-Performance
Improving build time is one of the most direct ways to ship faster. Both Gradle and Maven employ some form of parallel project building and parallel dependency resolution. The biggest differences are Gradle's mechanisms for work avoidance and incrementality. The top 3 features that make Gradle much faster than Maven are:

# 2-Incrementality — Gradle avoids work by tracking input and output of tasks and only running what is necessary, and only processing files that changed when possible.
Build Cache — Reuses the build outputs of any other Gradle build with the same inputs, including between machines.
Gradle Daemon — A long-lived process that keeps build information "hot" in memory.
These and more performance features make Gradle at least twice as fast for nearly every scenario (100x faster for large builds using the build cache) in this Gradle vs Maven performance comparison.

# 3-User Experience
Gradle build script written with Kotlin in an IDE
Maven's longer tenure means that its support through IDEs is better for many users. Gradle's IDE support continues to improve quickly, however. For example, Gradle now has a Kotlin-based DSL that provides a much better IDE experience. The Gradle team is working with IDE-makers to make editing support much better — stay tuned for updates.

Although IDEs are important, a large number of users prefer to execute build operations through a command-line interface. Gradle provides a modern CLI that has discoverability features like `gradle tasks`, as well as improved logging and command-line completion.

Finally, Gradle provides an interactive web-based UI for debugging and optimizing builds: build scans. These can also be hosted on-premise to allow an organization to collect build history and do trend analysis, compare builds for debugging, or optimize build times.

# 4-Dependency Management
Both build systems provide built-in capability to resolve dependencies from configurable repositories. Both are able to cache dependencies locally and download them in parallel.

As a library consumer, Maven allows one to override a dependency, but only by version. Gradle provides customizable dependency selection and substitution rules that can be declared once and handle unwanted dependencies project-wide. This substitution mechanism enables Gradle to build multiple source projects together to create composite builds.

Maven has few, built-in dependency scopes, which forces awkward module architectures in common scenarios like using test fixtures or code generation. There is no separation between unit and integration tests, for example. Gradle allows custom dependency scopes, which provides better-modeled and faster builds.

As a library producer, Gradle allows producers to declare `api` and `implementation` dependencies to prevent unwanted libraries from leaking into the classpaths of consumers. Maven allows publishers to provide metadata through optional dependencies.
