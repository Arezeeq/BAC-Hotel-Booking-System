# Hotel-Booking-System
**About Project**

Hotel booking system is a software application that is implemented for the hotels to allow guests making room 
reservation anywhere and anytime worldwide via a website without the hassle of physically meeting with them. 

The objective of this project is to develop system that make it easy for customers to make reservations with 
feature of having their own dashboard of each user and to provide information each of the hotel rooms.

Guides to run applications:

1. Create config folder in backend folder
2. Add Database.js file with below setup:
  
        import {Sequelize} from "sequelize";
        
        const db = new Sequelize('<yourdatabasename>','<yourusername eg:root>','<yourpassword>',{
        host: "localhost",
        dialect: "mysql"
        });
        
        export default db;

3. Create the .env file in the backend folder and add the details as below:

        ACCESS_TOKEN_SECRET = just put whatever your want, make sure to write as long as you can
        REFRESH_TOKEN_SECRET = same here
    
4. Access both folder (backend and frontend) in the difference terminal, and npm init -a, after that npm install.
5. On the frontend terminal, run npm start while on the backend terminal run nodemon.

Project collabrator: Luqman https://github.com/LHZA97

*This is a student project that was created at [BAC education] under a PENJANA KPT-CAP Program.*
