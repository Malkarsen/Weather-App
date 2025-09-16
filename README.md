# Weather App

A simple weather application that fetches live weather data from the [OpenWeather API](https://openweathermap.org/) based on the city entered by the user.  
It also allows saving weather cards for quick access later.

## Features

- Search weather by city name.
- Displays weather data (temperature, conditions, and icon).
- Shows a loading indicator while fetching data.
- Handles errors (e.g., city not found, empty input).
- Save weather cards with a **Save** button.
- View saved cards listed below the search area.
- Delete a single saved card or remove **all cards** at once.
- Clean and responsive UI.
- Weather icons are loaded dynamically from the OpenWeather API.

## Technologies Used

- HTML5
- CSS3 (Flexbox)
- JavaScript (ES6+)
- [OpenWeather API](https://openweathermap.org/) for weather data

## How to Use

1. Enter the name of a city in the input field.
2. Click the **Search** button.
3. While waiting for a response, the button will be disabled and a loading message will appear.
4. If successful, the weather data and icon will be displayed in a card.
5. Click **Save** to add the card to your saved list.
6. Manage saved cards:
   - Use the **Delete** button on a card to remove it individually.
   - Use the **Delete all** button to clear all saved cards.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Malkarsen/weather-app.git
   ```

2. Open `index.html` in your browser.  
⚠️**Note**: You will need your own API key from [OpenWeather API](https://openweathermap.org/).
Replace `YOUR_API_KEY` in the `index.js` file with your actual key:
```js
const API_key = "YOUR_API_KEY";
```

## Folder Structure

```
├── index.html         # Main HTML file
├── styles.css         # Stylesheet
├── index.js           # JavaScript logic
└── assets/            # Images and icons
```

## License

This project is licensed under the MIT License.
