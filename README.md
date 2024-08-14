# Chat Application

## Project Description

The **Chat Application** is a full-stack real-time messaging platform that allows users to engage in private and group conversations, send multimedia content, and receive instant notifications. This application is designed with a focus on user experience, security, and performance.

---

## Table of Contents

- [Design Phase](#design-phase)
- [Development Phase](#development-phase)
  - [Frontend Development](#frontend-development)
  - [Backend Development](#backend-development)
- [Functionality](#functionality)
- [Tech Stack](#tech-stack)
- [Deployment](#deployment)

---

## Design Phase

1. **User Interface Design**: 
   - Sketched layouts of the application's interface focused on usability and user experience.
   - Used **Bootstrap** for creating a responsive design that adapts to different screen sizes.

2. **Wireframes**:
   - Created wireframes for the login, registration, chat, and profile management screens.

---

## Development Phase

### Frontend Development

1. **React**:
   - Used **React** for building a dynamic and interactive user interface.
   - Created separate components for login, registration, chat rooms, group chat, and user management.
  
2. **State Management**:
   - Utilized **React state** and **Formik** for managing form inputs and validation messages.
   - Used **Redux** or **Context API** for handling global state across the application.

3. **Routing**:
   - Implemented client-side routing using **React Router** for navigating between different pages (Login, Registration, Chat, Profile, etc.).

4. **Responsive Design**:
   - Used **CSS frameworks** like Bootstrap to ensure the application is responsive on all devices, from mobile phones to desktops.

### Backend Development

1. **Node.js & Express.js**:
   - Set up **Node.js** and **Express.js** for creating RESTful APIs that handle requests and responses from the client side.
   - Used **JWT** and **Bcrypt** to handle secure user authentication and authorization.

2. **MongoDB**:
   - Configured **MongoDB** as the database for storing user data, chat history, authentication tokens, and multimedia content.
   - Designed schema models for users, messages, and groups.

3. **Role-based Access Control (RBAC)**:
   - Integrated middleware to control user permissions and role-based access control, ensuring only authorized users can perform certain actions.

4. **Security**:
   - Implemented **JSON Web Tokens (JWT)** for stateless authentication.
   - Used **Bcrypt** to hash passwords for secure user authentication.

---

## Functionality

The following key functionalities have been implemented:

1. **Real-time Messaging**:
   - Users can send and receive messages in real-time, enabling instant communication.

2. **Private Messaging**:
   - Users can engage in one-on-one private conversations, ensuring secure and personal communication.

3. **Empty Message Alerts**:
   - Alerts are displayed when users attempt to send empty messages.

4. **Group Chats**:
   - Users can create or join group chats, allowing multiple participants to collaborate and communicate in the same conversation.

5. **Multimedia Sharing**:
   - Users can share images, videos, and documents in chat conversations, enhancing the communication experience.

6. **Notifications**:
   - Users receive notification alerts for new messages, mentions, and other relevant activities, keeping them informed and engaged.

---

## Tech Stack

- **Frontend**: React.js, Redux / Context API, Formik, React Router, Bootstrap, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: JWT, Bcrypt
- **Real-time Messaging**: WebSockets (or any real-time library like Socket.io)
- **Deployment**: Netlify (Frontend), Render (Backend)

---

## Deployment

1. **Frontend**: 
   - Deployed on **Netlify**. Visit the [live demo](https://dheechat.netlify.app/) to interact with the application.

2. **Backend**:
   - Deployed on **Render**. The RESTful API can be accessed at [Render](https://chatapplication-be.onrender.com/).

### Repositories

- Frontend: [Chat Application Frontend](https://github.com/Yukechan2002/ChatApplication-FE)
- Backend: [Chat Application Backend](https://github.com/Yukechan2002/ChatApplication-BE)

---