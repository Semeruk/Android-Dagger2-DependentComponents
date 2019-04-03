# Dagger2 with Dependent Components approach

Project shows that the @Singleton annotation lasts the entire lifecycle of the application.

Components that do not need to remain in memory all the time (i.e. components that are tied to the lifecycle of an activity or fragment, or even tied to when a user is signed-in) are the dependent components or subcomponents.

This project consists of one dependent component (child) and a dependency component (parent).

![dagger2 sketch](https://github.com/Semeruk/Android-Dagger2-Basics2/blob/master/diagram.jpg)
