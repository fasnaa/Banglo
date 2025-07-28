# Banglo - Your Ultimate Travel Itinerary Planner

![Banglo Logo](frontend/public/images/img1.jpeg)

## 🌟 Overview

Banglo is a modern web application that helps travelers create personalized day itineraries based on their interests, budget, and available time. Whether you're exploring a new city or looking to make the most of your day, Banglo provides intelligent recommendations to ensure you have the perfect adventure.

## ✨ Features

- **Personalized Itinerary Generation**: Create custom day plans based on your interests
- **Budget-Friendly Planning**: Filter activities within your budget constraints
- **Time Management**: Optimize your schedule based on available time
- **Interactive UI**: Modern, responsive design with smooth animations
- **Real-time Recommendations**: Get instant itinerary suggestions

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern UI framework
- **React Router DOM** - Client-side routing
- **Material-UI** - Component library
- **Framer Motion** - Animation library
- **React Icons** - Icon library
- **Axios** - HTTP client
- **Tailwind CSS** - Utility-first CSS framework

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database (with Mongoose ODM)
- **JWT** - Authentication
- **bcryptjs** - Password hashing
- **CORS** - Cross-origin resource sharing
- **dotenv** - Environment variables

## 📁 Project Structure

```
Banglo-1/
├── frontend/                 # React frontend application
│   ├── public/
│   │   ├── images/          # Static images
│   │   └── index.html
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/          # Page components
│   │   └── App.js          # Main application component
│   └── package.json
├── backend/                  # Node.js backend server
│   ├── config/
│   │   └── db.js           # Database configuration
│   ├── data/
│   │   └── places.json     # Places data
│   ├── routes/
│   │   └── dayPlanner.js   # API routes
│   ├── server.js           # Express server
│   └── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- MongoDB (for backend)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Banglo-1
   ```

2. **Install frontend dependencies**
   ```bash
   cd frontend
   npm install
   ```

3. **Install backend dependencies**
   ```bash
   cd ../backend
   npm install
   ```

4. **Set up environment variables**
   
   Create a `.env` file in the backend directory:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. **Start the development servers**

   **Backend (Terminal 1):**
   ```bash
   cd backend
   npm run dev
   ```

   **Frontend (Terminal 2):**
   ```bash
   cd frontend
   npm start
   ```

6. **Access the application**
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5000

## 📱 Usage

1. **Home Page**: Explore the landing page with beautiful imagery
2. **Plan Your Day**: Click "Plan Your Day" to access the itinerary planner
3. **Customize Preferences**: Set your budget, available time, and interests
4. **Generate Itinerary**: Get personalized recommendations
5. **View Results**: See your optimized day plan with timing

## 🔧 API Endpoints

### Day Planner
- `POST /api/day-planner/generate-itinerary`
  - **Body**: `{ budget, availableTime, interests }`
  - **Response**: `{ itinerary: [{ time, activity }] }`

## 🎨 Features in Detail

### Smart Itinerary Generation
- Filters places based on user interests
- Respects budget constraints
- Optimizes time allocation
- Provides realistic timing estimates

### Modern UI/UX
- Responsive design for all devices
- Smooth animations and transitions
- Intuitive navigation
- Beautiful imagery and layouts

### Data-Driven Recommendations
- Comprehensive places database
- Tagged interests and categories
- Cost and duration information
- Location-based suggestions

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 📞 Support

If you have any questions or need support, please open an issue in the repository.

---

**Made with ❤️ for travelers around the world**
