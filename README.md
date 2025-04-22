# Weather Agent with Amazon Bedrock

This project implements a conversational AI agent using Amazon Bedrock's Llama model that can fetch real-time weather information through the OpenWeather API.

## Features

- Conversational AI agent powered by Amazon Bedrock's Llama model
- Real-time weather data fetching using OpenWeather API
- Support for current weather conditions including:
  - Temperature
  - Weather conditions
  - Humidity
  - Wind speed
  - Sunrise/sunset times

## Prerequisites

- Python 3.11+
- AWS Account with Bedrock access
- OpenWeather API key

## Setup

1. Install required dependencies:

```sh
pip install boto3 requests python-dotenv

Create a .env file with your credentials:

AWS_ACCESS_KEY_ID=your_aws_access_key
AWS_SECRET_ACCESS_KEY=your_aws_secret_key
OPENWEATHER_API_KEY=your_openweather_api_key