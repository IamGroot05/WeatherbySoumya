# Weather Forecast Web Application

This is a web application that provides weather forecasts based on the user's current location or a searched city. The application uses the OpenWeather API to fetch weather data and the Pexels API to display background images that change based on the weather conditions and time of day (e.g., day, night, rain, cloudy).

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Current Location Weather:** Automatically displays the weather forecast based on the user's current location.
- **City Search:** Allows users to search for the weather forecast of any city.
- **Dynamic Background:** Changes the background image based on the weather conditions and time of day using the Pexels API.

## Technologies Used

- **HTML:** Markup language for creating the web application's structure.
- **CSS:** Stylesheet language for designing the web application's appearance.
- **JavaScript:** Programming language for implementing functionality.
- **OpenWeather API:** Used to fetch weather data.
- **Pexels API:** Used to fetch background images based on weather conditions and time of day.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/weather-forecast-app.git
   cd weather-forecast-app
2. **Open index.html:**
   Simply open the index.html file in your web browser to run the application.

## Usage
**Current Location Weather:**
- When the application loads, it will ask for permission to access your location.
- Allow location access to see the weather forecast for your current location.
  
**Search City Weather:**
- Use the search bar to enter the name of a city.
- Press the "Search" button to view the weather forecast for the entered city.
  
**Dynamic Background:**
- The background image will change based on the current weather conditions and time of day (day, night, rain, cloudy, etc.) of the searched city.

## File Structure
  weather-forecast-app/
  │
  ├── index.html          # Main HTML file
  ├── style.css           # CSS file for styling
  ├── script.js           # JavaScript file for functionality
  └── assets/             # Directory for assets (images, icons, etc.)

## Contributing
**Contributions are welcome! Please follow these steps:**
  1. Fork the repository.
  2. Create a new branch (git checkout -b feature-branch).
  3. Commit your changes (git commit -m 'Add some feature').
  4. Push to the branch (git push origin feature-branch).
  5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Thanks to the OpenWeather team for their excellent weather API.
Thanks to the Pexels team for providing high-quality images for the dynamic background feature.
