​​CS 255 Business Requirements Document Template​ 

 

​​Complete this template by replacing the bracketed text with the relevant​ information. 

 

​​This template lays out all the different sections that you need to​ ​complete for Project One. Each section has guiding questions to prompt​ ​your thinking. These questions are meant to guide your initial responses​ ​to each area. You are encouraged to go beyond these questions using what​ ​you have learned in your readings. You will need to continually reference​ ​the interview transcript as you work to make sure that you are addressing​ ​your client’s needs. There is no required length for the final document.​ ​Instead, the goal is to complete each section based on your client’s​ needs. 

 

​​Tip: You should respond in a bulleted list for each section. This will​ ​make your thoughts easier to reference when you move into the design​ ​phase for Project Two. One starter bullet has been provided for you in​ ​each section, but you will need to add more.​ 

​​System Components and Design​ 

Purpose 

​​What is the purpose of this project? Who is the client and what do they​ ​want their system to be able to do?​ 

​​The purpose of this project is to design a web-based system for​ ​DriverPass that helps students prepare for​ their DMV driving exams ​through online learning​, practice tests, and behind-the-wheel driving lessons.  

​​DriverPass wants a​ centralized system where customers can register, purchase training ​packages, schedule driving lessons​, complete online ​practice exams, and​ monitor ​their learning progress.​  

The system should also support employees by allowing them to manage ​customers, appointments, reports, and​ system administration while ​providing secure access based on user roles​. 

 

 

​​System Background​ 

​​What does DriverPass want the system to do? What is the problem they want​ ​to fix? What are the different components needed for this system?​ 

​​DriverPass was created because many students fail​ their DMV driving exams ​due to​ inadequate ​preparation.​  

​​The company wants to​ improve ​driver education​ by combining online learning materials with practical ​driving instruction.​  

Customers should have access to:  

Online practice tests  

Online learning materials  

​​On-the-road driving lessons​  

The system must allow customers to schedule, modify, and cancel appointments online.  

The company ​wants the system to​ synchronize with ​DMV updates so​ that practice tests and educational ​materials remain current.​  

​​The system will​ also maintain customer ​information, lesson schedules,​ ​instructor assignments, vehicle assignments, and​ activity logs while supporting secure cloud-based access. 

 

 

​​Objectives and Goals​ 

​​What should this system be able to do when it is completed? What​ ​measurable tasks need to be included in the system design to achieve​ ​this?​ 

​​Provide students with​ an easy-to-use ​online training​ platform.  

Allow customers to register and purchase driving lesson packages.  

Enable customers to schedule, modify, or cancel appointments online.  

Track student progress on online courses and practice tests.  

Maintain accurate ​records of​ customer information and driving lessons.  

Assign instructors and vehicles to scheduled appointments.  

​​Allow administrators to manage users​, permissions, and customer accounts.  

Synchronize practice tests and driving regulations with DMV updates.  

Generate reports showing reservations, customer activity, ​and account​ changes.  

Provide secure ​cloud-based access from​ computers and mobile devices. 

 

 

Requirements 

Nonfunctional Requirements 

​​In this section, you will detail the different nonfunctional requirements​ ​for the DriverPass system. You will need to think about the different​ ​things that the system needs to function properly.​ 

 

​​Performance Requirements​ 

​​What environments (web-based, application, etc.) does this system need to​ ​run in? How fast should the system run? How often should the system be​ ​updated?​ 

 

The system should ​operate as a web-based application accessible through​ modern ​web browsers.​  

The system should also ​support access from mobile devices​.  

Pages should load quickly and respond efficiently during customer interactions.  

Customer reservations and ​updates should be processed immediately​ while connected to the internet.  

​​DMV information should be updated​ automatically ​whenever new rules or​ ​practice questions become available​.  

Reports should be generated without noticeable delays. 

 

 

​​Platform Constraints​ 

​​What platforms (Windows, Unix, etc.) should the system run on? Does the​ ​back end require any tools, such as a database, to support this​ ​application?​ 

The application ​should be cloud-hosted.​  

​​The system should support​ Windows, macOS, Android, and iOS devices through a web browser.  

A secure relational ​database should store customer​ records, appointments, practice tests, lesson schedules, and reports.  

Reliable ​internet access is required for updating and​ modifying information.  

​​Cloud hosting should handle backups​, availability, and disaster recovery.  

 

 

 

​​Accuracy and Precision​ 

 

​​How will you distinguish between different users? Is the input case-​​sensitive? When should the system inform the admin of a problem​? 

Every user must ​log in with a unique​ account.  

​​Different users should​ receive different permissions ​based on their​ assigned ​role.​  

Customer records, appointments, and lesson information ​should remain​ ​accurate and​ synchronized.  

​​The system should record who creates, modifies, or cancels reservations.​  

​​The system should notify administrators​ when ​errors​ occur ​or unusual​ activity is detected.  

Reports should accurately reflect all system activity. 

 

 

