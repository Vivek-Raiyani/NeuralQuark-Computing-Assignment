# NeuralQuark-Computing-Assignment
The web application must be able to fetch the user's current location to determine the nearest coast.

### Installation
**Clone the repository**
   ```bash
   git clone https://github.com/Vivek-Raiyani/assignment-NeuralQuark-Computing.git
   cd assignment-NeuralQuark-Computing
   ```
** Sample API Keys **
```
storm_glass = 7049a32a-a130-11f0-9727-0242ac130006-7049a3d4-a130-11f0-9727-0242ac130006 
storm_glass = 68536d30-a267-11f0-b808-0242ac130006-68536d8a-a267-11f0-b808-0242ac130006
```
If you encounter rate limit in this create new api key 

**Add your API key (Optional)**
   - Sign up for a free API key at [StormGlass.io](https://stormglass.io/)
   - Open `assignment.html` in a text editor
   - Find the line `const apiKey = "";`
   - Add your API key: `const apiKey = "your-api-key-here";`

## 🔑 API Configuration

### StormGlass API

This application uses the [StormGlass API](https://stormglass.io/) for tide data.

**Free Tier Includes:**
- 10 requests per day
- Tide predictions
- Access to global tidal stations

**Getting Your API Key:**
1. Visit [StormGlass.io](https://stormglass.io/)
2. Sign up for a free account
3. Navigate to your dashboard
4. Copy your API key
5. Paste it in the `apiKey` variable in the HTML file

**Note:** If you don't add an API key, the app will automatically use dummy data for demonstration purposes.


## 📚 How It Works

1. **Location Detection** - The app requests your device's location using the Geolocation API
2. **Tide Data Fetching** - Queries the StormGlass API for the nearest tidal station and upcoming tide events
3. **Real-time Updates** - Displays countdown timer that updates every second
4. **Activity Recommendations** - Suggests activities based on whether it's high or low tide
5. **Map Visualization** - Shows your location and the tidal station using Leaflet.js

## 🙏 Acknowledgments

- [StormGlass.io](https://stormglass.io/) for providing tide data API
- [Leaflet.js](https://leafletjs.com/) for the interactive map library
- [OpenStreetMap](https://www.openstreetmap.org/) for map tiles

---
