# sync-skills
Synchronoss Skills Management Tool

#Prerequisites for SERVER

 API Services & Database
 -----------------------

	1. In order to use this repository you need to first set up the API Services.
	2. Services are developed in php & mysql.  
	3. API Services (from api folder) has to be deployed either in XAMPP, WAMP or any other php server.
	4. Mysql backup file (db_dump.sql) has to be restored in MYSQL server.
	5. Update the config file in api folder with respective Database and API server details.



#Prerequisites for UI Application
	
	UI Appication is developed using framework Angular 4, So make sure available its dependencies before using it.
	
	1. Install NODE and Angular Cli globally.

#Set it up, following the instructions on the repository to run in local machine.

   Install npm packages/set up the application
   -------------------------------------------
	git clone https://github.com/siva-sncr/sync-skills.git

	
	Navigate to repository from terminal.
	run    "npm install" from terminal
	
	It will install all the npm packages described in the package.json.

	ng serve

	The ng serve command first compiles the application, then simultaneously re-compiles and runs the lite-server. Both the compiler and the server watch for file changes.

	Note: Make sure API services and DB data should be available before running the application server (ng serve).