# Zerodha Trading Platform Clone

A full-stack web application that replicates the core functionality of Zerodha's trading platform, including a landing page, dashboard for trading operations, and backend API services.

## 🚀 Project Overview

This project consists of three main components:
- **Frontend**: Marketing/landing pages (React)
- **Dashboard**: Trading dashboard with portfolio management (React + Material-UI)
- **Backend**: RESTful API server (Node.js + Express + MongoDB)

## 📁 Project Structure

```
Zerodha/
├── frontend/          # Landing page and marketing site
├── dashboard/         # Trading dashboard application
├── backend/           # API server and database
└── README.md
```

## 🛠️ Technology Stack

### Frontend
- **React 18** - UI library
- **React Router DOM** - Client-side routing
- **CSS3** - Styling

### Dashboard
- **React 18** - UI framework
- **Material-UI v5** - Component library
- **Chart.js** - Data visualization
- **Axios** - HTTP client
- **React Router DOM** - Navigation

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM for MongoDB
- **Passport.js** - Authentication middleware
- **CORS** - Cross-origin resource sharing
- **Nodemon** - Development server

## 🎯 Features

### Landing Page (Frontend)
- Home page with hero section
- About page with team information
- Pricing page with brokerage details
- Products showcase
- Support ticket system
- User signup functionality

### Trading Dashboard
- Portfolio summary and overview
- Holdings management
- Active positions tracking
- Order placement and management
- Watchlist functionality
- Interactive charts and graphs
- Funds management

### Backend API
- User authentication and authorization
- CRUD operations for holdings, orders, and positions
- MongoDB data persistence
- RESTful API endpoints

## 🚦 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Zerodha
   ```

2. **Setup Backend**
   ```bash
   cd backend
   npm install
   npm start
   ```
   Server runs on `http://localhost:3002`

3. **Setup Frontend**
   ```bash
   cd frontend
   npm install
   npm start
   ```
   Application runs on `http://localhost:3000`

4. **Setup Dashboard**
   ```bash
   cd dashboard
   npm install
   npm start
   ```
   Dashboard runs on `http://localhost:3001`

### Environment Variables

Create a `.env` file in the backend directory:
```env
MONGODB_URI=your_mongodb_connection_string
PORT=3002
SESSION_SECRET=your_session_secret
```

## 📱 Application Flow

1. **Landing Page** (`localhost:3000`)
   - Users can explore features, pricing, and company information
   - Sign up for new accounts
   - Access support resources

2. **Trading Dashboard** (`localhost:3001`)
   - Authenticated users can manage their portfolio
   - View real-time data and charts
   - Place and track orders
   - Monitor holdings and positions

3. **Backend API** (`localhost:3002`)
   - Handles all data operations
   - Manages user authentication
   - Provides RESTful endpoints for frontend consumption

## 🔧 Development Scripts

### Backend
```bash
npm start          # Start development server with nodemon
```

### Frontend & Dashboard
```bash
npm start          # Start development server
npm build          # Build for production
npm test           # Run tests
```

## 📊 Data Models

The application uses the following data models:
- **Holdings**: User's stock holdings
- **Orders**: Buy/sell orders
- **Positions**: Active trading positions
- **Users**: Authentication and user management

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is for educational purposes and is not affiliated with the official Zerodha platform.

## 🎓 Learning Objectives

This project demonstrates:
- Full-stack JavaScript development
- RESTful API design
- React component architecture
- State management
- Database integration
- Authentication implementation
- Responsive web design
