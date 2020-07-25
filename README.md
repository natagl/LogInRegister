# LogInRegister

Client Side Setup:
Step 1. Enter the cloned repo:
cd Login-Register-Page-Boilerplate
Step 2. install npm packages from the root of repo 
npm install 
Step 3. Enter client folder 
cd client
Step 4. Again install some client specific dependencies: 
npm install
Step 5. Start the client : 
npm start
You should see a server open at  
Local:                     http://localhost:3000
On Your Network:  http://10.0.0.51:3000
Please note, at this point the Application will not work because the server has not been set up yet.

Server side Set up
Step 1. Install nodemon if it does not exist:
npm install -g nodemon
Step 2. Go inside LogInRegister-server folder
 cd LogInRegister-server  Step 3. Again install some serverspecific dependencies: 
npm install  
Step 4. If you don't have Mongo DB account ,you can create Mongo DB Atlas account :
(https://docs.atlas.mongodb.com/tutorial/create-atlas-account/)
Step 5. And then to connect your database with this application, You have to create config.js file in root folder of cloned repo,
example:module.exports = {    MONGODB:or        'mongodb+srv://<USER_NAME>:<PASSWORD>@cluster0-vtqvq.mongodb.net/<DATABASE_NAME>?retryWrites=true',    SECRET_KEY: "your own secret key value"};Step 4. Run the server:npx nodemon or justnodemon
