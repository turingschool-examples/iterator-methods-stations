# .reduce

Given an array of numbers, write a function that returns the product of all the numbers.

```javascript
var numbers = [1,2,5,7]

getProduct(numbers) // => 70

```

Given a list of countries, write a function that returns a new object where the keys are country names and their values are an object containing the rest of the country's data.

```js
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
    "population": "2986952",
    "capital": "Tirana",
    "continentName": "Europe"
  },
  {
    "countryCode": "DZ",
    "countryName": "Algeria",
    "population": "34586184",
    "capital": "Algiers",
    "continentName": "Africa"
  },
]

organizeByCountry(countries)
/*
output:
{
  Afghanistan: {
    "countryCode": "AF",
    "population": "29121286",
    "capital": "Kabul",
    "continentName": "Asia"
  },
  Albania: {
    "countryCode": "AL",
    "population": "2986952",
    "capital": "Tirana",
    "continentName": "Europe"
  },
  Algeria: {
    "countryCode": "DZ",
    "population": "34586184",
    "capital": "Algiers",
    "continentName": "Africa"
  },
}
*/
```
