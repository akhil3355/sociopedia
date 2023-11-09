# <font color="#00FFFF">Sociopedia</font>

Sociopedia is a social media application developed using the MERN stack (MongoDB, Express.js, React, Node.js). It provides users with a platform to connect, share, and engage with each other through posts and comments.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Client-Side Features](#client-side-features)
- [Server-Side Features](#server-side-features)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User Authentication**: Secure user accounts with authentication.
- **Create and Edit Posts**: Share your thoughts and updates with the community.
- **Like and Comment**: Engage with others through likes and comments on posts.
- **User Profiles**: Customize your profile with a profile picture and bio.
- **Responsive Design**: Enjoy a seamless experience across devices.
- **Registration Page**: Seamless user registration with Formik and Yup form validation.
  - **Formik Integration**: Simplified form management for a smoother user experience.
  - **Yup Validation**: Robust form validation ensuring data integrity.
- **Dark Mode and Light Mode**: Toggle between dark and light modes for a personalized user experience.
- **Create Post**: Share your moments by creating posts for the community to see.
- **Like Post**: Show appreciation for posts by liking them.
- **Add/Remove Friend**: Connect with others by adding or removing them as friends.
- **Backend API Integration**: Fetches data from backend APIs for dynamic and real-time content.
- **Reusable Widgets**: Utilizes reusable widgets for a modular and maintainable codebase.
- **Redux Persist**: Implements Redux Persist to store data in local storage, providing a persistent user experience.
- **Password Encryption**: Utilizes bcrypt for secure password hashing and encryption.
- **Material-UI (MUI)**: React component library for building responsive and customizable UIs.

## Technologies Used

- **MongoDB**: NoSQL database for storing user data and posts.
- **Express.js**: Web application framework for Node.js.
- **React**: JavaScript library for building user interfaces.
- **Node.js**: JavaScript runtime for server-side development.
- **Redux Toolkit**: Efficient state management for a scalable and maintainable codebase.
- **bcrypt**: Library for password hashing and encryption.
- **Material-UI (MUI)**: React component library for building responsive and customizable UIs.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed.
- [MongoDB](https://www.mongodb.com/) installed.

### Installation

1. Clone the repository:

   ```bash
   git clone [repository link]
   ```

2. Navigate to the server directory:

   ```bash
   cd server
   ```

3. Install server dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the server directory with the following content:

   ```env
   # MongoDB URL
   MONGO_URL=mongodb://your-mongo-url

   # JWT Secret Key
   JWT_SECRET=your-secret-key

   # Server Port
   PORT=5000
   ```

   Replace `your-mongo-url` with your MongoDB connection string, `your-secret-key` with a secure secret key for JWT, and `5000` with your desired server port number.

5. Navigate to the client directory:

   ```bash
   cd ../client
   ```

6. Install client dependencies:

   ```bash
   npm install
   ```

### Running the Project

1. Start the server:

   ```bash
   cd server
   npm start
   ```

2. Start the client:

   ```bash
   cd client
   npm start
   ```

## Client-Side Features

- **React Router**: Utilizes React Router for seamless navigation and a smooth user experience.
- **Redux Toolkit**: Implements Redux Toolkit for efficient state management, ensuring a scalable and maintainable codebase.
- **React Dropzone**: Integrates React Dropzone for easy and intuitive file uploads within the application.
- **Dark Mode and Light Mode**: Toggle between dark and light modes for a personalized user experience.
- **Create Post**: Share your moments by creating posts for the community to see.
- **Like Post**: Show appreciation for posts by liking them.
- **Add/Remove Friend**: Connect with others by adding or removing them as friends.

## Server-Side Features

- **Mongoose**: Uses Mongoose for MongoDB database operations, providing a straightforward and schema-based solution.
- **JWT Authentication**: Implements JWT for secure user authentication, ensuring a reliable and token-based login system.
- **Node.js with Multer**: Utilizes Node.js with Multer for efficient file uploads within the server.

## Usage

1. Create an account or log in if you already have one.
2. Explore posts on the main feed.
3. Create your own posts and engage with others through likes and comments.
4. Toggle between dark and light modes for a personalized experience.
5. Connect with others by adding or removing them as friends.

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Follow the [contributing guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or support, contact us at [akhilthiruthiyottil@gmail.com].

---
