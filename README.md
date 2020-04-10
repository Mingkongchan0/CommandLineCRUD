# CommandLineCRUD
.jar file for CRUD functions via command line arguments

Start cmd as Administrator and cd to directory containing the .jar file. 

## Running the application

>java -jar {jarname}.jar {argument}

>For example, java -jar CommmandLineCRUDtest-20200409.jar create
 
 Use the command above with any of the following arguments

* connect (Tests connection to SQLite)
* create (Creates a table with the appropriate columns and type)
* insert (Adds a record to the table)
* select (Displays a list of the records)
* delete (Deletes a record from the table)

## Differences between Ant and Maven

- Dependencies are introduced in a much more convenient manner in Maven (i.e. declaring the dependencies in pom.xml) whereas in Ant external libraries still have to be added to the project.
- Maven is pre-bundled with a 'lifecycle' consisting of multiple 'goals' (i.e. mvn clean install) that are similar to 'targets' which are manually defined/chained in Ant. 
- Maven also consists of lifecycles which are consolidated 
- Maven provides higher readability of depdencies that are declared in pom.xml, and myriad of plugins which broadens its functionalities.
