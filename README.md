# Weather Journal App

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js Version](https://img.shields.io/badge/node-14.x-green.svg)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/express-4.x-blue.svg)](https://expressjs.com/)

## 📋 Overview
The Weather Journal App is a dynamic web application that combines real-time weather data with personal mood tracking capabilities. This full-stack application demonstrates the integration of the OpenWeatherMap API with a Node.js/Express backend, providing users with current weather information while allowing them to log their emotional state.

## ✨ Key Features
- Real-time weather data fetching from OpenWeatherMap API
- Personal mood tracking functionality
- Dynamic UI updates without page reload
- Responsive design for all device sizes
- Local data persistence
- Error handling and user feedback

## 🛠 Tech Stack
- **Frontend:**
  - HTML5 for structure
  - CSS3 for styling and animations
  - Vanilla JavaScript for dynamic interactions
- **Backend:**
  - Node.js runtime environment
  - Express.js web framework
- **API Integration:**
  - OpenWeatherMap API for weather data
- **Data Storage:**
  - Local JSON storage (No database required)

## 📦 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-journal-app.git
   cd weather-journal-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   - Create a `.env` file in the root directory
   - Add your OpenWeatherMap API key:
     ```env
     API_KEY=your_api_key_here
     PORT=3000
     ```

## 🔑 OpenWeatherMap API Setup
1. Visit [OpenWeatherMap](https://openweathermap.org/) and create an account
2. Navigate to the API keys section in your account dashboard
3. Generate a new API key
4. Copy the API key to your `.env` file
5. Wait a few hours for the API key to activate

## 🚀 Running the Application
1. Start the development server:
   ```bash
   npm start
   # or
   node server.js
   ```
2. Access the application:
   ```
   http://localhost:3000
   ```

## 📁 Project Structure
```
weather-journal/
├── website/              # Frontend assets
│   ├── index.html       # Main HTML file
│   ├── app.js          # Frontend JavaScript
│   ├── style.css       # Styles and layout
├── server.js           # Express server setup
├── package.json        # Project dependencies
├── .env                # Environment variables
├── .gitignore         # Git ignore rules
└── README.md          # Project documentation
```

## 📸 Screenshots
[Coming Soon] The application interface will be showcased here, including:
- Home page layout and design
- Weather data visualization
- User input form interface
- Dynamic response displays

## 🤝 Contributing
Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔐 Security
- Never commit API keys or sensitive data to version control
- Always use environment variables for sensitive information
- Regularly update dependencies to patch security vulnerabilities

---

*Built with ❤️ by [Your Name]*

[⬆ back to top](#weather-journal-app)
