ReadMe

In order to run the application:

1. Open vagrant by going to the vagrant folder and entering "vagrant up", then ssh into vagrant by typing "vagrant ssh"

[Before running, if Flask and SQLAlchemy are not installed then install Flask by entering "pip install flask" then install sqlalchemy "pip install alchemy" in the terminal.]

2. Once in vagrant navigate to the folder that contains the "menu" folder, within which you will find the relevant files. 

3. Enter "python database_setup.py" in order to get the database set up and ready

4. Enter "python lotsofmenus.py" in order to enter the data into the database

5. Enter "python finalProject.py" in order to run the program itself

6. In your browser go to localhost:5000 in order to use the site

Other Points:

1. When someone visits a page the actions on that page will be run by Flask

2. JSON will present the relevant information for use in an API

3. You can edit the CSS in styles.css