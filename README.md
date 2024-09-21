
# TechStore frontend




## Installation
Open the project into vsode.
cd frontend
Install node modules  with npm

```bash
  npm install 
  
```
    then 
    

```bash

  npm run dev
  
```
to start the app.

app will start on port 5173.

## backend
Open the project into vsode.
cd backend
Install node modules  with npm

```bash
  npm install 
  
```
    then 
    

```bash

  npm run dev
  
```
to start the app.
make sure you have .env file present root folder.
app will start on port 5000.

## FrontEnd usage

you can login through admin credientials
 email: aizaz44@yahoo.com
  and password:123456 
  You can also register as user on site.
Admin can create delete and update products through dashboard which is only visible to admin. You can view product details by clicking on product and add it to cart by clicking on add to cart whichs being saved in database. refresh and access tokens are coming from backend through cookies and is not saved in local storage for security purposes.zustand is used for state managment .  
## TechStore Backend

prper errorhandling is done in server.js and in every controller . auth have route have controller for login registeration , refresh token and user profile data. TO create edit delete get single and get all products  controllers are  defined . refresh token and access token are sent through cookies and even if  you refresh page you will stay logged in and no session data will be lost . 

