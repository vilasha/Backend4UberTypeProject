# Backend4UberTypeProject

Back end for a project kind of Uber, with REST api to the front end and unit tests

Cross-Ride is a ride-sharing application developed by a startup company. Cross-Ride allows its users to register as drivers and/or riders. Registered drivers and riders advertise their usual travel schedule on the application. At the end of shared ride driver sends a request to the server with driver id, rider id, the start time of shared ride, the end time of shared ride and the distance covered in kilometers.

Development Environment:

	Java 8

	Any IDE

	MySQL 5.6+:
  
	Cross-Ride applications require MySQL database to store its data. Make sure to update application.properties with spring.datasource.URL(change hostname only), spring.datasource.username, and  spring.datasource.password. You are free to choose MySQL service in a cloud or installed on the local machine or MySQL container.
	
	The Cross-Ride application uses liquibase for Database changes. In case you need to update the Database, please create a new changeset file in resources/db.changelog folder and include the newly created file in db.changelog-master.xml
    For more details on liquibase follow https://www.liquibase.org/documentation/changeset.html 
	
	Cross-Ride Application:
	To start the application run CrossRideApplication.java main method from your IDE.