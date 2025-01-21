# Weather Forecast and Travel Recommendations

This Python-based project fetches a 3-day weather forecast for a specified city using the WeatherAPI. It provides detailed weather information, travel tips, and activity recommendations based on forecasted conditions. Additionally, it visualizes weather trends with clear bar charts and line plots. This tool is ideal for trip planning or gaining detailed weather insights.

---

## Features

### Key Weather Information
- Detailed forecast: Max & Min Temperatures, Average Humidity, Wind Speed, and Weather Conditions.
- Precipitation chances: Daily chances of rain and snow.

### Travel & Activity Recommendations
- Tailored advice based on the forecast, including packing tips and safety precautions.

### Visualizations
- Bar charts for maximum and minimum temperatures.
- Line graphs for average humidity trends.

---

## Technologies and Libraries Used
- Python 3.x
- Requests: For accessing the WeatherAPI.
- Matplotlib: For visualizing the forecast data.

---

## Installation

### Step 1: Clone the Repository

    git clone <repository_url>
    cd weather-forecast
    
### Step 2: Install Required Dependencies

    pip install requests matplotlib

### Step 3: Obtain WeatherAPI Key
  - Sign up at WeatherAPI to get a free API key.
  - Replace the api_key variable in the script with your API key:

        api_key = "your_api_key_here"
## Usage
1. Run the script:
   
       python weather_forecast.
2. Enter the name of the city when prompted:

       Enter city name: London
3. View the detailed forecast, travel recommendations, and weather visualizations.

## Example Output
### Console Output:

     Enter city name: London

    3-Day Weather Forecast for London, United Kingdom:

    Date: 2025-01-21
    Condition: Sunny
    Max Temperature: 12°C
    Min Temperature: 4°C
    Humidity: 58%
    Chance of Rain: 10%
    Chance of Snow: 0%
    Wind Speed: 10 km/h
    ------------------------------

    Travel Recommendations:
    - Great day for sightseeing or outdoor activities!

    Suggested Activities:
    - Explore parks, go cycling, or enjoy outdoor cafes.
    ------------------------------
    
## Visualization:
  - Bar Chart: Displays maximum and minimum temperatures for the next 3 days.
  - Line Graph: Shows the average humidity trend over the forecasted period.

## Highlights and Benefits
  - Accurate and real-time data: Powered by WeatherAPI for reliable forecasts.
  - Travel-friendly: Offers actionable advice for trip planning.
  - Intuitive visuals: Helps users understand weather trends at a glance.

## Future Enhancements
  - Extended forecast: Include weekly or monthly forecasts.
  - City comparisons: Add support for comparing weather across multiple cities.
  - Data export: Save forecast data and visuals to files for offline use.
  - Enhanced visualizations: Include wind and precipitation trends in the graphs.

## Contributing
  ### Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   
       git checkout -b feature-name
3. Commit your changes:

       git commit -m "Added new feature"
4. Push the branch:

       git push origin feature-name
5. Open a pull request.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code.




