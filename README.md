# Journal - A social media app 


A social media application built using the MERN stack, where users can share their experiences, follow each other, comment on posts, and filter content based on names and tags.


## Features ✨

- User registration and authentication
- Follow/unfollow functionality
- Commenting on posts
- Content filtering by names and tags
- Pagination for better user experience
- Hash encryption of passwords
- Access management with JWT tokens




## Technology Stack 🛠️

### Backend

- Node.js: A JavaScript runtime environment for server-side development.
- Express.js: A web application framework for Node.js used for building APIs and handling HTTP requests.
- MongoDB: A NoSQL database for storing application data.
- JWT (JSON Web Tokens): A mechanism for authenticating and securely transmitting information between parties.

### Frontend

- React.js: A JavaScript library for building user interfaces.
- Redux: A predictable state container for managing application state.
- React Router: A routing library for navigation in a React application.
- Axios: A library for making HTTP requests from the browser.

## Prerequisites 📦

- Node.js and npm (Node Package Manager) should be installed.
- MongoDB should be installed and running.

## Installation ⚙️

1. Clone the repository:

   ```bash
  
   cd social-media-web-app
   ```
2. Install the dependencies for both backend and frontend:
   ```bash
    cd server
    npm install
    ```
   ```bash
    cd ../client
    npm install
   ```
3. Configuration: Rename the .env.example file in the backend directory to .env and update the configuration values such as MongoDB connection URL, JWT secret, etc.
4. Start the application:
   ```bash
    cd server
    npm start
   ```
   ```bash
    cd ../client
    npm start
   ```
The application should now be running at http://localhost:3000. ▶️
