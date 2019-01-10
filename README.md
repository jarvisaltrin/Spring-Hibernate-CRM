# Spring-Hibernate-CRM
## Motivation
This respository was created as a project from Udemy Spring and Hibernate tutorial. 
The course is titled Spring and Hibernate for Beginners (includes SpringBoot) by Chad Darby.

## Description and Features
By integrating two simple Web appilcation technologies: Spring MVC and Hibernate and also integrating a Service Fascade design pattern.
We build a simple CRUD application allowing to Create, Read, Update, Delete and Search records from database.
It is a Web application where you manage a list of clients (CRM - Customer Relationship Management). 
The database used is MySQL and Hibernate ORM is used for communication.

### Architecture
The browser sends the request to the Controller (Spring MVC). The controller find the method based on mapping specified (eg. @ReguestMapping).
In this specific application, the method will communicate with Service Fascade Object which will delegate the request to Data Access Object (DAO) object. 
DAO is responsible for communicating with database. Information retrieved from database will pass to Controller through service layer through DAO.
The Controller returns appropriate view and model to the browser.

## Concepts Covered
Java EE, Spring MVC, Hibernate, MySQL, DAO (Data Access Object), Data binding, Service Fascade Design Pattern
