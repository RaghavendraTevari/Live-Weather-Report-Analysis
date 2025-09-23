# Live-Weather-Report-Analysis
### Provides insights into weather patterns across Indian regions, including temperature, wind speed, and air quality. This project collects live daily weather data of Indian States for seven days forecast data.
## Getting the live data
## This project utilizes data from tthe Power BI for analysis and visualization of weather data current and 7 days forecast data.
### The live data is obtained from weather api website
### * The Api key is generated
### * Generated Api is then pasted in the Api Explorer
### * The data is stored in the Json format
### * This Json file weatherApi link is used in PowerBI
### * = Json.Document(Web.Contents("http://api.weatherapi.com/v1/forecast.json?key=34994baecab8405a96f154533252009&q=Ajmer&days=7&aqi=yes"))
### * = Json.Document(Web.Contents("http://api.weatherapi.com/v1/forecast.json?key=34994baecab8405a96f154533252009&q=Bangalore&days=7&aqi=yes"))
### * = Json.Document(Web.Contents("http://api.weatherapi.com/v1/forecast.json?key=34994baecab8405a96f154533252009&q=Mumbai&days=7&aqi=yes"))
### * = Json.Document(Web.Contents("http://api.weatherapi.com/v1/forecast.json?key=34994baecab8405a96f154533252009&q=Delhi&days=7&aqi=yes"))
### * = Json.Document(Web.Contents("http://api.weatherapi.com/v1/forecast.json?key=34994baecab8405a96f154533252009&q=Hyderabad&days=7&aqi=yes"))
