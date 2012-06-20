HeartBeatChecker for partake.in
===============================
A alive monitoring tool to maintain PARTAKE.

Feature
-------
 - send a direct message to partake.in's administrators when partake.in doesn't response to the HTTP request.

How to build
------------
1. install [Google Plugin for Eclipse](https://developers.google.com/appengine/docs/java/tools/eclipse) to your eclipse.
2. create your [twitter4j.properties](http://twitter4j.org/en/configuration.html).
3. checkout the latest project.
4. import this project to your workspace, and check its setting.
    - use JDK1.6+ to compile.
    - use Google App Engine SDK 1.5.0.
    - use JUnit4 as the testing framework.
5. put your twitter4j.properties into `src/main/resources`.
6. now, you can run this project on Eclipse. see [Google App Engine's help](https://developers.google.com/appengine/docs/java/tools/eclipse?hl=en#Running_the_Project) for detail.
