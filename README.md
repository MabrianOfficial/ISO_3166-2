#ISO_3166-2 World Regions
This file pretends to merge data from several data source (pycountry, wikipedia, etc) to centralize all country-wide location and miscellaneous data in one file.

Data structure is like this:
Country_code (ISO_3166-1) : {
  'regions' : [
      {
        code (ISO_3166-2) : String,
        code (ISO_3166-2) : String,
      }
  ]
}
