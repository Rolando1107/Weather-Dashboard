Weather Dashboard 🌤️
A simple, lightweight weather app that provides real-time weather information for cities, including a 5-day forecast. This app fetches data from a weather API and allows users to track weather in multiple locations. It also saves a history of searched cities in a local JSON file for future reference.

Features
Real-Time Weather: Get current weather details such as temperature, wind speed, humidity, and more for any city.
5-Day Forecast: View upcoming weather conditions to plan ahead.
Search History: Store and manage a history of previously searched cities.
Lightweight Design: Built with a modular architecture for ease of use and scalability.
User-Friendly Backend: Developed using Node.js and TypeScript for maintainability and performance.
Technologies Used
Backend: Node.js with TypeScript.
HTTP Requests: node-fetch for API calls.
Environment Management: dotenv for secure environment variables.
Unique Identifiers: uuid for generating unique city IDs.
File System Operations: fs/promises for seamless JSON file handling.
Getting Started
Prerequisites
Make sure you have the following installed:

Node.js (v14 or higher)
npm (v6 or higher)
Installation
Clone the repository:

bash
Copy code
git clone git@github.com:moayed10111/WeatherApp.git
cd WeatherApp
Install dependencies:

bash
Copy code
npm install
Create a .env file at the root of the project:

plaintext
Copy code
API_BASE_URL=<YOUR_WEATHER_API_BASE_URL>
API_KEY=<YOUR_API_KEY>
Set up the database:

Create a folder named db in the root of the project.

Inside db, create an empty JSON file named db.json to store city data:

bash
Copy code
mkdir db && echo "[]" > db/db.json
Usage
Start the application:

bash
Copy code
npm start
Access the app via your terminal or extend it with a frontend.

Contributing
We welcome contributions! To contribute:

Fork the repository.

Create a new branch:

bash
Copy code
git checkout -b feature/YourFeature
Make your changes and commit them:

bash
Copy code
git commit -m "Add your feature"
Push the changes to your branch:

bash
Copy code
git push origin feature/YourFeature
Open a pull request, and we’ll review it promptly.

License
This project is licensed under the MIT License.

Future Enhancements 🚀
UI Integration: Build a frontend using React or Vue.js.
User Authentication: Enable users to save their city preferences securely.
Advanced Analytics: Include detailed metrics like air quality and precipitation probability.
Enjoy using the Weather Dashboard and stay informed about the weather wherever you go! 😊

Feel free to customize this further based on additional features or design goals.






