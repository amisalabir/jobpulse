Final Project | JobPulse
IMPORTANT INSTRUCTIONS:



Please follow the detailed explanation discussed in the main live class.
You have to download the Application Sketch File from the Drive then open it with any browser. How to use the file has been shown in the main live class.
Apply your knowledge to add CRUD operations where necessary.
As it is your final project so we are not giving you any instructions on database table structures and data modeling. As a developer you should apply your knowledge for this.
We are not providing any HTML Templates for this project so that the project of each and everyone remains different.
For the authentication Login with Google is Optional.
You have to make a video of the project where each and every feature is visible and upload it in the root of your Github Repository for this project.
Must Submit GitHub Link.



You must need to see the Main Project Analysis Class before doing this assignment.



For  your Final Project, you have to make a Job Portal Management System name “JobPulse”.


 


There will be 3 types of User : Main Owner of The System, Companies and Candidates.


 


For the Main System Owner Company  and Job Providing Companies, you have to maintain Roles & Permissions(Optional).


 


Main System Owner Company can only login in the site.


 


Job providing companies can register and login in the site.


 


Candidates can apply to the posted jobs under any company. Before applying candidates must be logged in into the system.



For The Owner of the system, you have to develop these Modules:


Frontend: Home Page, About Page, Jobs Page, Contact Page, Login Page.


The Login Route will be different for the Main Owner.


Backend: Dashboard, Companies, Jobs, Employee(Optional), Blogs, Pages, Plugins, Accounts Settings


 


For The Job Providing Companies, you have to develop these Modules:


Frontend Part: Login, Registration and Forget Password


Backend: Dashboard, Jobs, Employee(Optional), Blogs , Plugins, Accounts Settings.


 


For Job Providing company, Blogs Feature on backend, need to add just as a plugin. No need to develop as a whole functional feature.


 


* Employee module is declared as optional for Owner of the system and Companies but you have to keep it as a plugin. If you do not develop this feature with Roles and Permissions then just keep this as plugin card like other plugins.


 


For The Candidates, you have to develop these Modules:


Frontend Part: Login, Registration and Forget Password


Backend: Dashboard, Jobs, Profiles, Accounts Settings



Application Sketch Template Link:
Make sure you download this file and open it with any browser (Ref: Main Live Class)


https://drive.google.com/file/d/1yftKVqW-YrMIkvhq9BE2nO-Us094P5sL/view?usp=sharing
============================================
User Registration and Authentication: Users can create accounts, log in, and manage their profiles securely.

Job Listings: Employers can post detailed job listings, including job descriptions, requirements, location, and more.

Advanced Search: Job seekers can filter job listings based on various criteria such as location, industry, experience level, and more.

Application Management: Job seekers can submit applications for job listings and track their application status.

Messaging System: A built-in messaging system facilitates communication between job seekers and employers.

Resume Upload: Job seekers can upload and manage their resumes, making it easy for employers to review qualifications.

Admin Panel: An admin panel provides administrators with the ability to manage users, job listings, and oversee the platform's operations.

Responsive Design: The application is designed to be responsive, ensuring a seamless experience on both desktop and mobile devices.

Notifications: Users receive email notifications for job application updates, messages, and more.

Technologies Used:

Backend: Laravel PHP framework
Frontend: Vue.js JavaScript framework
Database: MySQL or any supported database system
Other Technologies: HTML, CSS, JavaScript, AJAX, REST API
==================================
Instructions to run:
run composer update instead of composer install also run php artisan

DB_HOST=127.0.0.1 
DB_PORT=3306 
DB_DATABASE=
DB_USERNAME=root

~composer install
~npm install
~npm run dev
DB_PASSWORD= 
~php artisan migrate:fresh
~php artisan db:seed
~php artisan serve