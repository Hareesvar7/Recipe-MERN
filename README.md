# Recipe Book Application - MERN Stack

Live Site URL : [Recipe Book](https://flavor-verse.netlify.app/)

This project is a full-stack web application built using React for the frontend and Express.js with MongoDB for the backend. The frontend uses various packages such as Formik, Yup, FontAwesome, and React-Axios to create a sign-up page with form validation and file upload, a home page with a search bar to fetch data from Spoonacular API, and a profile page that displays user details and saved recipes.

The backend uses packages such as bcrypt, body-parser, cors, helmet, jsonwebtoken, mongoose, and multer to handle user authentication, password encryption, and database operations. It checks whether the user exists before storing the user's information in the database and uses JSON web tokens for secure communication between the client and server.

The Redux store is used to store the user's details, saved recipes, and the authentication token. The state is also persisted using Redux persist to ensure that the user's details are saved even after refreshing the page.

The application also has a recipe detail page that displays information such as cooking time, instructions, summary, and ingredients for each recipe. Users can save recipes to their profile, and the application provides a way to search for recipes based on keywords.

To use the application, users must first sign up with their name, email, password, and profile picture. Once signed in, they can search for recipes, save their favorite recipes, and view their saved recipes on their profile page. The application also provides a logout button to ensure the user's privacy and security.

 
## Installation

To run this project, you'll need to have Node.js and MongoDB installed on your system. You can download Node.js from the official website: https://nodejs.org/, and install MongoDB by following the instructions provided here: https://docs.mongodb.com/manual/installation/.

To install the project dependencies, follow these steps:

Clone the repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/your-name/your-project-name.git
Navigate to the project directory:

bash
Copy code
```bash
cd your-project
```
Install the frontend dependencies:
```bash
npm install
```
Navigate to the backend directory:

```bash
cd backend
```
Install the backend dependencies:

```bash
npm install
```
Create a .env file in the backend directory, and set the following environment variables:

makefile
```bash
PORT=5000
MONGODB_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
```
Replace <your-mongodb-uri> with the URI of your MongoDB database, and <your-jwt-secret> with a secret key of your choice.

Start the backend server:

```bash
npm start
```
Open a new terminal window, navigate to the project directory, and start the frontend server:

```bash
npm start
```
Open your web browser and navigate to http://localhost:3000 to view the application.

That's it! You should now be able to run the application locally. If you encounter any issues, please refer to the project documentation or create a new issue on the project's GitHub repository.
    
  

## Deployment


Create a GitHub repository for your project.

Push your code to the GitHub repository.

Sign up for a Render account.

Create a new web service on Render, and select "Custom" as the type.

Fill in the required details such as the name of the service, the region, 
the startup command 
```bash
npm start
```

the build command
```bash
npm install
```
Under the Environment section, add the necessary environment variables such as the 
```bash
MongoDB URL
port number
JWT secret
```


