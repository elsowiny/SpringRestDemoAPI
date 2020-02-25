# SpringRestDemoAPI
Very minimal basic API without database coding.

******
	In order to run this program, you must have APACHE TOMCAT installed.

	https://tomcat.apache.org/download-90.cgi

	If using eclipse, go to file > new > other > server

	from there go to apache > Tomcat vx.x server *if prompted for the installation directory, then navigate to the folder where apache is downloaded *

	from

	TO RUN PROJECT --- right click on project and click > run as > RUN ON SERVER Select tomcat and click finish.
******

Basic api that sends back user information when requesting the url. 
To get a specific user - use the url of http://localhost:8080/spring-rest-demo/api/students/(**INDEX OF USER YOU DESIRE**)

--Added custom exception handler for case where you enter a studentId out of bounds of the list..
(this testing is done using an if statement that tests against the list size)

--Added generic exception handler for case when user inserts random chars after the api request which is returned in JSON format.