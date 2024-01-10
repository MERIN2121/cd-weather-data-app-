# cd-weather-data-app-                  Weather Data Application

This Python application leverages SQLite and Open Meteo APIs to retrieve, store, and analyze weather data. The program is divided into four phases, each addressing different aspects of functionality, database interaction, and data visualization.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Database Schema](#database-schema)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

This application aims to provide weather-related functionalities, including database querying, chart generation, data retrieval from Open Meteo APIs, and more. The project is structured into phases, each building upon the previous one to create a comprehensive weather data solution.

## Features

- **Phase 1:** Database querying and basic display of weather data.
- **Phase 2:** Data visualization using Matplotlib, including bar charts and scatter plots.
- **Phase 3:** User interface for querying, chart generation, and database deletion.
- **Phase 4:** Integration with Open Meteo APIs to retrieve and store real-time weather data.

## Requirements

- Python 3.x
- SQLite
- Matplotlib
- Requests

## Installation

1. Clone the repository: `git clone https://github.com/your-username/weather-data-app.git`
2. Navigate to the project directory: `cd weather-data-app`
3. Install dependencies: `pip install -r requirements.txt`

## Usage

1. Execute `python phase1.py` to run Phase 1 of the application.
2. Follow a similar pattern for Phases 2, 3, and 4.

## Database Schema

The SQLite database consists of three tables: `countries`, `cities`, and `daily_weather_entries`. Refer to the [database schema](#link-to-schema) for more details.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

