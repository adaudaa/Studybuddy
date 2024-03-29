# Campus Buddies
Software Engineering Group project.

Campus Buddies is an interactive online forum for shared learning and studying that allows students to find those with similar subjects that are located nearby in order to form study groups.

# Project Scope and Objectives
Our project is designed to allow users to make an account with us, where their information is then stored in a database. There is a forum system that makes it where users can communicate with each other.

# Setup
Create a database using MySQL Workbench and either match the information to lines 7 and 16-19 in StudyBuddy/website/\_\_init\_\_.py or edit those lines - ensure a schema exists in your connections that matches the DB_Name on line 7 or it will error out

Included in the root folder is a campusbuddies.sql file - this contains the queries to generate some filler data to render on the forums and elsewhere. Everything is fully functional but this will give some entries without having to create new enteries manually each time.

Create the venv and install requirements:
    commands: 
        python -m venv venv
        . ./venv/scripts/activate
        pip install -r requirements.txt
        python main.py

        After you run main.py for the first time, it will generate the tables in the database for you. Use Ctrl+C in the VSCode terminal to terminate the server, then run the campusbuddies.sql queries to generate some data.
        Then run [python main.py] again and you'll have some working data
``
