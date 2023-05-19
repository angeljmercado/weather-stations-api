# weather-stations-api
The Weather Stations API is a simple API that allows you to query information about the temperature for specific dates or years. It provides a straightforward way to retrieve weather data based on station IDs and dates. 
## Examples of Data Querying
### URL Format: 
`http://127.0.0.1:5000/api/v1/[station]/[date]`  

### To retrieve a specific record for a particular station and date:
`http://127.0.0.1:5000/api/v1/20/19931025`  

### To retrieve all records for a specific year in a particular station:
`http://127.0.0.1:5000/api/v1/yearly/10/[1990]`  
