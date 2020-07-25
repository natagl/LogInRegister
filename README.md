# LogInRegister

### Client Side Setup:
**Step 1.** Enter the cloned repo:<br>
cd Login-Register-Page-Boilerplate<br>
**Step 2.** install npm packages from the root of repo :<br>
npm install <br>
**Step 3.** Enter client folder:<br>
cd client <br>
**Step 4.** Again install some client specific dependencies: <br>
npm install<br>
**Step 5.** Start the client: <br> 
npm start <br>
You should see a server open at  <br>
Local:   http://localhost:3000 <br>
On Your Network:  http://10.0.0.51:3000<br>
Please note, at this point the Application will not work because the server has not been set up yet.<br>

### Server side Set up<br>
**Step 1.** Install nodemon if it does not exist:<br>
npm install -g nodemon<br>
**Step 2.** Go inside LogInRegister-server folder:<br>
 cd LogInRegister-server  <br>
**Step 3.** Again install some serverspecific dependencies: <br>
npm install  <br>
**Step 4.** If you don't have Mongo DB account ,you can create Mongo DB Atlas account:<br>
(https://docs.atlas.mongodb.com/tutorial/create-atlas-account/)<br>
**Step 5.** And then to connect your database with this application, You have to create config.js file in root folder of cloned repo,

```
example:
module.exports = { MONGODB:or'mongodb+srv://<USER_NAME>:<PASSWORD>@cluster0-vtqvq.mongodb.net/<DATABASE_NAME>?retryWrites=true',SECRET_KEY: "your own secret key value"};
```  

**Step 4.**  Run the server:<br>
npx nodemon or justnodemon<br>
  
### Technologies Used:<br>
-> ReactJs, GraphQL, NodeJs, MongoBD, Mongoose, Apollo Server, Semantic UI, PostMan(for testing Heroky backend deployment)<br>
For deployment:<br>
-> Fontend: Netlify(https://nataliialoginregister.netlify.app/)<br>
-> Backend: Heroku(https://tranquil-wildwood-09091.herokuapp.com/) <br>

#### Contact<br>

Nataliia Glinska - glinska.nataliia21@gmail.com📩<br>
Project Link : https://nataliialoginregister.netlify.app/<br>
