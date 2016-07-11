#ISO_3166-2 World Regions
This file pretends to merge data from several data sources (openweathermap, wikipedia, etc) to centralize all country-wide locations and miscellaneous data in one file.

The data structure looks like this:
```
"Country_code" (ISO_3166-1) : {
  "regions" : [
      {
        "code" (ISO_3166-2) : String,
        "name"      : String,
        "latitude"  : Float,
        "longitude" : Float,
        "timezone"  : String,
        "openweathermap_city_id"  : Integer,
      }
  ],
  "currency" (ISO_4217): String,
  "name": String,
}
```

