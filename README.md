# Live-Weather-Report-Analysis
## Getting the live data
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
