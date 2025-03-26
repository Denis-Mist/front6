# 🔒 Fullstack Authentication Example with JWT

A simple fullstack application demonstrating JWT-based authentication with a Node.js backend and a vanilla JavaScript frontend.

![Demo](https://via.placeholder.com/800x400.png?text=Authentication+Demo) *Replace with actual screenshot*

## ✨ Features

- **User Registration**  
  Create a new account with email and password.
- **JWT Authentication**  
  Secure login using JSON Web Tokens.
- **Protected Routes**  
  Access restricted content after successful authentication.
- **In-Memory User Storage**  
  Users stored in a runtime array (persists until server restart).

## 🛠️ Technologies

**Backend**  
- Node.js
- Express
- JWT
- CORS

**Frontend**  
- Vanilla JavaScript
- Fetch API
- Bootstrap (for styling)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Denis-Mist/front6
   cd auth-jwt-demo
   Install backend dependencies

bash
Copy
cd backend
npm install
Set environment variables
Create .env file in /backend:

env
Copy
JWT_SECRET=your_strong_secret_here
PORT=5000
Start the backend server

bash
Copy
npm start
Launch the frontend
Open frontend/index.html in a web browser.

📖 Usage
Register

Navigate to: /frontend/index.html

Fill in email and password

Click "Register"

Login

Use your credentials

Successful login stores JWT in localStorage

Access Protected Data

Click "Get Protected Data" after login

Server verifies JWT before responding

🌐 API Endpoints
Method	Endpoint	Description
POST	/api/register	User registration
POST	/api/login	User authentication
GET	/api/protected	JWT-protected test endpoint
🔧 Testing with Curl
Registration

bash
Copy
curl -X POST -H "Content-Type: application/json" \
-d '{"email":"test@example.com","password":"secret"}' \
http://localhost:5000/api/register
Login

bash
Copy
curl -X POST -H "Content-Type: application/json" \
-d '{"email":"test@example.com","password":"secret"}' \
http://localhost:3000/api/login
📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Contributing
Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

Made with ❤️ by [Your Name] | Live Demo | Documentation

Copy

*Replace placeholder values (yourusername, [Your Name], demo links) with actual project details. Add real screenshots and update the license file as needed.*
