# Weather App

A simple weather app built with Flask that fetches weather data from the OpenWeather API. Users can input a city, state, and country to get real-time weather information including the current temperature, weather condition, and an icon representing the weather.

## Features

- Fetches real-time weather information based on city, state, and country input.
- Displays the weather condition (main and description) and temperature in Celsius.
- Shows an icon corresponding to the current weather condition.

## Technologies Used

- **Flask**: Web framework for building the app.
- **OpenWeather API**: To fetch weather data.
- **HTML/CSS**: For structuring and styling the web page.
- **Python**: Backend logic and API integration.
- **dotenv**: To securely load API keys.

## Installation

### Prerequisites

- Python 3.x
- pip (Python package manager)

### Steps to Install

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    ```

2. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up environment variables**:
    - Create a `.env` file in the root directory of the project.
    - Add your OpenWeather API key:
      ```
      API_KEY=your_api_key_here
      ```

4. **Run the Flask app**:
    ```bash
    python app.py
    ```

5. Open your browser and go to `http://127.0.0.1:5000/` to view the app.

## Usage

1. **Enter City, State, and Country**: On the homepage, you'll see input fields for city, state, and country.
2. **View Weather Information**: After clicking "See Weather", the app will display:
    - **Main**: Type of weather (e.g., Clear, Cloudy).
    - **Description**: More detailed weather description (e.g., Clear sky).
    - **Temperature**: Current temperature in Celsius.
    - **Icon**: An image representing the weather condition.

## Example

When you enter "Kolkata", "WB", "India" into the input fields, the app will fetch and display the weather information for that location.

## Project Structure

weather-app/ │ ├── app.py # Main Flask app file ├── weather.py # Weather data fetching logic ├── .env # Environment file for API keys ├── templates/ │ └── index.html # HTML template for the web page ├── static/ │ └── style.css # CSS styling for the app └── requirements.txt # List of Python dependencies


## Contributing

Feel free to fork the repository, create a branch, and submit a pull request. Any contributions are welcome!



