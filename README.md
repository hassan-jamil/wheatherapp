# WeatherApp

## Project Overview
The WeatherApp is a dynamic and user-friendly application designed to provide accurate and real-time weather updates for users across the globe. The primary purpose of the project is to offer a seamless way to check current weather conditions, hourly and weekly forecasts, and other weather-related information. It aims to solve the problem of quickly accessing reliable weather data in an intuitive interface.

## Key Features
- **Real-Time Weather Updates**: Displays current weather conditions for any location.
- **Hourly and Weekly Forecasts**: Provides detailed hourly and 7-day weather forecasts.
- **Search by Location**: Allows users to search for weather details by city or coordinates.
- **User-Friendly Interface**: Clean and intuitive UI for an enhanced user experience.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.

## Requirements
To set up and run the WeatherApp, ensure you have the following installed:

- **Programming Language**: Python (Version 3.8 or higher)
- **Framework**: Flask
- **APIs**: OpenWeatherMap API (API key required)
- **Dependencies**:
  - requests
  - flask
  - python-dotenv

## Installation and Usage Instructions
Follow these steps to set up and run the WeatherApp locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/hassan-jamil/weatherapp.git
   cd weatherapp
   ```

2. **Set Up a Virtual Environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Environment Variables**:
   - Create a `.env` file in the root directory.
   - Add your OpenWeatherMap API key:
     ```env
     API_KEY=your_openweathermap_api_key
     ```

5. **Run the Application**:
   ```bash
   flask run
   ```
   The application will be available at `http://127.0.0.1:5000/`.

## Benefits of the Project
- **Accurate Data**: Utilizes the OpenWeatherMap API to provide reliable weather information.
- **Enhanced Productivity**: Enables quick access to weather data, aiding users in planning their day efficiently.
- **Accessible Anywhere**: A responsive design ensures usability on various devices, including smartphones and tablets.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute the software, provided the original license is included. For more details, refer to the `LICENSE` file in the repository.

## Social Media Links
Connect with the developer for feedback, collaboration, or queries:

- **GitHub**: [https://github.com/hassan-jamil](https://github.com/hassan-jamil)
- **LinkedIn**: [Insert LinkedIn link here]
- **Twitter**: [Insert Twitter handle here]
- **Email**: [Insert email here]

## File Structure
Here is an overview of the repository structure:

```
weatherapp/
│
├── app.py               # Main application file
├── requirements.txt     # Python dependencies
├── .env                 # Environment variables
├── static/              # Static files (CSS, JS, images)
├── templates/           # HTML templates
└── README.md            # Project documentation
```

Feel free to explore the project and contribute to its development!

