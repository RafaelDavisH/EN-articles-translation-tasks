To evaluate the performance of a system, you need a tool that can simulate its behavior in production.

For this purpose, you can use a software tool based on Scala called Gatling. This article will teach you how to integrate it into a Spring Boot application and perform a load test.

Main Concepts
Gatling is a tool you can use to execute load and performance tests. It can be used as a standalone application or integrated into a Maven or Gradle-based project.

Gatling is based on Scala, the Netty framework, and the Akka toolkit. It has an asynchronous, non-blocking architecture, which allows for high performance with minimum wasting of resources.

You can define tests by Gatling's flexible domain-specific language. You can also use its recorder function with a Graphical User Interface to capture user interactions in the browser and generate Scala scripts that can be modified and launched to perform a simulation.

In this article, you will learn how to integrate Gatling in a Spring Boot web application based on Maven. You will define a load test by its DSL, and then run it using the Gatling Maven plugin.

With Gatling, you can perform performance tests in a variety of ways. For instance, you can implement:

Load Testing: to see how a system performs under a specific load
Stress Testing: to find the breaking point of a system, raising the load progressively
Soak Testing: running the system with a steady load for a long time to find its pitfalls
Spike Testing: to see how the system performs when swiftly raising the load to a peak and then going down
The basic components by which Gatling implements the features described above are:

Scenarios: a series of steps performed by a virtual user
Feeders: how data is provided to feed the scenarios
Injection: a sort of a blueprint that states how the test is performed, in terms of number of virtual users, how they change in time, and so on
