# Space Weather Workshop 2026
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abinashour/Space_weather_Workshop_2026/blob/main/Space_Weather_Monitoring_10_6_26.ipynb)

Participants will monitor space weather using solar image, videos, X-ray flux data and Kp index data to check the Sun activity and current space weather conditions, then classify the day as quiet, active, or stormy.

## Dataset Description
 
The dataset folder is divided into two different dates. Each date contains space-weather-related data that will be used in this practical activity.

The provided data include:

1. Solar images and videos from:
   - SDO/HMI continuum
   - SDO/AIA 193 Å
   - SOHO/LASCO C3

2. GOES X-ray flux data in W/m²

3. Kp index data

## How to Use Workshop Content Locally 

Open Command Prompt or Anaconda Prompt and run:

```bash
cd "C:\Writeyour Path" #Example cd C:\Users\aaa\Desktop
git clone https://github.com/abinashour/Space_weather_Workshop_2026.git
cd Space_weather_Workshop_2026
jupyter notebook "Space_Weather_Monitoring_10_6_26.ipynb"
