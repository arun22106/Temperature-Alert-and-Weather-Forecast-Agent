# Temperature Alert and Weather Forecast Agent

This project involves the creation of two agents: a Temperature Alert Agent and a Message Printer Agent. The Temperature Alert Agent monitors temperature conditions and sends alerts to the Message Printer Agent when the temperature exceeds defined thresholds. Additionally, the project includes a weather forecast feature for a specified location.

## Table of Contents

- [Introduction](#introduction)
- [Agents](#agents)
- [Usage](#usage)
- [Weather Forecast](#weather-forecast)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Contact](#contact)

## Introduction

This project consists of three main components:

1. **Temperature Alert Agent:** Monitors the temperature at a specified location using the OpenWeatherMap API. It sends alerts to the Message Printer Agent when the temperature exceeds predefined minimum or maximum thresholds.

2. **Message Printer Agent:** Receives and prints messages and alerts sent by the Temperature Alert Agent.

3. **Weather Predictor:** Predicts weather conditions using deep learning algorithms.

## Agents

### Temperature Alert Agent

- **Name:** `alert_agent`
- **Seed:** `alert_agent_seed`
- **Endpoint:** `http://localhost:8000`
- **Port:** `8000`

### Message Printer Agent

- **Name:** `message_printer`
- **Endpoint:** `http://localhost:8001`
- **Port:** `8001`

## Usage

Run the main script:

```bash
python main.py
```

## Prerequisites

- Python 3.6 or later
- `uagents`
- `requests`
- `numpy`
- `pandas`
- `matplotlib`
- `tensorflow`

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/arun22106/Temperature-Alert-and-Weather-Forecast-Agent.git
cd Temperature-Alert-and-Weather-Forecast-Agent
```

### 2. Install Dependencies

```bash
pip install uagents requests numpy pandas matplotlib tensorflow
```

### 3. Run the Project

```bash
python main.py
```

## Weather Forecast

The project also provides weather forecasts for a specified location.

1. Run the project as described in the Usage section.
2. When prompted, enter the location for which you want a weather forecast.
3. The forecast is retrieved using the OpenWeatherMap API and saved to `prediction.txt`.

## Configuration

Configure the agents with the required settings, including location, minimum and maximum temperature thresholds, API key, and endpoint.

- **Temperature Alert Agent:** Configure the location, temperature thresholds, API key, and endpoint as required.
- **Message Printer Agent:** No additional configuration is required.
- **OpenWeatherMap API Key:** Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api) and configure it in the appropriate variable in your source code. Do not publish private API keys or credentials.

## Contact

Feel free to reach out with any feedback or suggestions.