​​Adaptability​  

​​Can you make changes to the user (add/remove/modify) without changing​ ​code? How will the system adapt to platform updates? What type of access​ ​does the IT admin need?​  

 

​​Administrators should be able to add, disable, or modify user accounts​ without changing program code.  

​​The system should allow packages to be disabled​ when necessary.  

Future updates ​should allow additional packages and features​ to be added.  

​​The cloud-based architecture​ should ​simplify software updates​ and ​maintenance​.  

​​The IT administrator should have complete control over user​ accounts and permissions. 

 

 

​​Security​ 

​​What is required for the user to log in? How can you secure the​ ​connection or the data exchange between the client and the server? What​ ​should happen to the account if there is a “brute force” hacking attempt?​ ​What happens if the user forgets their password?​  

​​Users must authenticate with a username and password.​  

​​Password reset​ functionality should ​be available for customers who forget​ their password.  

User permissions should be assigned according to job responsibilities.  

Communication between users ​and the server should be encrypted​.  

Customer ​personal information and payment information should be​ securely ​stored​.  

Failed login attempts should be monitored, and repeated unsuccessful ​attempts should temporarily lock the account​.  

​​The IT administrator should have the ability to reset passwords and​ disable user ​accounts when necessary.​ 

 

 

Functional Requirements 

 

​​Using the information from the scenario, think about the different​ ​functions the system needs to provide. Each of your bullets should start​ ​with “The system shall . . .” For example, one functional requirement​ ​might be, “The system shall validate user credentials when logging in.”​ 

 

​​The system shall allow customers to create​ user accounts.  

The system shall authenticate users ​during login.​  

​​The system shall allow customers to reset forgotten passwords.​  

​​The system shall allow customers to purchase training packages.​  

​​The system shall allow customers to schedule driving lessons​ online.  

​​The system shall allow customers to modify​ existing appointments.  

​​The system shall allow customers to cancel appointments.​  

The system shall assign instructors and vehicles to scheduled lessons.  

The system shall store customer personal and payment information.  

​​The system shall provide online​ practice exams.  

The system shall ​display customer progress for completed​ and in-progress practice tests.  

The system shall synchronize DMV rules, policies, and practice questions with official updates.  

​​The system shall generate activity reports​ showing reservation changes and user actions.  

The system shall allow administrators to manage user accounts and permissions.  

The system shall allow secretaries to create and manage customer appointments.  

The system shall allow instructors to record lesson comments and progress.  

The system shall maintain audit logs for system activity.  

 

 

​​User Interface​ 

​​What are the needs of the interface? Who are the different users for this​ ​interface? What will each user need to be able to do through the​ ​interface? How will the user interact with the interface (mobile,​ ​browser, etc.)?​  

The interface should ​be web-based and accessible from​ desktop computers, laptops, ​tablets, and​ smartphones.  

Customers should be able to:  

Register  

Log in  

Purchase packages  

Schedule appointments  

View lesson schedules  

​​Complete online practice tests​  

Track learning progress  

Secretaries should be able to:  

Register customers  

Schedule appointments  

Modify appointments  

Cancel appointments  

Instructors should be able to:  

​​View assigned lessons​  

​​Enter​ driver notes  

Record lesson information  

Administrators should be able to:  

Manage users  

Reset passwords  

Generate reports  

Maintain the system  

The ​dashboard should display online test progress​, student information, driver notes, instructor information, and lesson schedules similar to the interface sketch provided by DriverPass. 

 

 

Assumptions 

​​What things were not specifically addressed in your design above? What​ ​assumptions are you making in your design about the users or the​ ​technology they have?​  

​​Users have​ reliable internet access.  

Customers possess ​basic​ computer ​or smartphone skills.​  

DMV will provide updates electronically.  

Cloud hosting ​services provide​ sufficient reliability ​and availability.​  

​​Customers provide accurate​ registration information.  

Payment processing services operate correctly.  

Employees ​receive training before using the system.​ 

 

 

Limitations 

​​Any system you build will naturally have limitations. What limitations do​ ​you see in your system design? What limitations do you have as far as​ ​resources, time, budget, or technology?​ 

Internet access is required for most system functions.  

​​The project schedule limits the amount of functionality included in the​ ​initial release.​  

​​Future customization​ of lesson packages will require additional development.  

​​The system depends on timely DMV updates.​  

​​Budget and time constraints may​ delay ​advanced features​ until future versions.  

​​Mobile functionality depends on browser compatibility​ across devices.  

 

Gantt Chart 

​​Please include a screenshot of the GANTT chart that you created with​ ​Lucidchart. Be sure to check that it meets the plan described by the​ ​characters in the interview​. 

 

DriverPass Gantt Chart:  

 

 

 

 

 

 

 

 

 

 

References:  

 

Southern New Hampshire University. (n.d.). CS 255 DriverPass interview transcript. Southern New Hampshire University. 

 
