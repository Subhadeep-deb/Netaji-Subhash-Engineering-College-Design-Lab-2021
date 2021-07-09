</h1>

What is this for?
This is a Simple User Registration & Login systems app done with Node.js Framework using MongoDB(Atlas) as the data store, Express as the routing system, Body-parser as the parser for webpage, Express-session used  to track the user's session and of course Mongoose to make interacting with Mongo from Node easy.



Running the tests

•Registration Form :-

The Registration page bsically allows the users to register their account by the perticular fields such as Email, Username, Password.

In registration page there will also an option of login , for those users who already have been regiterd .

•Login Form :-
 
If the user has been registered on the app, can login by passing the credentials. The system will check whether the creadential entered by them is already stored in the database or not .  

•User's Profile:
After the user logged in, a simple profile with the user's username and password <br>displayed with a session Logout button.

•Password Reset:

If the user forget his/her password, can reset by entering the registered Email id <br>and reset the password.That perticular user password updation will be effected in database .

DataBase:
Here we use **[MongoDB Atlas(Cloud)](https://www.mongodb.com/cloud/atlas)** as the database. Here we have two collection created, named as:
- users.
- sessions.

A Collection(**Users**) is populated with the user's credentials.

<img src="" height="300" width="720";"><br><br>

A Collection(**session**) is created which stores the users Logged session.
<br>
<br>
<br>

## Prerequisites
Tools that we need to run this app:

- ***[Node.js](https://nodejs.org/en/)***
- ***[Node Package Manager](https://www.npmjs.com/get-npm)***
- ***[MongoDB (Atlas)](https://www.mongodb.com/cloud/atlas)***

Installing
```
npm install
```
Connection to DataBase Access
At line 11 on ```./server.js``` change ***```<DB_USERNAME>```*** with your DataBase UserName & ***```<DB_PASSWORD>```*** with your DataBase Password.

To Run the App
```
node server.js
```

The server will start Running on
+ http://localhost:3002/
