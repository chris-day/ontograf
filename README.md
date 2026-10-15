OntoGraf
====================

Protege Desktop plug-in that allows visual, interactive navigation of the relationships in OWL ontologies.

OntoGraf is bundled with the default installation of Protege Desktop.  There are no additional installation steps required.  Enable OntoGraf from the Window | Tabs menu.  More user documentation is available on the Protege wiki:

http://protegewiki.stanford.edu/wiki/OntoGraf

# Build and run tests
```
mvn clean verify
```
Or skip tests:
```
mvn clean package -DskipTests
```
Requires JDK 11+ and Maven 3.9.x. To explicitly use your installed Java 11:
```
JAVA_HOME=/usr/lib/jvm/zulu11-ca-amd64 mvn clean verify
```
The plugin JAR is produced at:
```
target/ontograf-2.0.4-SNAPSHOT.jar
```
Copy ontograf-2.0.4-SNAPSHOT.jar into your Protege plugins directory. Rename ontograf-2.0.3.jar to ontograf-2.0.3.jar.old. 
