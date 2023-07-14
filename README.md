# **ImageVault**

ImageVault is a full-stack MERN (MongoDB, Express, React, Node) social media application called "ImageVault" that allows users to post images, like and comment on posts, and connect with others. This readme overviews the project and explains the different components involved in building the application.

## **Overview**

ImageVault is a social media platform designed to share images and connect with other users. It provides a user-friendly interface that allows users to register, log in, and customize their profiles. Users can upload images, view posts from other users, like and comment on posts, and follow others to stay updated with their activity. The application offers a responsive design to ensure optimal user experience across various devices and screen sizes.

The front end of ImageVault is built using React, a popular JavaScript library for building user interfaces. It leverages technologies like Redux for state management, React Router for navigation, and Material UI for creating visually appealing UI components. React Redux manages the application's state, ensuring efficient data flow and providing a centralized data store. The front end also utilizes Formik and Yup libraries for building and validating forms, respectively, enabling smooth user interactions. Additionally, React Dropzone is incorporated to allow users to upload images easily. Combining these tools and libraries enhances the development experience and creates a seamless user interface.

The backend of ImageVault is developed using Node.js and Express, providing a robust server-side infrastructure. MongoDB is the database, and Mongoose, an Object-Document Mapping (ODM) library, simplifies data modelling and interaction with the database. Multer, a middleware, handles file uploads, while GridFS-Storage manages the storage of large files in MongoDB GridFS. The backend includes authentication and authorization functionalities using JSON Web Tokens (JWT), ensuring secure access to the application's features and protecting user data.

The ImageVault project follows a modular and organized code structure, making it scalable and maintainable. It incorporates industry-standard practices and leverages various tools and libraries to provide a comprehensive social media application experience.

## **Features**

ImageVault offers the following features to its users:

- **User Registration and Authentication**: Users can register an account with a unique username and password. Authentication is implemented using JSON Web Tokens (JWT) to ensure secure access to the application.
- **User Profiles**: Each user has a profile page where they can customize their profile picture, bio, and other details. Users can also view and edit their profiles.
- **Post Creation and Interaction**: Users can upload images and create posts. They can also view posts from other users and interact with them by liking and commenting.
- **Social Interaction**: ImageVault facilitates social interaction by allowing users to follow other users. Users can view a feed of posts from their followers to stay updated with their activity.
- **Likes and Comments**: Users can express their appreciation for posts by liking them. They can also leave comments on posts to converse with other users.
- **Search and Discover**: ImageVault provides search functionality for users to find specific posts or users. Users can explore and discover new content and profiles based on their interests.
- **Notifications**: The application notifies users about new likes, comments, and followers to keep them informed and engaged with their social network.
- **Dark Mode**: ImageVault offers a dark mode option, enhancing the user experience and allowing users to customize the application's appearance.
- **Responsive Design**: The application is designed to be responsive, ensuring optimal user experience on different devices and screen sizes.

## **Dependencies and Tools**

The following dependencies and tools are used in the ImageVault project:

- Material UI: A popular React UI framework for creating responsive and visually appealing components.
- Redux Toolkit: A library for efficient Redux state management in React applications.
- React Router: A library for handling navigation and routing in React applications.
- Redux Persist: A library for persisting Redux state in the browser's local storage.
- React Dropzone: A library for drag-and-drop file uploads in React applications.
- Node.js: A JavaScript runtime used for building the backend server.
- Nodemon: A tool that automatically restarts the server on file changes during development.
- VS Code: A source code editor for efficient coding and development.
- Dotenv: A module that loads environment variables from a .env file.
- MongoDB: A NoSQL database used for storing application data.
- Mongoose: An Object-Document Mapping (ODM) library for MongoDB and Node.js.
- JsonWebToken: A library for implementing JSON Web Tokens for user authentication.
- Multer: A middleware for handling file uploads in Node.js.
- GridFS-Storage: A library for storing large files in MongoDB GridFS.
- Google Fonts: A collection of freely available fonts for web applications.
- Formik: A library for building forms in React.
- Yup: A library for form validation in React applications.

## **Installation**

To run the ImageVault application locally, follow these steps:

1. Install Node.js: Visit the **[Node.js website](https://nodejs.org/en/download/)** and download the appropriate version for your operating system.
2. Install Visual Studio Code: Download and install **[VS Code](https://code.visualstudio.com/download)** to set up your development environment.
3. Clone the repository: Clone the ImageVault repository to your local machine.
4. Install dependencies: Navigate to the project directory and run the following command to install the required dependencies:
    
    ```
    npm install
    ```
    
5. Configure environment variables: Create a **`.env`** file in the root directory and set the required environment variables based on the provided examples or specific instructions.
6. Start the backend server: Run the following command to start the Node.js backend server:
    
    ```
    npm start
    ```
    
7. Start the frontend application: Open a new terminal window, navigate to the project directory, and run the following command to start the React frontend:
    
    ```
    npm start
    ```
    
8. Access the application: Open your web browser and visit **`http://localhost:3000`** to access the ImageVault application.
