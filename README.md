# Crud-Using-MERN-Stack
# Performing CRUD operation using MERN Stack
Vite: Vite is a build tool that aims to provide a faster and leaner development experience for modern web projects. It is particularly well-suited for projects using frameworks like React
Download and extract the zip folder and open it in VS Code.<br />
Run the following commands in the Backend Directory Terminal:<br />
npm init<br />
npm i express(for backend)<br />
npm i mongoose(for database connection)<br />
npm i cors(connect front end with backend)<br />
npm i dotenv (For file reading)<br />

Run:<br />
npm run dev<br />

Now you can open Postman and log in.<br />
First, create a blank collection and click on get request.<br />
Then Select POST, and write HTTP://localhost:8000/api/create <br />
Enter the details in the body and press send request.<br />
Now follow the same process for GET, and write HTTP://localhost:8000/api/get<br />
Now follow the same process for UPDATE, and write HTTP://localhost:8000/api/update/apikey*<br />
Now follow the same process to DELETE, and write HTTP://localhost:8000/api/delete/apikey*<br />

The provided information will be directly POST, GET, UPDATE, and DELETE on your MongoDB.<br />



Now for Frontend<br />

npm create vite@latest<br />
Frontend-with-reactjs (Project name)<br />
->react<br />
->JavaScript<br />
cd Frontend-with-reactjs<br />
npm install<br />
npm i axios<br />
npm i bootstrap<br />
npm i react-hot-toast<br />
finally, type npm run dev<br />

