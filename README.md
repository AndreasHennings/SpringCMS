# Spring_REST_JPA

1. About
This is an implementation of a RESTful service using the Spring framework. Users can connect to the applications' services via HTTP request and perform basic 
CRUD operations. As an example, this application manages student data (id, name, date of birth, email).


2. Database Prerequesites
A local Postgres Database must be installed, started and ready to communicate via Localhost:5432. Database settings can be managed or altered by editing the 
application.properties file. The Database is configured to drop all data at restart.


3. Usage
Before using, the Database must be started. On Windows, psql.exe can be used. Name/Password is postgres/admin.
After the project is started, a Tomcat Server that can be reached via Localhost:8080/api/v1/student, which will reply with an empty list.
CRUD methods can be found in StudentController.java file.

4. This software is for testing purposes only and has no warranty whatsoever.
