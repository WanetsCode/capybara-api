
# capybara-api

capybara-api is a sweet, cute, fast API to get a whole bunch of images or a random image of a capybara

## Documentation

Note: 
- Pages are cached for 7 days
- API Base URL is `https://api.capy.lol`


### Get Capybara
Get random capybara and return as an image
```
GET /v1/capybara
```

Get random capybara and return as JSON
```
GET /v1/capybara?json=true
```

### Get Capybaras
Get a bunch of capybaras
```
GET /v1/capybaras
```