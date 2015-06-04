Description:

           - This project provides a list of restaurants and their menus.
           
           - Authenticated users are allowed to add,edit& delete menu items and restaurants.
           
           - OAuth an open standard for authorization specifies a process for resource owners to authorize third-party access to their server resources without sharing their credentials.
           
           - A google plus signin is added to the application using OAuth2.0.
           
           
Installations :

             - Vagrant and VirtualBox.
             
             - git.
             
             - github for desktop.
             
             - python.
             
             
             

How to run the project in terminal(for mac)? :

             - vagrant init hashicorp/precise32.
             
             - vagrant up.
             
             - vagrant ssh.
             
             - cd /vagrant (This will take you to the shared folder between your virtual machine and host machine).
             
            - use sudo apt-get install python-sqlalchemy to install sqlalchemy.
            
            - use sudo apt-get install python-pip to install pip.
            
            - use sudo apt-get install Flask to install Flask.
            
            - Type ls to ensure that you are inside the directory that contains project.py, database_setup.py, and two directories  'templates' and 'static'.
            
            - type python database_setup.py to initialize the database.
            
            - type python lotsofmenus.py to populate the database with restaurants and menu items. 
            
            - Type python project.py to run the Flask web server.


            



1)python database_setup.py - initializes the database.

2)python lotsofmenus.py - populates the database with restaurants and menu items.

3)python project.py - Runs the Flask web server. 

