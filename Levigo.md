# Levigo-Research
## Barcode

## CI/CD
https://semaphoreci.com/blog/cicd-pipeline

A CI/CD pipeline helps you automate steps in your software delivery process, such as initiating code builds, running automated tests, and deploying to a staging or production environment
CI, short for Continuous Integration, is a software development practice in which all developers merge code changes in a central repository multiple times a day
CD stands for Continuous Delivery, which on top of Continuous Integration adds the practice of automating the entire software release process.
It’s essentially a runnable specification of the steps that need to be performed in order to deliver a new version of a software product.
### Source stage
A pipeline run is triggered by a source code repository.
Change in code triggers a notification to the CI/CD tool, which runs the corresponding pipeline.
### Build stage
We combine the source code and its dependencies to build a runnable instance of our product that we can potentially ship to our end users
Failure to pass the build stage is an indicator of a fundamental problem in the configuration of our project and it’s best to address it immediately.\
### Test stage
In this phase we run automated tests to validate the correctness of our code and the behavior of our product
Depending on the size and complexity of the project, this phase can last from seconds to hours.
Failure during the test stage exposes problems in code that developers didn’t foresee when writing the code

Once we have a built a runnable instance of our code that has passed all predefined tests, we’re ready to deploy it

## Tools for testing app development
https://www.testbytes.net/blog/performance-testing-tools-for-mobile-applications/

### Source Labs
This automated mobile app testing covers over 800 different browsers to ensure bug-free user environment.
The testing cloud runs tests in parallel and isn’t time-consuming at all.
### Test Complete
Possible to run repeated UI tests across native and hybrid mobile apps. 
Compatible with both Android and iOS devices
Possible to create automated test scripts or choose from programming languages including Python, VBScript, and JavaScript.
### Calabash
Used to perform automated functional testing for native mobile apps
Two open-source libraries for both Android and iOS devices
It can also provide APIs for touch screening experiences and works well with Ruby, NET, Java, and many other programming languages.
### Webload
Enables you to do a stress test to let you know of the device’s performance. 
Comes with an application that helps in recording scripts directly from a mobile device
### Kobitan
Kobiton provides access to devices for running manual and automated test. 
This mobile device cloud platform is built on top of the Appium open-source framework and could be used to test across devices without script modifications.
The main feature of the tool includes commands, screenshots, faster identification, and automatically generated activity logs
