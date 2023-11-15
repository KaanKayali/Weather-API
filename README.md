# Weather-API
## Desciption
Different Images based on the weather. API-key from the open-meteo.com site.

## How it works
It requests in the HTTP-aysnc event of an object a json file from the free open source weather api.
Link: https://open-meteo.com/

This json file gets stored and decoded in the object. Based on the latitude the picture on the application screen changes.
The data changes every hour.

```
var url = "https://api.open-meteo.com/v1/forecast?latitude=47.37&longitude=8.55";
var _data = json_parse(async_load[? "result"]);
latitude = _data.latitude;
```
