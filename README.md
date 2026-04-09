# 🌤️ Weather Web Application

Welcome to the Weather Web Application, a sleek and responsive web app that delivers real-time weather updates and 5-day forecasts powered by the OpenWeatherMap API. With a modern and intuitive UI/UX, this app showcases temperature, pressure, humidity, and wind speed in a visually engaging format, optimized for all devices.

---

**Link:https://weatherwebapp-45d60.web.app/

## ✨ Features

- 🌡️ **Real-Time Weather**: Instantly view current weather conditions, including temperature, pressure, humidity, and wind speed.
- 📅 **5-Day Forecast**: Plan ahead with a detailed 5-day weather forecast for any location.
- 📱 **Responsive Design**: Enjoy a seamless experience on desktops, tablets, and mobile devices.
- 🖼️ **Intuitive UI/UX**: A clean, modern interface designed for effortless navigation and readability.
- 🌐 **API Integration**: Harnesses the power of the OpenWeatherMap API for accurate, up-to-date weather data.
- 🔥 **Firebase Hosting**: Deployed and hosted on Firebase for reliable performance.

---

## 🎥 Demo

- 🌍 **Live Demo**: Explore the app in action [here](https://weatherwebapp-45d60.web.app/).
- 🎬 **Demo Video**: Watch a quick walkthrough [here](https://drive.google.com/file/d/11o__ffVwohRo6xtcYPeTn2vQ5QHRIAkA/view?usp=drive_link).

---

## 🛠️ Technologies Used

- **HTML5**: Structured, semantic markup for the app's foundation.
- **CSS3**: Stylish, responsive design with smooth animations and transitions.
- **JavaScript**: Dynamic functionality and seamless API integration with OpenWeatherMap.
- **Firebase**: Hosting platform for deployment and scalability.
- **OpenWeatherMap API**: Reliable source for real-time weather and forecast data.

---

## 🚀 Installation

Get the app running locally in just a few steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/[your-username]/[your-repo-name].git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd [your-repo-name]
   ```

3. **Obtain an OpenWeatherMap API Key**:
   - Sign up at [OpenWeatherMap](https://openweathermap.org/) to get your free API key.
   - Create a `.env` file in the project root and add:
     ```env
     API_KEY=your_openweathermap_api_key
     ```

4. **Install Dependencies**:
   ```bash
   npm install
   ```

5. **Run the Application**:
   - For local development, serve the `public` folder using a local server (e.g., `npx serve public`).
   - Alternatively, deploy to Firebase:
     ```bash
     npm install -g firebase-tools
     firebase login
     firebase deploy
     ```

---

## 🌟 Usage

- **Search**: Enter a city name or zip code in the search bar to fetch weather data.
- **Explore**: View current weather and a 5-day forecast with key metrics.
- **Responsive**: Enjoy a consistent experience across all screen sizes.

---

## 📂 Project Structure

```
├── .firebaserc               # Firebase project configuration
├── .gitignore                # Files and directories to ignore in version control
├── firebase.json             # Firebase hosting configuration
├── package.json              # Node.js dependencies and scripts
├── package-lock.json         # Dependency lock file for consistent installs
├── pglite-debug.log          # Debug log file (ignored by .gitignore)
├── public/
│   ├── index.html            # Core HTML structure   
```

---

## 🤝 Contributing

We welcome contributions to make this project even better! Here's how to get started:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request and describe your changes.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute as per the license terms.

---

## 🙌 Acknowledgements

- 🌦️ [OpenWeatherMap](https://openweathermap.org/) for their robust weather API.
- 🔥 [Firebase](https://firebase.google.com/) for reliable hosting and deployment tools.
- [Add other acknowledgements, e.g., libraries, tutorials, or inspirations].

---

🌞 **Stay updated, stay weather-ready!**
