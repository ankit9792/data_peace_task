#Data_Peace_Task

Data_Peace_Task is an rest api which is developed using ‘sails js’ framework of ‘node js’ and can be used to see user list, search any user, create a new user in database, update user’s details and delete a user.


Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
Prerequisites


What things you need to install the software and how to install them

1.  Node Js
2.  Sails Js (node js framework)
3.  Workbench (Mysql IDE)
4.  Postman (For api testing)


Installing

A step by step series of examples that tell you have to get a development env running

1.  Installing Node Js (For Windows)
-   Download the Windows installer from the Nodes.js® web site (https://nodejs.org).
-   Run the installer (the .msi file you downloaded in the previous step.)
-   Follow the prompts in the installer (Accept the license agreement, click the NEXT button a bunch of times and accept the default installation settings).

2.  Installing Sails Js
-   npm install sails -g

3.  Installing Workbench
-   Download workbench from http://dev.mysql.com/downloads/workbench/.
-   Run the installer (the .msi file you downloaded in the previous step.)
-   Follow the prompts in the installer (Accept the license agreement, click the NEXT button a bunch of times and accept the default installation settings).

4.  Installing Postman
-   Install Google Chrome.
-   Install the Postman extension for Chrome.


Running the tests

Follow these steps to run the sails server and test the api :-

1.  Adding data to database :-
-   Open workbench
-   Create new connection with host: localhost and user: root
-   Goto Import data
-   Browse and select the attached .sql file
-   Select “create new schema” option with name “data_peace”.
-   Click “import” button.

2.  Running the server :-
-   Open command prompt
-   Goto the api directory in command promt
-   Run command “npm install”
-   Run command “sails lift”

3.  Testing api :-
-   Open postman
-   Select request type (post, get, put, delete)
-   Enter server url with port and parameter (ex: http://localhost:1337/users)


Built With
•   Sails Js - The web framework used
•   Node Js – JavaScript Environment
•   MySql – Database Used





