# .filter

1. What does `.filter` do?
2. Is the original array modified?
3. How many arguments does `.filter` take?
4. How many arguments does the _callback function_ take?
5. Which arguments are required (for both the method and its callback)?
6. Does the callback need a return value? If so, what needs to be returned?


## Example 1:

Given an array of countries, write a function that returns an array of all Asian countries.

Ex:

```javascript
var countries = [
  {
      "countryCode": "AF",
      "countryName": "Afghanistan",
      "population": "29121286",
      "capital": "Kabul",
      "continentName": "Asia"
  },
  {
      "countryCode": "AL",
      "countryName": "Albania",
      "population": "29869520",
      "capital": "Tirana",
      "continentName": "Europe"
  },
  {
      "countryCode": "AO",
      "countryName": "Angola",
      "population": "13068161",
      "capital": "Luanda",
      "continentName": "Africa"
  },
  {
      "countryCode": "AI",
      "countryName": "Anguilla",
      "population": "13254",
      "capital": "The Valley",
      "continentName": "North America"
  },
  {
      "countryCode": "AM",
      "countryName": "Armenia",
      "population": "29680000",
      "capital": "Yerevan",
      "continentName": "Asia"
  },
]

filterAsianCountries(countries)
/*
returns:
[
{
    "countryCode": "AF",
    "countryName": "Afghanistan",
    "population": "29121286",
    "capital": "Kabul",
    "continentName": "Asia"
},
{
    "countryCode": "AM",
    "countryName": "Armenia",
    "population": "2968000",
    "capital": "Yerevan",
    "continentName": "Asia"
},
]
*/
```

## Example 2:

Given the same list of countries, find all countries with a population greater than 15,000,000.

```js
filterBigCountries(countries)
/*
returns:
[
  {
      "countryCode": "AF",
      "countryName": "Afghanistan",
      "population": "29121286",
      "capital": "Kabul",
      "continentName": "Asia"
  },
  {
      "countryCode": "AL",
      "countryName": "Albania",
      "population": "29869520",
      "capital": "Tirana",
      "continentName": "Europe"
  },
  {
      "countryCode": "AM",
      "countryName": "Armenia",
      "population": "29680000",
      "capital": "Yerevan",
      "continentName": "Asia"
  },
]
*/
```
