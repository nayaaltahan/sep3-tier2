# sep3-tier2
Group project for my third semester project

This repository contains the Java code, the second tier of my semester project
The following link will redirect you to some design UML diagrams used to the design the entire system:
https://drive.google.com/drive/folders/198_-HTjOyh3Cn5tFPa6ceQif-axDoyRm?usp=sharing

The project is to create a heterogeneous system that is split into three tiers.
The data tier, programmed in PostgreSQL
The application tier, programmed in Java, can be found in this repository
The presentation tier, programmed in C#, as an ASP.NET web application.

The first tier is connected to the second layer through SOAP Web services,
where the first tier invokes web services methods on the second tier providing
the ability to pass data through SOAP messages.

The second tier is connected to the third layer through Java Database
Connectivity using a class that provides the second tier with methods to
manipulate the data in the database.
