# Weather-App---Flutter
A multi-page weather application that retrieves and displays real-time current weather data using the OpenWeatherMap API.

📱 Features
Search Weather: Search for any city worldwide

Weather Details: View comprehensive weather information

Favorites: Save and manage favorite cities

Settings: Configure temperature units (°C/°F)

Responsive UI: Clean, modern interface with weather icons

Offline Storage: Saves favorites locally using SharedPreferences

home page:
<img width="1896" height="917" alt="image" src="https://github.com/user-attachments/assets/010a621a-4bc8-4c81-9de2-e02eda74893e" />
 API Key Configuration
Where to put the API Key:
Add API Key

Get your API key from OpenWeatherMap

Open lib/core/config/api_config.dart

Replace 'YOUR_API_KEY_HERE' with your actual API key:
static const String apiKey = 'your_actual_api_key_here';

<img width="649" height="206" alt="image" src="https://github.com/user-attachments/assets/b8f3523d-5002-48c0-83cd-bdaced0d6f39" />

🔧 API Usage
The app uses OpenWeatherMap Current Weather API:

Endpoint:
text
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units={unit}
Parameters:
q: City name (e.g., "London")

appid: Your API key

units: Temperature unit ("metric" for °C, "imperial" for °F)

there are another 2 pages settings and Favorites
<img width="1904" height="347" alt="image" src="https://github.com/user-attachments/assets/95c495d3-65ea-4f55-a6d1-56b7f80a9d02" />

<img width="1909" height="449" alt="image" src="https://github.com/user-attachments/assets/a91294c6-c6b3-471c-8728-a1e7305f1f36" />

