Addressbook 
====================
#new change
# changes for test


![Addressbook Screenshot](addressbook_screenshot.png "Addressbook Screenshot"))


Running the example from the command line
-------------------
```
$ mvn jetty:run
```
# test comment

Open [http://localhost:8080/](http://localhost:8080/)


Importing in IntelliJ IDEA 14
--------------------
These instructions were tested on IntelliJ IDEA 14 CE. You can get it from https://www.jetbrains.com/idea/

To get the project up and running in IDEA, do:
- File -> New -> Project from Version Control -> Git
- The URL to use is https://github.com/vaadin/addressbook.git
- If you get a message about "Non-managed pom.xml file found". Choose "Add as Maven Project"
- If you get a message about no JDK or SDK being selected. Choose "Configure" and select your installed JDK. You can also set the JDK using File -> Project Structure
- To start the project, find the "Maven Projects" tab on the right hand side of the screen and navigate to
  - Vaadin Web Application -> Plugins -> jetty -> jetty:run
  - Click the play button or right click and select Run (Select Debug instead to run in debug mode)



*** End of documentation
