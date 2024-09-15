## This is a basic api I built with Flash, Connexion, and Marshmallow, in order to familiarize myself with what API's are and how they run.

## This API uses SQLalchemy for Database management. The database 'people.db' contains two tables, 'person' and 'note', as an example of one-to-many relationships within the API.

## Information about the endpoints, components, and paths can be found within 'swagger.yml'

## Models and Schemas can be found within 'models.py'

## To accsess the Swagger UI, type within the URL field.

## To set up the API:
## 1.) Set up a virtual enviornment using 'python -m venv venv' in the command line. 
## 2.) Activate the virtual enviornment by using .\venv\Scripts\activate in the command line,
##          Note- You may need to run on of the alternate activation scripts depending on what shell you are using (bash, powershell, etc.)
## 3.) Install the required dependencies using 'pip -r install .\requirements.txt'
## 4.) Next, initialize the database by using 'python database_setup.py' in the command line.
##           This script sets up the database with the 'person' table.
## 5.) Extend the database by running 'python extend_database.py' in the command line.
##           This script extends the database by adding the 'note' table.
## 6.) Activate the API by running 'python app.py' in the command line.
## 7.) Crtl-click on the server address within the terminal, and the browser will open the 'home.html', found in the templates folder.
