# Index
1. main.py (Skeleton) :  Later we’ll add routes, initialize our db object, and configure logging in main.py

# Part-1

- Flask uses the concept of blueprints to make application components and support common patterns across the application. 

- Blueprints help create smaller modules for the application making it easy to manage. Blueprint is highly valuable for larger applications and simplifies how large applications work.

- We’ll structure the application into small modules and keep all our application code in the /src folder inside our app folder. So, go ahead and create a src folder inside your current working directory and then create run.py file inside it.

- Here we have defined the config, imported create_app, and initialized the application. 

# Part-2

- Next we’ll move the config to a separate directory and specify environment-specific configuration. 
We’ll create another directory /api inside src and export config, models, and routes from api directory, so now create a directory inside src called api and then create another directory called config inside api.