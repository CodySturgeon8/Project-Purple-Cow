FUTURE UPDATES:
! Set up Dockerfiles and docker-compose.yml files correctly for single command start up as I ran out of time before setting this up properly !
! Fix update and delete buttons to be the same size when editing a single item !
! Allow easy change of port by command line arguments or another way through docker !

HOW TO START APPLICATION:
A local MySQL instance should be running before starting up the application, along with a database created named 'fearlessdb'.
You can use XAMPP for easy setup. Once installed, open the application which will give you a control panel. Simply click start for both Apache and MySQL, then click on Admin for MySQL. This will open a web page that displays a dashboard of your MySQL instance. Simply create a new database named 'fearlessdb', then you are all set. Keep XAMPP running.
Now open up the project in any editor, or navigate to the project folder in command prompt. You will need two instances of command prompt or terminal running.
In one of the terminal windows, cd into client, and the other cd into server.
In the window in the server folder, run 'npm install' and then 'node server.js'. In the other window that is inside client run 'npm install' and then 'npm start'
Navigate to http://localhost:3000 to view the application.