</h1>

INTRODUCTION:-

This is a Simple User Registration & Login systems app done with Node.js Framework using MongoDB(Atlas) as the data store, Express as the routing system, Body-parser as the parser for webpage, Express-session used  to track the user's session and of course Mongoose to make interacting with Mongo from Node easy.

Running the tests

•Registration Form :-

The Registration page bsically allows the users to register their account by the perticular fields such as Email, Username, Password.

In registration page there will also an option of login , for those users who already have been regiterd .
![Registration](https://user-images.githubusercontent.com/86963570/125126507-d7262c80-e118-11eb-82eb-eeaf0d0901ab.png)


•Login Form :-
 
If the user has been registered on the app, can login by passing the credentials. The system will check whether the creadential entered by them is already stored in the database or not . 
![Login_1](https://user-images.githubusercontent.com/86963570/125126386-a8a85180-e118-11eb-9d3c-5d6a89c4f389.png)


•User's Profile:
After the user logged in, a simple profile with the user's username and password will be displayed with a session Logout button.
![Profile_details](https://user-images.githubusercontent.com/86963570/125126476-cd9cc480-e118-11eb-8c64-b8b797c7fb9b.png)

•Password Reset:

If the user forget his/her password, can reset by entering the registered Email id <br>and reset the password.That perticular user password updation will be effected in database .
![Change_password](https://user-images.githubusercontent.com/86963570/125126604-f91faf00-e118-11eb-97c1-858fabf0de72.png)

DataBase:
Here we use **[MongoDB Atlas(Cloud)](https://www.mongodb.com/cloud/atlas)** as the database. Here we have two collection created, named as:
- users.
- sessions.

A Collection(**Users**) is populated with the user's credentials.
![collection_user](https://user-images.githubusercontent.com/86963570/125126660-0d63ac00-e119-11eb-9161-9db8ba8f4744.png)

Software requirements :-
- ***[Node.js](https://nodejs.org/en/)***
- ***[Node Package Manager](https://www.npmjs.com/get-npm)***
- ***[MongoDB (Atlas)](https://www.mongodb.com/cloud/atlas)***
-
The server will start Running on
+ http://localhost:3002/


Conclusion:-
This project is basically provides a Registration and login system where the user data will be reflected to the database .
The project also make a good security system to autheticate a perticular user by his/her credentials .
All over this project gives a user friendly solution to make easy signup for the users .

