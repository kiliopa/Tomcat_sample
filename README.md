# Tomcat_sample
The example app has been packaged as a war file and can be downloaded here (Note: make sure your browser doesn't change file extension or append a new one).

The easiest way to run this application is simply to move the war file to your CATALINA_BASE/webapps directory. A default Tomcat install will automatically expand and deploy the application for you. You can view it with the following URL (assuming that you're running tomcat on port 8080 which is the default):
http://localhost:8080/sample

If you just want to browse the contents, you can unpack the war file with the jar command.

        jar -xvf sample.war
      
Note: CATALINA_BASE is usually the directory in which you unpacked the Tomcat distribution. For more information on CATALINA_HOME, CATALINA_BASE and the difference between them see RUNNING.txt in the directory you unpacked your Tomcat distribution.

from: https://tomcat.apache.org/tomcat-9.0-doc/appdev/sample/
