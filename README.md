"# Freelancer Hub

Freelancer Hub is a full-stack web application that connects freelancers with clients, providing a platform for task posting, bidding, and project management. Built with modern technologies including React, Node.js, and MongoDB.

## 🚀 Features

- **User Authentication**: Secure login and signup system using Firebase
- **Task Management**: Post, browse, and manage tasks
- **Real-time Bidding System**: Place and view bids on tasks
- **Dashboard**: Comprehensive overview of tasks and activities
- **Category-based Browsing**: Browse tasks by categories
- **Search Functionality**: Advanced search capabilities with modal interface
- **Responsive Design**: Mobile-first approach using Tailwind CSS
- **Theme Toggle**: Support for light and dark themes
- **Progress Tracking**: Visual representation of task progress using Chart.js
- **Review System**: Rate and review freelancers and clients

## 🛠️ Tech Stack

### Frontend
- React (v19)
- Vite
- Tailwind CSS
- DaisyUI
- Firebase Authentication
- Chart.js
- Framer Motion
- React Router DOM
- SweetAlert2
- Swiper

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- CORS
- dotenv

## 📁 Project Structure

```
├── frontend/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── firebase/
│   │   ├── layout/
│   │   ├── pages/
│   │   ├── provider/
│   │   ├── routes/
│   │   └── utils/
│   └── public/
└── backend/
    └── index.js
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- MongoDB

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a .env file in the backend directory with your MongoDB connection string:
   ```
   MONGODB_URI=your_mongodb_connection_string
   ```

4. Start the server:
   ```bash
   npm run dev
   ```

## 🔐 Environment Variables

### Frontend
Create a `.env` file in the frontend directory with your Firebase configuration:

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### Backend
Create a `.env` file in the backend directory:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

## 📱 Key Components

- **Header**: Navigation and authentication status
- **Banner**: Hero section with key features
- **TaskCard**: Displays individual task information
- **BrowseCategory**: Category-based task filtering
- **SearchModal**: Advanced search interface
- **DashboardLayout**: Admin/user dashboard interface
- **AuthProvider**: Authentication context provider
- **PrivateRoute**: Protected route implementation

## 🔒 Authentication

The application uses Firebase Authentication with the following features:
- Email/Password authentication
- Social media login options
- Protected routes
- Persistent login state

## 🎯 Future Enhancements

- Real-time chat system
- Payment integration
- File sharing capabilities
- Advanced filtering options
- Mobile application
- Email notifications
- Rating and review system

## 👥 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.

## 👤 Author

ARISH

---

For more information or support, please open an issue in the repository." 
