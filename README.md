# react-node-file-upload-project
This is a simple React node mongodb project. It includes the user Registration and Login and file upload using Multer. The Logged in user can upload a file and with a unique code  and can also download and delete the file according to his need. 

Procedure to setup, run Backend (Node.js, Express, MongoDB) API Service & Frontend (React) UI Project:

Backend Service/API
Start backend(API) Service first (backend-service)

(1) Open terminal and navigate to Project folder i.e. backend-service. (2) For first time run "npm install" on your terminal (3) Wait for all dependency to be installed (4) Enter "npm start" on your terminal to run the service (5) This backend service will run on http://localhost:5000/

Here are the API end-points created: (1) / GET / -- Get Api root (This will serve Api root with EJS page) (2) /GET /countries -- Get list of countries needs for country list to be used in UI Project (3) /POST /signup -- Sign Up or Register new user (4) /POST /login -- Login with username & password How much completed? (a) All API needed for the UI requirement is completed. (b) Database will create automatically. Just you need to Provide the user credentials for MongoDB (c) Overall 100% is completed.
