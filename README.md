"# Freelancer Hub

Freelancer Hub is a full-stack web application that connects freelancers with clients, providing a platform for task posting, bidding, and project management. Built with modern technologies including React, Node.js, and MongoDB.

## � About

Freelancer Hub is an innovative online marketplace designed to revolutionize the way freelancers and clients connect and collaborate. In today's digital age, where remote work and independent contracting are becoming increasingly prevalent, our platform serves as a bridge between talented professionals and businesses seeking their expertise.

### 🎯 Vision
Our vision is to create a seamless, transparent, and efficient ecosystem where talent meets opportunity. We believe in empowering freelancers to showcase their skills while helping businesses find the perfect match for their projects.

### 💡 What Sets Us Apart
- **Smart Matching**: Our platform uses intelligent algorithms to connect clients with the most suitable freelancers based on skills, experience, and project requirements.
- **Secure Transactions**: Built-in payment protection and milestone-based payment system ensures security for both parties.
- **Quality Assurance**: Comprehensive review system and portfolio showcase helps maintain high-quality service standards.
- **Community Focus**: We foster a supportive community where professionals can grow, learn, and collaborate.

### 🌟 Core Values
1. **Transparency**: Clear communication and honest feedback
2. **Innovation**: Continuously improving user experience
3. **Quality**: Maintaining high standards in service delivery
4. **Security**: Protecting user data and transactions
5. **Community**: Building a supportive professional network

### 🎉 Who It's For
- **Freelancers**: Professionals looking to showcase their skills and find quality projects
- **Businesses**: Companies seeking talented professionals for their projects
- **Entrepreneurs**: Startups and small businesses looking for flexible workforce solutions
- **Agencies**: Creative and technical agencies looking to expand their talent pool

## �🚀 Features

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
