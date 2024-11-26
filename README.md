# Weather Application

A simple and user-friendly Weather Application built using Python's `tkinter` library to provide real-time weather updates for a city.

## Features
- Fetches live weather data using OpenWeatherMap API.
- Displays the following weather details:
  - Temperature (in Kelvin)
  - Atmospheric Pressure (in hPa)
  - Humidity (in percentage)
  - Weather Description
- Error handling for invalid city names.
- Clear functionality to reset the input and output fields.

## Prerequisites
- Python 3.x installed on your system.
- The following Python libraries installed:
  - `requests`
  - `tkinter` (comes pre-installed with Python)

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install Required Libraries:**
   ```bash
   pip install requests
   ```

3. **Set Up API Key:**
   - Sign up for a free API key from [OpenWeatherMap](https://openweathermap.org/api).
   - Replace `api_key` in the script with your API key.

4. **Run the Application:**
   ```bash
   python weatherapp.py
   ```

## How to Use
1. Enter the name of a city in the input field.
2. Click on the "Submit" button to fetch the weather data.
3. The application will display the temperature, pressure, humidity, and a brief description of the weather.
4. Use the "Clear" button to reset the input and output fields.

## File Structure
- `weatherapp.py`: The main script for the application.

## Screenshots
![Weather App Screenshot](#)  
*Screenshot description here*

## Improvements and Contributions
Feel free to contribute by submitting pull requests or reporting issues. Suggestions for improving the UI or adding new features like forecasts are welcome!

## License
This project is licensed under the [MIT License](LICENSE).

