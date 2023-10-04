# FriendZone - Social App

FriendZone is a MERN (MongoDB, Express.js, React.js, Node.js) application that allows users to connect with friends, create posts, upload photos, and view profile pages.

**Live App:** [FriendZone on Vercel](https://mern-friendzone.vercel.app/)


![FriendZone Screenshot](./server/public/assets/homepage.png)


## Getting Started

To get started with FriendZone, follow the instructions below:

### Prerequisites

Make sure you have the following software installed on your machine:

- Node.js
- MongoDB

## Features
FriendZone offers the following features:

- User authentication (login and registration)

- Adding friends

- Creating and editing posts

- Like posts

- Uploading photos

- Profile page with user information

## Technologies and Libraries Used
FriendZone is built using the following technologies:


- [Material UI](https://mui.com/material-ui/getting-started/): Developed the user interface of the application using Material-UI components and styles, following the Material Design guidelines.

- [Redux Toolkit](https://redux-toolkit.js.org/introduction/getting-started): Implemented state management using Redux Toolkit, providing centralized and predictable state management for the application.

- [React Router](https://reactrouter.com/en/v6.3.0/getting-started): Utilized React Router for handling client-side routing and navigation within the application.

- [Redux Persist](https://github.com/rt2zz/redux-persist): Integrated Redux Persist to persist and rehydrate the Redux store, ensuring data persistence across page reloads.

- [React Dropzone](https://react-dropzone.js.org/): Utilized React Dropzone for handling file uploads and providing an intuitive user interface for attaching photos to posts.

- [Node.js](https://nodejs.org/en/download/): Built the server-side of the application using Node.js, providing a JavaScript runtime environment for server-side code.

- [Nodemon](https://github.com/remy/nodemon): Leveraged Nodemon during development for automatic server restarts on file changes, improving the development workflow.

- [MongoDB](https://www.mongodb.com/): Utilized MongoDB as the database for storing user profiles, posts, and other relevant data.

- [Mongoose](https://github.com/Automattic/mongoose): Used Mongoose, an Object Data Modeling (ODM) library for MongoDB, to simplify database interactions and perform CRUD operations.

- [JsonWebToken](https://github.com/auth0/node-jsonwebtoken): Implemented user authentication and authorization using JsonWebToken for secure communication between the client and server.

- [Multer](https://github.com/expressjs/multer) and [GridFS-Storage](https://github.com/devconcept/multer-gridfs-storage): Used Multer along with GridFS-Storage for handling file uploads and storing large files such as user profile pictures and post images.

Other libraries and technologies used in the FriendZone app include Dotenv for environment variable management, Google Fonts for typography customization, Formik for form handling and validation, and Yup for schema-based form validation.

## Installation and Setup

1. Clone the repository.
2. Install dependencies using `npm install` or `yarn install`.
3. Set up environment variables using a `.env` file.
4. Start the server using `npm start` or `yarn start`.
5. Start the client development server using `npm run client` or `yarn run client`.
6. Access the application in your browser at `http://localhost:3000`.

## Project Structure

The project structure follows a standard MERN application layout, with the client-side code residing in the `client` directory and the server-side code in the `server` directory. 


![FriendZone Screenshot](./server/public/assets/profilepage.png)


