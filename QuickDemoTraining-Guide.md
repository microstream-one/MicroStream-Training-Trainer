<h1>Quick Demo Guide</h1>

<h3>Target of the unit</h3>

1. Participants should see how easy the usage of MicroStream can be.
2. Should see the basic architecture of MicroStream
3. 

<h3>Needed preparations</h3>

1. Any java IDE or text editor
2. Maven installed or available via IDE
3. Annotation Processing enabled in the IDE (Eclipse)
4. GIT installed on the system or available via IDE

<h3>Necessary Links</h3>

1. GIT Repo: https://github.com/microstream-one/microstream-quick-demo.git

<h3>Training</h3>

1. <strong>Explanation about the training</strong>
	1. Needed preparations see above
	2. Duration of the unit
	3. Targets of the unit
2. <strong>Explanation about the project</strong>
	1. Micronaut project
	2. One action controller class to do the "magic"
3. <strong>Clone the project from repository see link above</strong>
	1. `$ git clone https://github.com/microstream-one/microstream-quick-demo.git`
	2. Or using the GIT functionality of an IDE
4. <strong>Starting the project once to ensure a proper configuration</strong>
	1. Switching to folder "MicroStreamQuickDemo"
	2. Call `.\mvnw mn:run`from commanline
	3. Or start **Application.class** as java application within an IDE
	4. Result in the console: A big *Micronaut* writing and 'Server Running: http://localhost:8080' at the end.
5. <strong>Calling http://localhost:8080 from browser or CLI</strong>
	6. `curl localhost:8080/action`
	7. Call http://localhost:8080/action from browser
	8. Result at the console: 'Still some more java code necessary to do fancy stuff'
6. **Adding *MicroStream* dependencies to pom.xml**
	7. Getting dependencies from https://manual.docs.microstream.one/data-store/getting-started
	8. Open pom.xml
	9. Adding following dependencies to the dependency section of pom.xml
 ```xml
<dependency>
	<groupId>one.microstream</groupId>
	<artifactId>storage.embedded</artifactId>
	<version>04.01.00-MS-GA</version>
</dependency>
<dependency>
	<groupId>one.microstream</groupId>
	<artifactId>storage.embedded.configuration</artifactId>
	<version>04.01.00-MS-GA</version>
</dependency>```
