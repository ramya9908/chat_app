# Real-Time Chat Application

A modern, full-stack chat application built with the MERN stack, featuring real-time messaging, user authentication, and a responsive design.

![Chat App Demo](demo-image.png)

## ✨ Features

- **Real-time messaging** with Socket.io
- **User authentication & authorization** using JWT
- **Online user status** tracking
- **Responsive design** with TailwindCSS and DaisyUI
- **Global state management** with Zustand
- **Secure password hashing** with bcryptjs
- **Error handling** on both client and server
- **Professional deployment** ready

## 🛠️ Tech Stack

**Frontend:**
- React.js
- TailwindCSS
- DaisyUI
- Zustand (State Management)
- Socket.io Client

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose
- Socket.io
- JWT Authentication
- bcryptjs

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- MongoDB database
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd chat-app-yt
   ```

2. **Install dependencies**
   ```bash
   npm run build
   ```

3. **Environment Setup**
   
   Create a `.env` file in the root directory:
   ```env
   PORT=5000
   MONGO_DB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   NODE_ENV=development
   ```

4. **Start the application**
   
   For development:
   ```bash
   npm run server
   ```
   
   For production:
   ```bash
   npm start
   ```

5. **Access the application**
   
   Open your browser and navigate to `http://localhost:5000`

## 📁 Project Structure

```
chat-app-yt/
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── socket/
│   ├── utils/
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── pages/
│   │   ├── store/
│   │   └── utils/
│   └── package.json
├── .env
└── package.json
```

## 🔧 Available Scripts

- `npm run server` - Start development server with nodemon
- `npm start` - Start production server
- `npm run build` - Install all dependencies and build the project

## 🔐 Environment Variables

| Variable | Description | Example |
|----------|-------------|---------|
| `PORT` | Server port number | `5000` |
| `MONGO_DB_URI` | MongoDB connection string | `mongodb://localhost:27017/chatapp` |
| `JWT_SECRET` | Secret key for JWT tokens | `your_super_secret_key` |
| `NODE_ENV` | Environment mode | `development` or `production` |

## 🔑 Authentication

The application uses JWT (JSON Web Tokens) for authentication:

- **Registration**: Users can create new accounts with username and password
- **Login**: Secure login with password hashing
- **Protected Routes**: Middleware protection for authenticated routes
- **Persistent Sessions**: JWT tokens stored in HTTP-only cookies

## 📡 Real-time Features

- **Instant messaging** between users
- **Online/offline status** indicators
- **Message delivery** confirmations
- **Typing indicators** (if implemented)
- **Room-based chat** functionality

## 🎨 UI Components

Built with modern, responsive design:

- Clean and intuitive chat interface
- Mobile-friendly responsive layout
- Dark/light theme support (if implemented)
- Custom styled components with DaisyUI
- Smooth animations and transitions

## 🚀 Deployment

The application is deployment-ready for platforms like:

- **Heroku**
- **Vercel**
- **Netlify**
- **Railway**
- **DigitalOcean**

Make sure to:
1. Set environment variables in your hosting platform
2. Update MongoDB connection string for production
3. Configure CORS settings if needed

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the ISC License.

## 🐛 Issues

If you encounter any issues or have suggestions, please create an issue in the repository.

## 🔗 Connect

Feel free to reach out for any questions or collaboration opportunities!

---

**Built with ❤️ using the MERN Stack**
