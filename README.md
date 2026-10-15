OntoGraf
====================

Protege Desktop plug-in that lets you visually and interactively navigate relationships in OWL ontologies.

OntoGraf is bundled with the default Protege Desktop installation.  This release replaces the default version with new axiom labelling.  More user documentation is available on the Protege wiki:

http://protegewiki.stanford.edu/wiki/OntoGraf

# New axiom labelling feature

<img width="800" height="435" alt="image" src="https://github.com/user-attachments/assets/87be8e7d-652a-4caa-a844-cc5ba914f6e5" />


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
