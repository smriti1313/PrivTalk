# **PrivTalk: Secure Real-Time Messaging App**

**PrivTalk** is a modern web-based chat application designed to offer end-to-end encrypted communication in real-time. Built using the **MERN stack**, this app allows users to engage in private and secure conversations.

## 🛠️ **Technologies Used:**
- **Frontend**: React.js, Chakra UI, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Real-time Communication**: Socket.io
- **Database**: MongoDB
- **Encryption**: Crypto.js, JWT Authentication, BcryptJS for password hashing

[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-000000?style=for-the-badge&logo=javascript&logoColor=yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)](https://socket.io/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

---

## 🚀 **Features**

- **User Authentication**: Secure login/signup with JWT and encrypted password storage using BcryptJS.
- **Profile Customization**: Update your profile picture and username.
- **Real-Time Communication**: Instant messaging with one-to-one and group chat functionality.
- **Group Management**: Create and manage groups, with admin permissions to add/remove users.
- **Encrypted Conversations**: All chats are end-to-end encrypted for enhanced privacy.
- **Search**: Real-time user search.
- **Notifications**: Receive real-time group notifications and track unseen messages.

## 💻 **Demo**

Watch the project in action!  
[Click here to view the demo](https://www.linkedin.com/feed/update/urn:li:activity:7033886022119632896/)

---

## 📝 **Getting Started**

To run PrivTalk locally on your machine, follow the steps below:

### Prerequisites
Ensure you have the following installed:
- **Node.js** (with npm)
- **MongoDB** (for database)

### Setup

Clone the repository:
   
git clone https://github.com/Deepeshgodhwani/PrivTalk.git
   cd PrivTalk


Install Dependencies:

> For frontend (client-side):

    
cd client
    npm install

   
> For backend (server-side):
cd ../server
npm install


Run the app:

> Start the client:
cd client
npm start

> Start the server:
cd server
npm start


### Environment Variables
You need to set up the following environment variables in the .env file inside the server directory:

> JWT_ACCESS_KEY

> MONGO_PATH