CREATE WIREFRAME BEFORE STRATING ANY PROJECT

steps of bulding this simple app that represents one to many relationship
1- the first thing is to create ERD for users and post (one user can have many posts )

***************************
users table has:
id
first_name
last_name
email
password
created_at
updated_at
***************************

*********************
posts table has:
id
content
user_id---> forgin key came from one to many relationship
created_atupdated_at
******************************

2- next step is to forward engineer and test both tables if they work or not by writing select * from table_name;

3-nex_step is to install flask and pymysql inside terminal 
>python -m pipenv install flask pymysql                 ->success installing
>python _m pipenv shell                               -->get into shell
>python server.py                                     -->run our server

once we get pipfil and pipfile.lock thats mean we are ready to start writing our code.

3-start modulirize our files


4- first start in your models to create classes(each table should has a class with content) and implement the CRUD that we need in each class if we have more than one table


5-after finishing the class , will move to controller and create route for each link or button in html AND THE VARIBLAE NAME THAT WE NAME IT IN CONTROLLERS FILES WILL USE IT IN HTML TO IMPLEMENT JINJA SYNTAX


6-will move to html depending on the template that we returned from our route , will write the jinja SYNTAX


7-print each step and run it to see the output how it looks.


NOTE/SOMETIMES THE LINK WILL NOT DIRECT US TO THE SAME ROUTE IN THIS CASE JUST EXIT TERMINAL AND RE RUN THE SERVER.PY AGAIN AND IT WILL WORK.
