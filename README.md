# parent-pom-sample
A sample parent pom project, to manage the versions of the dependencies.

## Prerequisites
* To run the application you need to have git, mvn and JDK8 installed.

## Download
* Open command line and move to your workspace.
* Download project using your username: 
<br>`> git clone https://gitlab.com/kmponis-examples/parent-pom-sample.git`
* Go to project: 
<br>`> cd /parent-pom-sample`

## Run 
* Use terminal and move to your workspace
* Run in command line:
  <br>`> mvn clean install`

## Use
* Add to maven dependencies:
  ```xml
  <dependency>
  	<groupId>com.parent.pom</groupId>
  	<artifactId>parent-pom-sample</artifactId>
  	<version>1.0.0</version>
  </dependency>
  ```