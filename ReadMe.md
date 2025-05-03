Ensa-Gram
Ensa-Gram is a real-time chat application designed for seamless communication for the student of ENSA . It features user authentication, real-time messaging, and customizable themes, all wrapped in a modern and responsive UI.

Features
User Authentication: Secure sign-up, login, and profile management.
Real-Time Messaging: Instant communication using WebSockets.
Theme Customization: Choose from multiple themes powered by DaisyUI.
Responsive Design: Optimized for all devices.
Modern UI: Built with Tailwind CSS and DaisyUI for a clean and customizable interface.
Tech Stack
Frontend:
React: Component-based UI library.
Vite: Fast development server and build tool.
Zustand: Lightweight state management.
Tailwind CSS: Utility-first CSS framework.
DaisyUI: Tailwind CSS component library.
Socket.IO Client: Real-time communication.
Backend:
Node.js: JavaScript runtime.
Express: Web framework for Node.js.
MongoDB: NoSQL database.
Mongoose: MongoDB object modeling.
Socket.IO: Real-time communication.
Installation
Prerequisites
Node.js (v16 or higher)
MongoDB



FrontEnd
# React and Vite
npm install react react-dom
npm install --save-dev vite @vitejs/plugin-react

# Zustand for state management
npm install zustand

# Tailwind CSS and DaisyUI for styling
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
npm install daisyui

# React Router for routing
npm install react-router-dom

# React Hot Toast for notifications
npm install react-hot-toast

# Lucide React for icons
npm install lucide-react

# Socket.IO client for real-time communication
npm install socket.io-client


BackEnd 
# Express for server setup
npm install express

# CORS for handling cross-origin requests
npm install cors

# dotenv for environment variables
npm install dotenv

# MongoDB and Mongoose for database
npm install mongoose

# JSON Web Token (JWT) for authentication
npm install jsonwebtoken

# bcrypt for password hashing
npm install bcrypt

# Socket.IO for real-time communication
npm install socket.io

# Nodemon for development (optional)
npm install --save-dev nodemon