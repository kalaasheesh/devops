Addressbook Tutorial
====================

This tutorial teaches you some of the basic concepts in [Vaadin Framework](https://vaadin.com). It is meant to be
a fast read for learning how to get started - not an example on how application should be
designed. Please note this example uses and requires Java 8 to work.

![Addressbook Screenshot](addressbook.png "Addressbook Screenshot")


Running the example from the command line
-------------------
```
$ mvn jetty:run
```

Open [http://localhost:8080/](http://localhost:8080/)


Importing in Eclipse
--------------------
These instructions were tested on Eclipse IDE for Java EE Developers Luna SR2. You can get it from http://eclipse.org/downloads/

To checkout and run the project in Eclipse, do:
- File -> Import...
- Check out Maven Projects from SCM
- Choose Git from SCM menu
  - If you do not see "Git" in the SCM menu, click "Find more SCM connectors in the m2e Marketplace" and install "m2e-egit". Restart Eclipse and start over.
- Right click the imported "addressbook" and choose Run As -> Maven Build...
  - Set the goal to "jetty:run" and click "Run"

You should now have a Jetty server running on localhost:8080. Navigate to [http://localhost:8080/](http://localhost:8080/) to play with the application

To use the built in server adapters of Eclipse, instead of doing "Run As -> Maven Build..." you can do
- Run As -> Run on Server
- Select the server you want to run on, e.g. Apache Tomcat 8 and click ok
- *Do not use the suggested J2EE Preview server* as it is outdated, deprecated and does not support Servlet 3, which is required for this application

*** End of documentation