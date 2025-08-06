🚀 MongoDB Chat App
==========================

MongoDB Chat App is a real-time messaging application built using Node.js, Express.js, and MongoDB. It enables users to send and receive messages instantly, manage their accounts, and perform full CRUD (Create, Read, Update, Delete) operations on messages.

This project is designed to be scalable, secure, and flexible, making it a strong foundation for building chat systems or expanding into feature-rich communication platforms.

✨ Features
==========

1. **Real-Time Messaging** – Send and receive messages instantly using WebSockets.
2. **CRUD Operations on Messages** –
     **Create**: Add new messages.
     **Read**: Fetch messages from MongoDB in real-time.
     **Update**: Edit previously sent messages.
     **Delete**: Remove messages from the chat.
3. **User Authentication & Authorization** – Secure login and registration.
4. **Message Storage** – Persistent data storage using MongoDB.
5. **User Management** – Manage profiles and track active users.
6. **Error Handling & Logging** – Structured error responses and logging for debugging.
7. **Scalability & Flexibility** – Easily extendable for new features like group chats.
8. **Security** – Encrypted passwords and secure authentication mechanisms.
9. **Instant Updates** – Automatic message synchronization across connected clients.

🧰 Tech Stack
=============

| HTML | Node.js | Express.js | Mongoose | MongoDB |
| JavaScript | CSS3 |

📁 Project Structure
=====================

```
mongo-chat-app/
│── app/
│   ├── controllers/     # CRUD logic for users and messages
│   ├── models/          # Mongoose schemas
│   ├── routes/          # API and chat routes
│   └── views/           # Frontend templates
│── public/              # Static assets (CSS, JS)
│── index.js             # Entry point
│── init.js              # Initialization config
│── package.json         # Dependencies
│── style.css            # Global styling

```

⚙️ How to Run
=============

1.**Clone the repository**
```
git clone https://github.com/your-username/mongo-chat-app.git
cd mongo-chat-app
```

2.**Install dependencies**
```
npm install
```
3.**Configure environment variables (create .env file)**
```
MONGO_URI=your-mongodb-connection
PORT=5000
JWT_SECRET=your-secret-key
```

4.**Start the app**
```
npm start
```

5.**Open in browser**
```
http://localhost:5000
```
📸 Screenshots
=============
<img width="939" height="456" alt="Screenshot 2024-12-20 154608" src="https://github.com/user-attachments/assets/83ec69a1-5458-4371-af27-3e37c3bd283b" />
<img width="719" height="1017" alt="Screenshot 2024-12-20 154133" src="https://github.com/user-attachments/assets/92042917-a7fe-45d0-b22b-e48e17a05d46" />
<img width="643" height="1020" alt="Screenshot 2024-12-20 181005" src="https://github.com/user-attachments/assets/274cc301-91a1-42f6-b6b1-9e91b61eb2fa" />
<img width="634" height="437" alt="Screenshot 2024-12-20 181119" src="https://github.com/user-attachments/assets/a8db9a07-3fac-4512-824b-5bba755ad770" />



👤 **Author**

* **Name**: [Hrusikesh Sahu]
* **Email**: [hs2068672@gmail.com]
* **Linkedin**: [https://www.linkedin.com/in/hrusikesh-sahu-895420300/]

