# Simple Weather App

This repository contains a simple weather application built with Django. The application allows users to search for weather information by entering the name of a location. Upon searching, the app fetches weather data from the OpenWeatherMap API and displays details such as the city name, country code, coordinates, temperature, pressure, and humidity.

## Features

- **Location Search:** Users can enter the name of a city to get the current weather information.
- **Weather Details:** Displays the city name, country code, coordinates (longitude and latitude), temperature, pressure, and humidity.

## Technologies Used

- **Backend:** Django
- **Frontend:** HTML, CSS
- **API:** OpenWeatherMap

## Configuration

1. Open the `views.py` file located in the `weatherdetector` app directory.
2. Replace the placeholder API key with your actual API key in the following line:
    ```python
    api_key = 'your_actual_api_key'  # Replace with your actual API key
    ```

## Usage

1. Run the Django development server:
    ```sh
    python manage.py runserver
    ```

2. Open your web browser and navigate to `http://127.0.0.1:8000/`.

3. Enter the name of a city in the search box and click the "Get Weather" button to fetch and display the weather information.


## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API.
- The Django community for their excellent documentation and support.
