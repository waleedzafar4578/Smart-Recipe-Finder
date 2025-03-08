# Smart Recipe Finder

A web and mobile application that helps users discover recipes based on available ingredients. Built with Flask, React, and React Native (upcoming).

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

Smart Recipe Finder solves the common problem of deciding what to cook based on available ingredients. Users can input their available ingredients and receive personalized recipe suggestions, complete with detailed instructions and nutritional information.

## ✨ Features

### Core Features
- **Ingredient-Based Recipe Search**
  - Input available ingredients
  - Get matching recipe suggestions
  - Smart recipe ranking system

- **Detailed Recipe Information**
  - Step-by-step cooking instructions
  - Cooking time and difficulty level
  - Comprehensive nutrition facts
  - Required ingredients list

- **User Preferences**
  - Filter by cuisine type
  - Dietary restrictions support
  - Meal type categorization
  - Save favorite recipes

### Upcoming Features
- 📸 Image-based ingredient detection using Google Vision API
- 🎤 Voice input for ingredients
- 🤖 AI-powered personalized recipe recommendations

## 🛠 Tech Stack

### Backend
- **Flask** - Python web framework
- **Spoonacular API** - Recipe data source
- **OpenAI API** - AI-generated recipes (planned)
- **PostgreSQL/MongoDB** - Data storage
- **JWT** - Authentication

### Frontend (Web)
- **React.js** - UI framework
- **Material UI** - Styling
- **Axios** - API communication
- **Redux** - State management (optional)

### Mobile (Upcoming)
- **React Native** - Cross-platform mobile development
- **Expo** - Development toolkit
- **React Navigation** - Screen management

## 📁 Project Structure
```
smart-recipe-finder/
│── backend/ # Flask Backend
│ ├── app.py # Main Flask API
│ ├── models.py # Database models
│ ├── routes.py # API routes
│ └── utils.py # Helper functions
│
│── frontend/ # React Frontend
│ ├── src/
│ │ ├── components/ # Reusable components
│ │ ├── pages/ # Main pages
│ │ └── services/ # API services
│ └── package.json
│
│── mobile/ # React Native App (Future)
├── src/
│ ├── components/ # Mobile components
│ ├── screens/ # App screens
│ └── navigation/ # Navigation setup
└── app.json # Expo config
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- Python (v3.8 or higher)
- PostgreSQL/MongoDB

### Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

### Frontend Setup
```bash
cd frontend
npm install
npm start
```

### Mobile Setup (Coming Soon)
```bash
cd mobile
npm install
expo start
```

## 📚 API Documentation

Detailed API documentation will be available after backend implementation.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 📞 Contact

For any questions or suggestions, please open an issue in the repository.