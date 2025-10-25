# live-weather-dashboard

## 🧭 Getting Started  
### Prerequisites  
- Modern web browser (Chrome, Firefox, Edge)  
- (Optional) Local web server if you want to run with live reload  
### Installation & Usage  
1. Clone or download this repository.  
2. Open `index.html` in your browser.  
3. In `dashboard.js`, ensure you have replaced the placeholder API key with a valid key from the weather service provider.  
4. In the search input (`id="search-city"`), type a city name (e.g., “Madurai”) and click the search button.  
5. View the current weather and the 5-day forecast.  
6. Use the **Clear history** button to reset the search list.  

## 🔍 Code Highlights  
- The script checks the current hour and adds a CSS class (`morning`, `evening`, `night`) to the `<body>` to change the background theme dynamically.  
- Using Bootstrap’s grid system to layout the search panel and weather display side by side.  
- Use of IDs such as `#temperature`, `#humidity`, `#wind-speed`, `#uv-index`, and forecast IDs (`#fDate0`…`#fDate4`, `#fTemp0`… etc) to inject data into the DOM.  
- Use of `localStorage` (or similar) to store and load search history, and dynamically create list items under the search history `<ul>`.

## ✅ Good Practices & Tips  
- Validate user input (e.g., empty city name, invalid characters).  
- Handle API errors (e.g., city not found, request limit reached).  
- Normalize city names (e.g., trim whitespace, convert to title case) for consistent history entries.  
- Consider adding visual icons for weather (e.g., sun, rain) for better UX.  
- Add comments in `dashboard.js` to explain key sections (fetching data, updating UI, storing history).  
- Use semantic HTML tags (`<header>`, `<main>`, etc) and ensure accessibility (alt text for images/icons).  

## 🧪 Future Enhancements  
- Add option to switch between Celsius/Fahrenheit.  
- Allow selecting units (metric/imperial).  
- Add caching of weather results to reduce API calls.  
- Display weather icons (from API) instead of text.  
- Improve UI/UX layout for mobile screens.  
- Add animations for forecast cards (optional).  
- Add “last updated time” display.  

## 📄 License  
This project is open-source and available under the MIT License.  
(Or specify whichever license you choose.)

## 🙏 Acknowledgements  
- Weather data provided by [OpenWeatherMap](https://openweathermap.org) (or whichever API you use)  
- Background images from Unsplash  
- Bootstrap & Font Awesome for styling and icons  
- Inspiration from typical “weather dashboard” tutorials and projects  
  

