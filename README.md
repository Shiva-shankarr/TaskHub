# TaskHub - Modern Task Management Platform

![TaskHub Banner](client/public/banner.png)

## 🚀 Overview

TaskHub is a powerful, cloud-based task management platform built with the MERN stack (MongoDB, Express.js, React, Node.js). It provides teams with a robust solution for task management, collaboration, and workflow optimization.

## ✨ Key Features

### 👑 Admin Features
- **User Management**
  - Create and manage admin accounts
  - Add/remove team members
  - User account activation/deactivation

- **Task Management**
  - Create and assign tasks
  - Set task priorities (high, medium, normal, low)
  - Manage task statuses (todo, in progress, completed)
  - Create and track subtasks
  - Asset management (image uploads)

### 👤 User Features
- **Task Operations**
  - Update task status
  - View task details and history
  - Add comments and participate in task discussions
  - Track personal task progress

### 🌟 General Features
- **Authentication & Security**
  - Secure user authentication
  - Role-based access control
  - JWT-based authorization

- **Dashboard & Analytics**
  - Intuitive task overview
  - Status-based task filtering
  - Activity tracking
  - Performance metrics

## 🛠️ Technical Stack

### Frontend
- **Core**: React (Vite)
- **State Management**: Redux Toolkit
- **UI Components**: Headless UI
- **Styling**: Tailwind CSS
- **Additional Libraries**:
  - React Router DOM for routing
  - React Hook Form for form handling
  - Recharts for analytics
  - Moment.js for date handling
  - Sonner for notifications

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **Security**: bcryptjs
- **Middleware**: cors, cookie-parser, morgan

## 📦 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- MongoDB Atlas account
- Git

### Backend Setup
1. Navigate to the server directory:
   ```bash
   cd server
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a .env file in the server directory:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   PORT=8800
   NODE_ENV=development
   ```

4. Start the server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the client directory:
   ```bash
   cd client
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a .env file in the client directory:
   ```env
   VITE_APP_BASE_URL=http://localhost:8800
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## 🌐 MongoDB Atlas Setup

1. Visit [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
2. Create a free account or sign in
3. Create a new cluster
4. Configure database access:
   - Create a database user
   - Set up IP whitelist
5. Get your connection string
6. Add the connection string to your server's .env file

## 🔐 Security Features
- Password hashing using bcryptjs
- JWT-based authentication
- Secure HTTP-only cookies
- CORS protection
- Environment variable protection

## 🎯 Best Practices
- Modern React patterns and hooks
- RESTful API design
- Proper error handling
- Responsive design
- Code splitting and lazy loading
- Performance optimization

## 📱 Responsive Design
The application is fully responsive and works seamlessly across:
- Desktop computers
- Tablets
- Mobile devices

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support
For support, please contact:
- Email: codewavewithasante@gmail.com
- Telegram: [Codewave_with_asante](https://t.me/Codewave_with_asante)

## 📄 License
This project is licensed under the ISC License.

---
Made with ❤️ by CodeWave
