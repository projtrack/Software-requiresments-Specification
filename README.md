 ## Projtrack - Software Pipeline Dashboard -(SRS) Document
 
 #### Project Name
 Projtrack - Project Management Pipeline Dashboard
 #### Date 
04/02/2022
 #### Version 
 1

## 1. introduction
#### Purpose:
The purpose of this document is to build project managment software with the ease of having popular tools intrergrated into one centeral place. This Document is intended for Stake holders and Devlopers

#### Document Conventions
This section will Explain and termanolgy that is used in this document

#### Intended Audience
The main audience of this document includes the developers of this project Developers are supposed to use this document in the development phase to the structure and design of each component

#### Scope
This Software Design Description (SDD) document provides necessary information about Projtrack - Project Pipeline dashboard . This document includes design principles of the software with its requirements, functionalities and necessary definitions. The information is aimed to guide any programmer to understand our design and be an assistant in the development phase.
	
## 2. General Description

#### Product Features
|Product/Service       |Feature            |Benefit         |
|----------------------|-------------------|----------------|
|Stipe Intergration    |Payment Prosessing | Secure Payments|
|React                 |UI framework   | Opensource & Secure|
|React Native  | Mobile UI UX framework     | Cross platform|
 | Docker | Deployment| Scalable and Secure|
 
#### User Class Characteristics
- Administrator
	- Will Have have Full access to Database. We will have the assumption that this user will be have the technical Ability to be able to manage the system at a Micro Level. This will Include
		- Full Database Access.
		- The Ability to Update API Keys for the services that will be used in this project.
		- Will have the Ability to Run Migrations and Backups
		- Will be able to set up Cron jobs to run task's a certian times
- Project Manager
	- Access to Customer Database (Full Crud)
	- Access to Setting up Project Hours & Forcasts
	- Creating and Sending Invoices
	- 
- Devlopers
	- 
- Support Staff
	- 
- Consumers/Customers 
	- 
	
#### Operating Enviroment
This project is a Web/Mobile application so it will need A server and client server for hosting the Client Website.
#### Dependencies
The application website Frontend will be written in React as it has lots of support and is quite a flexable frontend framework. The Mobile apps will be written in React native as we are using react for the frontend and should be able to use the Components we made in react in react native without to much hastle. The backend will be written in Golang as it is a highly scalable language and lastly the database we will use will be Postgress.
## External Interface Requirements

#### User Interfaces
##### Mobile Application
##### Website Application

#### Hardware Interfaces
#### Communication Interfaces
#### Software Interfaces
