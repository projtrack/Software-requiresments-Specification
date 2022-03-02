 ## Projtrack - Software Pipeline Dashboard -(SRS) Document
 
 #### Project Name
 Projtrack - Project Management Pipeline Dashboard
 #### Date 
04/02/2022
 #### Version 
 1

## 1. introduction
#### Purpose:
The purpose of this document is to build project managment software with the ease of having popular tools intrergrated into one centeral place. This Document is intended for Stake holders and Devlopers to help them with Feature and Tool devlopment

#### Document Conventions
This section will Explain and termanolgy that is used in this document

#### Scope
This Software Design Description (SDD) document provides necessary information about Projtrack - Project Pipeline dashboard . This document includes design principles of the software with its requirements, functionalities and necessary definitions. The information is aimed to guide any programmer to understand our design and be an assistant in the development phase.
	
## 2. General Description

#### Product Features
- The Ability to login to the application with their github that is linked to their company. It will allow the users to be able to add projects, Scope Projects , Create Project Khanban board
 
#### User Class Characteristics
- Administrator
	- Will Have have Full access to Database. We will have the assumption that this user will be have the technical Ability to be able to manage the system at a Micro Level. This will Include
		- Full Database Access.
		- The Ability to Update API Keys for the services that will be used in this project.
		- Will have the Ability to Run Migrations and Backups
		- Will be able to set up Cron jobs to run task's a certian times
- Project Manager
	- Access to Customer Database (Full Crud).
	- Access to Setting up Project Hours & Forcasts.
	- Creating and Sending Invoices.
	- Able to create and Send Proposals to Customers,
	- Creating Projects, Assigning Team Members (Support & Developers)
	- Creating Tickets and Managing Tickets Via Linear
	- Create a timeline of major changes to codebase as a visual refrence for Customers so they can Visualise every Major change to their code
		- Stretch Goals: 
			- Create Staging and Production Enviroments Via Docker, Vercel or someother Deploying tool
			- Track Commits on a project
			- View test reports on CI/CD Pipeline for projects that are using TDD, Rely on Unit tests.
- Devlopers
	- View Project hours and Forcasts
	- View Customers Details and Project Details
	- Record Time Spent on projects
	- Leave Notes on a Project( Documentation)
	- View Tickets and Change status of a ticket
	- View Git Commits
		- Stretch Goals: 
			- Create Staging and Production Enviroments Via Docker, Vercel or someother Deploying tool
			- Track Commits on a project
			- View test reports on CI/CD Pipeline for projects that are using TDD, Rely on Unit tests.
- Consumers/Customers 
	- View Current Hours Spend,
	- View Current Months Hours,
	- Log a Ticket,
	- Respond to a ticket,
	
#### Operating Enviroment
This project is a Web/Mobile application we will be using supabase for the Database and Nextjs for the Serverless functions.This project will have both a Website Application and a mobile application. The mobile Version Will be Intended to be ran on an Ipad.

#### Dependencies
The Website will be written in Nextjs and hosted with vercel. We've Chosen this service as its scalable and supports serverless functions out the box. It requires no configuration for Hosting. For the Database we've Choosen to use Supabase. We've choosen to use Supabase cause of the benefits of having the Authrisation done at a Database level is more secure than doing it through application level.The mobile application will be written in Flutter I've choosen this language as it Supports Multi platform support. I can also make native Mac and Windows applications with it.
.
## External Interface Requirements

#### User Interfaces
##### Mobile Application
##### Website Application

#### Hardware Interfaces
#### Communication Interfaces
#### Software Interfaces
