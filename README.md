# WeatherDataApi

This Flask app allows you to query of temperature information for listed stations in Europe with 
multiple endpoints.

```
    URL Format: http://127.0.0.1:5001/api/v1/station/date
    For one station for one date: http://127.0.0.1:5001/api/v1/10/1994-04-17
    For one station for all dates: http://127.0.0.1:5001/api/v1/10
    For one station for one year: http://127.0.0.1:5001/api/v1/yearly/10/year
```