# Social-media-site
This is the code for a  social media site called codeial, an acronym for code+social.
With codeial a user can Sign In/Up with his username as well as Google-oath2 strategy,
a user can add friends, can create posts and can add likes and comments on other user's posts
, forgot password feature is also added. A user can also chat with other users, which are on his friend's lists.
A Chatting engine is made with socket.io. All records of a user, user id, posts, comments are being recorded in a Database.
MongoDB is used as Database.

Screenshots:
![image](https://user-images.githubusercontent.com/87467419/135202599-39e21fa8-c651-4b1b-bbc6-b24e92fd7bb7.png)
![image](https://user-images.githubusercontent.com/87467419/135202620-db66679b-9dc3-4c19-8216-0fd7d7cb3def.png)


Technology stack : 
* HTML,CSS,Javascript,jQuery,Ajax,Sass
* Node.js,MongoDB,Express.js

Insights :
* passport-jwt strategy for authentication and authorization.
* passport-google-oauth2 strategy for social authentication through  google.
* used Nodemailer to send out emails.
* used socket.io for implementing chat engine.

How to Install :
* Clone the project onto your local machine.
* Then cd codeial
* npm install
* npm start
* Visit your app at http://localhost:8000.

