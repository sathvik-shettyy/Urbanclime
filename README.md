```markdown
# Simple Weather App

Author: Sathvik Shetty

## Description
This is a simple weather app written in Python that allows users to retrieve current weather information for a specified city using the OpenWeatherMap API.

## Features
- Displays current temperature in Celsius.
- Provides a brief weather description for the specified city.
- Shows humidity percentage.

## Getting Started

### Prerequisites
- Python 3.x
- An OpenWeatherMap API key. Get yours [here](https://openweathermap.org/api).

### Installation
1. Clone the repository: `git clone https://github.com/sathvikshetty/Urbanclime.git`
2. Navigate to the project directory: `cd weather-app`
3. Install dependencies: `pip install -r requirements.txt`

### Usage
1. Obtain your OpenWeatherMap API key.
2. Open `config.py` and replace `'YOUR_API_KEY'` with your actual API key.
3. Run the app: `python weather_app.py`
4. Enter the city name when prompted.

## Example
```bash
Enter the city name: New York
```
Output:
```
Weather in New York:
Temperature: 20.5°C
Description: Clear sky
Humidity: 68%
```

## Contributing
If you'd like to contribute to this project, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
