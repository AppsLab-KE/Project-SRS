### Sample Project SRS Adapted from [Apps:Lab](https://appslab.co.ke/)

## Company Overview

In here you give a brief about the company working on the Software.

## Travel Management System
This is a travel management system to manage all your company expense on travels and accommodation.

#### Problem statement
In this section you write the client problem statement as per the client. It should be brief and straight to the point.

#### Proposed solution
In this section write a brief proposed solution according to your technical understanding and to the best of your knowledge. You can cite some links from you R&Ds

### Key Features
This will be the core of the project SRS. It should explicit, understandable by the client but easy to interprate to code by developers. To achieve this write it in user story format; The title is the story and the bullets are the "checklist" 
##### User Auth
- Each user using the system has a login credential to access system functionalities.
- User should be able to login in with email and a password
- Password should be more than 8 characters
- Etc
##### Roles and Permissions
- The system has permissions and roles for users. 
- Users are assigned different role and permission to perform different action in the system - for example approvals and the roles also give access to different sections in the system
- Etc
##### Department and HOD 
- Company department and there head of departments module.
- Department should have one or more HOD
- Department are unique by name
- Etc
##### Hotels and Accommodation 
- Management of recommended hotels and accommodation by the company on commission based model
- Etc
##### Mode of travel 
- Employee different mode of travel for example Air, road, rail, sea
- Etc
##### Travel Group 
- Manages different company travel groups, example managers, casuals etc travel groups.
- Travel group – this helps to manage and assign different travel groups to different job groups.
- We can have international and local company travel groups.
- An employee can be assigned to different travel groups.
- Etc
##### Company setup 
- Company details and information example logo, company name, country
- Etc
##### Job group 
- Module for managing different job group within the company
- Etc
 ##### Location and maps 
 - This module manages travel locations and destinations on the map.
 - Etc
##### Travel management 
- This module allows employees to apply for travels and admin will monitor and approve travels, 
- User can view their active travels and travel status, 
- Admin can disapprove travels.
- Etc
##### Travel allowance and expense 
- Travel expense tracker attract the allowance awarded to employee traveling and their travel expense.
- Etc
##### User/Employee profile 
- This module allow employee/user to view his profile and his her travel and activities
- Etc
##### Currency 
- For managing different currencies for example when an employee is flying to the US, his / her travel currency will be dollar.
- Etc
##### Reports 
- Generate travel reports from the system
- Etc
##### Travel notes and feedback 
- Allow the employee to update notes and give feedback to hr during and/or after travel
- Etc
##### Travel gallery 
- This module gives the company employee an option to share their travel pictures on the company travel gallery and company social media.
- Etc

### System solution
Due to the nature of your business we propose you have: - More details to go here
#### Backend/Dashboard application and/or admin system management. 
Your backend/admin panel details goes here

The admin/dashboard/backend application will be mostly used by the company management staffs.
It will used to manage, monitor, update and control the whole system. 
Super admin will be able to add staff and assign them role and permission and set company profile. 
Respective staff will be able to perform their respective task(s) per role(s) /permission(s) as per their job description. 
Staff actions and pages to view will be filtered by roles and permissions set. 
#### Landing page for guest customers. 
Write website/landing page details here
The landing web application will allow guest and customer view the service offered by the travel company.
The landing page will act as the company website with all the services, company contact, company profile.
#### Mobile Application
Write mobile application features here
List the features of the mobile apps and its functionalities here;
The mobile app will the following features :
  ##### Sign in and Signup  
  - Employee should be able to create accounts on the app and login
  - Etc
  ###### Hotels and Accomodation 
  - View all hotels and accomodation places offered by your company.
  - Etc
  ##### Travel Modes 
  - Users should be able view all modes of travel in the app
  - Etc
  ##### Travel Groups 
  - A user can be in one or more travel group
  - Etc
  ##### Location and Maps 
  - App should show maps for travel locations and destinations
  - Etc
  ##### Travels
  - Employee should be able to apply for travels, view approval status for their travels
  ##### Travel Allowance and Expense Tracker 
  - Employee should be able to track their allowances and expenses of each travel on the app
  - Etc
  ##### Feedback 
  - Allow users to submit feedback for a travel/tour
  - Etc
  ##### Travel Gallery 
  - Allow users to add pictures to their past travels and other people can also view this pictures.
  - User can share their photos with company social media
  - Etc
#### API
Give detail about API here 
API is an application interface that exchanged information between two or more applications. 
APIs provide extra security while sharing information. 
Think of API as the channel we will use to exchange information between the backend application (dashboard), mobile application and any third party application. And all the information will be stored in one central database (company database).
#### Database
Database details goes here
The system will use a single relational database and a backup database for all the applications database.
The database will be backed up automatically to avoid data loss. 
#### Security
Security details goes here
We prioritize application security and we focus more on application security to make sure that the users who use the system transact on a secure and protected system. We use token based requests and oauth authentication. 
Validate every transaction and http request in each step in the system..... 
#### Payment Gateway
Payment details in case there is a payment in the system
The following payment methods will be used in the system. 
    1. Mpesa
    2. Cash
    3. Debit/Credit Cards

### Technology Requirements
You tech stack goes here 
The system will be developed using the latest technology. We will use the following technology to develop the web application;
- Laravel framework and PHP – For server-side
- HTML5, CSS3, VueJs – For frontend (interface).
- OAuth, 2FA, Bycrt, token  – For authentication, encryption and security

And for mobile app;
- Kotlin – since we will be communicating with the native features of android framework and phone hardware, we will use Kotlin to develop the mobile application
- XML – for mobile application frontend (interface)

And for database;
- MySQL 

### Non- Technology Requirements
List you non-technology requirements here
The web app will require up to date modern browser installed  (chrome is highly recommended) on tablet, laptop or computer.Devices preferred will be laptops, desktop computers or tablet for the staff. But the web application will be adaptive and responsive – which mean it will be able to work perfectly even on a phone.
The application will require data or Wi-Fi connection to be accessible over the internet
Mobile applications are to be Android 4.4 (android kitkat) version and above.The applications will require internet connectivity to run
99.9% uptime server. This is a gurarentee from our end as the service provider. 

### NOTES
In case of any requirement update we will update the document and inform you.

### Contacts
You contact detail goes here




