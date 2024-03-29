﻿# SocialWave 🌍

Hello 👋,
SocialWave is a MERN (MongoDB, Express.js, React.js, Node.js) stack social media platform where users can connect, share posts, interact with friends, and more. 

## Features 🌟

- User authentication: Signup, login, and logout functionalities.
- Post creation: Users can create posts.
- Like system: Users can like posts and see comment on them.
- Friend system: Users can add and remove friends.
- Responsive UI: Built using React and Material UI for a smooth user experience across devices.

## Tech Stack 🛠️

- **Frontend**: React.js, Material UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Other Libraries**: nodemon, bcrypt (password hashing), morgan (HTTP request logger), multer (multipart form-data handling), CORS(Cross-origin resource sharing), Helmet - helps secure Express apps by setting HTTP response headers, body-parser etc.

## Setup Instructions  🚀

1. Clone the repository: https://github.com/Nitinpr1/SocialWave.git
2. Navigate to the project directory.
3. Install dependencies for both frontend and backend.
4. Set up environment variables:
   - Create a `.env` file in the `server` directory.
   - Define the following variables in the `.env` file:
     - `MONGODB_URI`: MongoDB connection URI
     - `JWT_SECRET`: Secret key for JWT token generation
5. Start the backend server : nodemon index.js
6. Start the frontend development server: npm run start
7. Open your browser and navigate to `http://localhost:3000` to view the application.

## Usage 😀 

- Sign up for a new account or log in with existing credentials.
- Create posts, like posts, and see comment on them.
- Add or remove friends to interact with them on the platform.

Screenshot:
![screenshot](https://github.com/Nitinpr1/SocialWave/blob/main/client/public/assets/home.png)





