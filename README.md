# Online Matrimonial System

## Project Overview

The **Online Matrimonial System** is a matchmaking platform that facilitates users in finding their ideal marriage partner by filtering based on customizable criteria. Users can register, manage their profiles, and search for compatible matches. The application is built with a focus on providing a seamless and secure user experience.

---

## Table of Contents
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Screenshots](#screenshots)
7. [Future Enhancements](#future-enhancements)
8. [Acknowledgments](#acknowledgments)

---

## Features

The system provides the following features:

- **User Registration and Login:** Users can register with personal details and access the system securely.
- **Profile Management:** Users can view, update, or delete their profiles.
- **Search Partner:** Allows users to search for partners based on criteria such as age, religion, and location.
- **Request Partner:** Users can send friend requests to potential matches.
- **Chat with Partner (Future Feature):** A proposed feature to enable chatting between matched users.

---

## Technologies Used

### Languages and Frameworks
- **Frontend:** HTML, CSS, JavaScript, Bootstrap, React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB for data storage and retrieval

### Tools
- **Code Editor:** Visual Studio Code
- **Platform:** Local development server

---

## Project Structure

```plaintext
Online Matrimonial System
├── src/
│   ├── components/         # React components
│   ├── routes/             # Backend routes for APIs
│   ├── models/             # Database schemas
│   ├── controllers/        # Function logic for API routes
│   └── views/              # Frontend views
├── public/
│   └── assets/             # Static assets like images and stylesheets
├── server.js               # Main server file
└── package.json            # Project dependencies
```

---

## Installation

To set up the project on your local machine:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/online-matrimonial-system.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd online-matrimonial-system
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Set up MongoDB:**
   - Install and configure MongoDB on your machine.
   - Add your MongoDB connection string to an environment file.

5. **Run the application:**
    ```bash
    npm start
    ```

---

## Usage

### User Registration
- Users need to sign up by providing essential information like name, age, email, etc.
- Upon successful registration, users are redirected to the login page.

### Search for Partner
- Guests and registered users can search for partners based on their selected criteria (age, religion, gender).
- Registered users have additional access to sending requests to matches.

### Profile Management
- Users can view and update their profiles or delete them if no longer required.

### Partner Module
- Registered users can send friend requests to matched profiles.
- The future goal is to implement a chat feature for enhanced communication between users.

---

## Screenshots

### Home Page
![Home Page](screenshots/1.JPG)

### User Registration
![User Registration](screenshots/2.JPG)

### Search Feature
![Search Feature](screenshots/search_feature_mm.png)

### View Profile
![View Profile](screenshots/view_profile_mm.png)

---

## Future Enhancements

- **Chat Feature:** Implement real-time chat functionality.
- **Friend Request Feature:** Allow users to manage requests effectively.
- **User Validation:** Implement an admin system for verifying user details and enhancing platform safety.

---

## Acknowledgments

We referred to various resources to build this project, including:

- [React](https://reactjs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [StackOverflow](https://stackoverflow.com/)

---

Feel free to contribute, open issues, and submit pull requests to make the project better.
