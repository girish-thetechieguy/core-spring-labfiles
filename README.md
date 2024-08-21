# Core Spring and Spring Boot Lab Projects

Labs for the Core Spring and Spring Boot courses

To import these labs into your IDE, import the parent pom `lab/pom.xml` as Maven projects or `lab/build.gradle` as Gradle projects.

Install Required Software
Install the following software if they are not installed already on your machine.

Java 11:

Oracle Java 11
Open JDK Installations
REST client

curl or
Postman
Build the Projects
Build the projects under core-spring-labfiles/lab directory. This will download and install required dependencies to local repository.

Windows:

COPY
mvnw clean install
MacOSX or Linux:

COPY
chmod 755 mvnw
./mvnw clean install
If you experience any build failure, check firewalls or proxy settings in the <Home-Directory>/.m2/settings.xml file.

Choose an IDE
While the lab projects can be built and run without an IDE, usage of a mainstream Java IDE is strongly encouraged.

The course assumes one of the following, although you may pick an alternate one with feature parity:

Spring Tools 4 (STS)
JetBrains IntelliJ
The Spring Tools 4 (STS) is a free IDE built on the Eclipse Platform with additional plugins to support Spring, Aspect Oriented Programming and the Tanzu Application Service deployment platform.

Import Projects Into Your IDE
Import the projects in core-spring-labfiles/lab into your IDE. You can import them as either Maven or Gradle projects.

For STS, you can perform "Import" from the lab directory, which will import the projects underneath it.

For IntelliJ, you can perform "Import Projects" via the parent pom.xml or build.gradle, and IntelliJ will automatically set them up as a multi-module project.

Verify that the projects are imported correctly.

STS:

IntelliJ:

Review the Using TODO Tasks article.

Troubleshooting
After importing the lab projects, your IDE may report errors, typically related to project dependencies. You can resolve these issues using the following techniques:

For STS:
Select all projects, right-click, Maven, Update Projects.
Clean all selected projects
Close & Open all projects
