## Cookie-Session

22664681 - Nguyễn Vũ Thị Quế Trân

npm install
npm init -y
npm install express
npm install cookie-parser
npm install express-session
npm install mongoose

2. cookie_session_auth source code
a. cookie_session_auth
node app.js

b. register
Method: POST
URL: http://localhost:3000/auth/register
![alt text](public/results/register.png)

## Check in database
![alt text](public/results/mongoDBregister.png)

c.login
Method: POST
URL: http://localhost:3000/auth/login
![alt text](public/results/login.png)

## Check in database
![alt text](public/results/mongoDBlogin.png)

d. go to profile
Method: GET
URL: http://localhost:3000/auth/profile
![alt text](public/results/profile.png)

e. Logout
Method: GET
URL: http://localhost:3000/auth/logout
![alt text](public/results/logout.png)

## Check in database
![alt text](public/results/mongoDBlogout.png)