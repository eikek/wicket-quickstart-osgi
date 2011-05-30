wicket quickstart osgi
======================

This is a minimalistic project that shows the wicket-quickstart application in action together with OSGi.


Organization
------------

The project was originally created using [pax]{http://wiki.ops4j.org/display/ops4j/Pax} and modified to make it
more simple.

All dependencies listed in the  `pom.xml` of  `provision` project are deployed to the OSGi container. The
`wicket-quickstart` project contains the wicket application, wich is also deployed to the OSGi container.


Startup
-------

Compile the project using maven `mvn clean install`. Then everything can be fired up using `mvn pax:provision`


Navigation
----------

The wicket quickstart application is available from: http://localhost:8080/wicket-quickstart

There are two UIs available: 

1. felix web console: http://localhost:8080/system/console  (login is admin/admin)
2. felix shell (`help` shows a list of commands, `felix:lb` lists all bundles)


