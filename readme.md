
Example of using WebSocket on Jetty.

This project uses maven.
This checkout is a valid ${jetty.base} directory too.

To build:

    $ mvn clean install

  This should have created a webapps/root.war file for you
  
To run using jetty home:
  
    $ java -jar /path/to/jetty-home-9.4.6.v20170531/start.jar


To run in jetty distribution:

    $ java -jar /path/to/jetty-distribution-9.4.6.v20170531/start.jar

To test:

  1) Open [http://localhost:8080/demo](http://localhost:8080/demo) in your websocket capable web browser


