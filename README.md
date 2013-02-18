Server-sent Events Java Sample
=========================

This is a sample Java based web application which uses HTML 5 [Server-sent events](http://dev.w3.org/html5/eventsource/) and supports IE 8+.

This sample application is based on 
* [Jetty EventSource Serlvet](https://github.com/jetty-project/jetty-eventsource-servlet)
* [Yaffle's EventSource](https://github.com/Yaffle/EventSource) polyfill library 

How to build
-------------------------
The sample project is built using [Gradle](http://www.gradle.org), just use `gradle war` to generate the WAR file. Put the WAR file into any servlet container and access the index page.



