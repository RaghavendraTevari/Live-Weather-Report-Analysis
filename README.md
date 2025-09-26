# Live-Weather-Report-Analysis
### The process of building a Real-Time weather report from using data WeatherAPI.
### Provides insights into weather patterns across Indian regions, including temperature, wind speed, and air quality. This project collects live daily weather data of Indian States for seven days forecast data.
## Getting the live data
## This project utilizes data from the Power BI for analysis and visualization of weather data current and 7 days forecast data.
### The live data is obtained from weather api website
### * The Api key is generated
### * Generated Api is then pasted in the Api Explorer
### * The data is stored in the Json format
### * This Json file weatherApi link is used in PowerBI
`= Json.Document(Web.Contents("https://api.weatherapi.com/v1/forecast.json?key=xy994baecab8405a96f1545xx252009&q=Ajmer&days=7&aqi=yes"))` 
`= Json.Document(Web.Contents("https://api.weatherapi.com/v1/forecast.json?key=APIKEY=Bangalore&days=7&aqi=yes"))`
`= Json.Document(Web.Contents("https://api.weatherapi.com/v1/forecast.json?key=APIKEY=Mumbai&days=7&aqi=yes"))`
`= Json.Document(Web.Contents("https://api.weatherapi.com/v1/forecast.json?key=APIKEY=Delhi&days=7&aqi=yes"))`
`= Json.Document(Web.Contents("https://api.weatherapi.com/v1/forecast.json?key=APIKEY=Hyderabad&days=7&aqi=yes"))`
## WeatherAPI
### It is a simple and powerful service the data is stored in JSON format which is helpful for PowerBI. It produces live, historical and forecast Weather data.
# Step 1: Get the API Keyfrom website
### Sign up in website WeatherAPI.com, then copy your API key.
### Use it for API calls which city you want.
# Step 2: Building of API url in PowerBI
## = Json.Document(Web.Contents("https://api.weatherapi.com/v1/forecast.json?key=Ajmer&days=7&aqi=yes"))
### For forecast of 7 days with AQI(Air Quality Index) along with the current data.
# Step 3: Connecting PowerBi to weatherAPI
### 1. Install and open PowerBI Desktop app.
### 2. Click on `Get Data` then click on `Web`.
### 3. Enter your URL.
### 4. Click `OK`.
