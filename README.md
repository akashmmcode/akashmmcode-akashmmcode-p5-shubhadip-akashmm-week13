akashmmcode-akashmmcode-p5-shubhadip-akashmm-week13

# Weather App

## How to use

  1 - Clone the repo <br>
  2 - cd into the repo akashmmcode-akashmmcode-p5-shubhadip-akashmm-week13  <br>
  3 - Run `npm install`  <br>
  4 - Run `npm start`  <br> 
  5 - Open `http://localhost:5000/` in your browser  <br>
  6 - Access the above url on your browser or on postman <br>

## Features

### Requesting weather data of a particular city

```
http://localhost:5000/weather/amsterdam
```

## Response

```json
{
    "success": true,
    "message": "Fetch done",
    "weather": "Mostly smoke today",
    "temperature": "The Temerature in delhi is 17 Degree Celsius",
    "pressure": "1016hpa",
    "humidity": "45%",
    "wind": "Speed 2.06 Deg 250"
}
```

### Detailed Forecast for the next X days

```
http://localhost:5000/weather/amsterdam/3
```

```json
{
    "success": true,
    "message": "Fetch done",
    "temp": "The temerature for the next 3 days in delhi is 19,20,19 degree Celsius",
    "pressure": [
        1015,
        1013,
        1014
    ],
    "humidity": [
        34,
        26,
        20
    ],
    "visibility": [
        10000,
        10000,
        10000
    ]
}

```

