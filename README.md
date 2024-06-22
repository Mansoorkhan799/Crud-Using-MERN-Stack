# Crud-Using-MERN-Stack
Performing CRUD operation using MERN Stack
Vite: Vite is a build tool that aims to provide a faster and leaner development experience for modern web projects. It is particularly well-suited for projects using frameworks like React
Download and extract the zip folder and open it in VS Code.
Run the following commands in the Backend Directory Terminal:
npm init
npm i express(for backend)
npm i mongoose(for database connection)
npm i cors(connect front end with backend)
npm i dotenv (For file reading)

Run:
npm run dev

Now you can open Postman and log in.
First, create a blank collection and click on get request.
Then Select POST, and write HTTP://localhost:8000/api/create 
Enter the details in the body and press send request.
Now follow the same process for GET, and write HTTP://localhost:8000/api/get
Now follow the same process for UPDATE, and write HTTP://localhost:8000/api/update/apikey*
Now follow the same process to DELETE, and write HTTP://localhost:8000/api/delete/apikey*

The provided information will be directly POST, GET, UPDATE, and DELETE on your MongoDB.



Now for Frontend

npm create vite@latest
Frontend-with-reactjs (Project name)
->react
->JavaScript
cd Frontend-with-reactjs
npm install
npm i axios
npm i bootstrap
npm i react-hot-toast
finally, type npm run dev

