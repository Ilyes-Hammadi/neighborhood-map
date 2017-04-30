# Neighborhood Map
Front-end Web Developer Nanodegree project
<br>
![](https://github.com/Ilyes-Hammadi/neighborhood-map/blob/master/docs/demo.gif)

## Run the project
### Get the code localy
```shell
$ git clone https://github.com/Ilyes-Hammadi/neighborhood-map.git
$ cd neighborhood-map
$ npm install
```

### Setup keys
Get your foursquare api key [here](https://developer.foursquare.com/), after you get your API keys, put them in the `js/keys.js` file.
```javascript
const CLIENT_ID = "CLIENT_ID"
const CLIENT_SECRET = "CLIENT_SECRET"
```

Set your Google Maps API key in the `js/keys.js` file, you can get an API key [here](https://developers.google.com/maps/documentation/javascript/get-api-key)
```javascript
const GOOGLE_MAPS_API = 'GOOGLE_MAPS_API';
```

### Run the devlopement server
The server will run on `localhost:8000`
```python
$ python -m SimpleHTTPServer
```

## License
[MIT](https://github.com/Ilyes-Hammadi/neighborhood-map/blob/master/LICENSE)
