📱 CodeAlpha Social Media Platform

A full-stack Social Media Platform built using Node.js, Express.js, MongoDB, HTML, CSS, and JavaScript.
The platform enables users to create accounts, share posts, interact through likes/comments, and follow other users.

This project demonstrates a modern backend architecture with secure authentication, REST APIs, and scalable database integration.

🚀 Features
🔐 Authentication System
User Registration
User Login
Password Hashing with bcryptjs
Secure Authentication using JWT (JSON Web Tokens)

📝 Post Management
Create New Posts
View All Posts
Like Posts
Comment on Posts

👥 Social Features
Follow / Unfollow Users
User Profiles
Followers & Following System
🌐 REST API Architecture
RESTful API Design
Modular Route Structure
Middleware-based Authentication
Scalable Backend Architecture

🛠️ Tech Stack
Frontend
HTML5
CSS3
JavaScript
Backend
Node.js
Express.js
Database
MongoDB Atlas
Mongoose
Authentication & Security
JWT (JSON Web Tokens)
bcryptjs
Tools & Deployment
Postman
Git & GitHub

📂 Project Structure
CodeAlpha-Social-Media-Platform/
│
├── backend/
│   ├── models/
│   │   ├── User.js
│   │   └── Post.js
│   │
│   ├── routes/
│   │   ├── userRoutes.js
│   │   └── postRoutes.js
│   │
│   ├── middleware/
│   │   └── authMiddleware.js
│   │
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── profile.html
│   ├── style.css
│   └── script.js
│
└── README.md

📸 Application Workflow
1️⃣ User Registration

Users create an account securely.

2️⃣ User Login

Authentication handled using JWT.

3️⃣ Create Posts

Authenticated users can publish posts.

4️⃣ Interactions

Users can:

Like posts
Comment on posts
5️⃣ Social Connections

Users can:

Follow other users
View profiles
Track followers/following
