# Spring Social Showcase with Spring Data JPA

### from https://github.com/spring-projects/spring-social-samples/tree/master/spring-social-showcase-boot

- 최신 라이브러리로 업데이트 하였습니다.
- localhost:8080 에서 바로 테스트 해볼 수 있도록 수정하였습니다.
- 링크드인은.. 제외하였습니다. (로컬호스트로 바로 테스트가 잘 안되네요 ㅠ)
- 메이븐 프로젝트로 변경 하였습니다.
- JPA지원하도록 수정중에 있습니다. (이것때문에 따로 작업합니다.)


### Quick Start
- JDK 1.8 or later
- Maven 3.0+

```
git clone https://github.com/origoni/spring-social-showcase-boot-test.git
cd spring-social-showcase-boot-test
mvn spring-boot:run
```

- visit [http://localhost:8080/](http://localhost:8080/)




Spring Social Showcase (Spring Boot)
====================================
This sample app demonstrates many of the capabilities of the Spring Social project, including:
* Connect to Facebook, Twitter, and LinkedIn
* Sign in using Facebook, Twitter, and Linked in using ProviderSignInController for provider-signin

Step 1: Register your application
---------------------------------
Before you can run the application, you'll need to obtain application credentials from Facebook, Twitter, and LinkedIn by registering the application with each of the service providers:

 * Facebook: https://developers.facebook.com/apps
 * Twitter: https://apps.twitter.com/
 * LinkedIn: https://www.linkedin.com/secure/developer

Be sure to read each platform's usage policies carefully and understand how they impact your use of Spring Social with those platforms.

Step 2: Edit application.properties
-----------------------------------
Once you have registered the application, you'll need to edit src/main/resources/application.properties, adding the credentials to the appropriate properties.

Step 3: Run the application
---------------------------
To run, simply import the project into your IDE and deploy to a Servlet 2.5 or > container such as Tomcat 6 or 7.
Access the project at http://localhost:8080/spring-social-showcase

Alternatively, you can run the application using Gradle. To make it easier to build the project with Gradle, the Gradle wrapper has been included. The Gradle wrapper makes it possible to run Gradle without having to explicitly install Gradle to your system.

To run the application with Gradle:

```sh
$ gradlew bootRun
```

Or you can build the application with Gradle, then run the resulting WAR file as an executable JAR:

```sh
$ gradlew build
...
$ java -jar build/libs/spring-social-showcase.war
```

When running the application from the command line, you can access it at http://localhost:8080 from your browser.

Step 4: Participate in the Spring Social community
--------------------------------------------------

Discuss Spring Social on StackOverflow at http://stackoverflow.com/questions/tagged/spring-social. We welcome you to ask questions and we encourage you to answer any you might have insight into.

If you run into any problems or have a suggested new feature, let us know at https://jira.spring.io/browse/SOCIAL. Or better yet, fork Spring Social on GitHub and send us a pull request to fix a bug or introduce a new feature.
