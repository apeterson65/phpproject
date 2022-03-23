Final project for PHP
Creted by Andrew Peterson

	DB name: heroes
	Table: Heroes
		Fields:
			id (primary key)
			name
			realname
			rating
			teamaffiliation
			
Project directory structure
	heroAPI
		Includes
			Constraints.php
			DbConnnectlphp
			DbOperations.php
		v1
			Api.php

• So we have the following things in our PHP project.
• includes
• Constants.php: In this file we will define all the required constants e.g., database name, username, password etc. 
• DbConnect.php: This fill will contain a class where we will connect to our MySQL database.
• DbOperation.php: The actual CRUD operation is performed inside this file.
• v1
• Api.php: This is our API, we will send request to this file only from the android side. And this file will handle all the API calls.


In order to get the program to work I did have to redo the file path's in the Dbconnect on line 23 and Api on line 4. 