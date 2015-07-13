Example Axis2 Maven project
===========================

This project is meant to show how to simply generate a service stub from a predefined WSDL file. It is a maven project so it needs [Maven ](https://maven.apache.org/) installed.

When you run "mvn clean axis2-wsdl2code:wsdl2code" in the project root the Java code will be generated in the proper target/generated-sources directory and your IDE should pick it up as a sources directory.

When you run "mvn clean install" it should create a complete deployable .war in the target directory.

At this moment there is no implementation of the ServiceSkeleton; I'll leave that up to the reader!
