Description:

           - This project provides a list of restaurants and their menus.
           
           - Authenticated users are allowed to add,edit& delete menu items and restaurants.
           
           - OAuth an open standard for authorization specifies a process for resource owners to authorize third-party access to their server resources without sharing their credentials.
           
           - A google plus signin is added to the application using OAuth2.0.
           
           - A local permission system is also added to the project for protecting users by not getting thier data modifying thier data by other users.
           
           - A viewer can just only see the restaurants and thier menu items but an authorized person can add,edit or delete restaurants and menu items.
           
           
Installations :

            - Vagrant and VirtualBox.
             
            - git.
             
            - github for desktop.
             
            - python.
            
             
            - Visit http://console.developers.google.com and login to your google account.
            
            - Click Create project and name your project.google automatically creates a project id.
            
            - Once the project is created u will be redirected to project dashboard.
            
            - Now click on Apis&auth and select credentials.
            
            - In the OAuth section click create new client ID and select web application and then click configure consent screen.
            
            - In the consent screen provide email adress and product name and save changes and then click create client ID.
            
            - Now we will get client id for web application.
            
            - click on download json to download the json file.call it client_secrets.json and store in project.
            
            - In login.html give the client id to data-clientid = "your client id".

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
            
            - In your browser visit http://localhost:5000 to view the restaurant menu app.


