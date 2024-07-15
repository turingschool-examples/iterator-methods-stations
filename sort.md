# sort()

## Example 1:
Given an array of countries, write a function that sorts the countries alphabetically by countryCode. 

Ex:

```javascript
var countries = [
  {
      "countryCode": "AS",
      "countryName": "American Samoa",
      "population": "57881",
      "capital": "Pago Pago",
      "continentName": "Oceania"
  },
  {
    "countryCode": "AI",
    "countryName": "Anguilla",
    "population": "13254",
    "capital": "The Valley",
    "continentName": "North America"
  },
  {
      "countryCode": "AD",
      "countryName": "Andorra",
      "population": "84000",
      "capital": "Andorra la Vella",
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
      "countryCode": "SX",
      "countryName": "Sint Maarten",
      "population": "37429",
      "capital": "Philipsburg",
      "continentName": "North America"
  },
];

sortByCountryCode(countries) // => [
//   {
//       "countryCode": "AD",
//       "countryName": "Andorra",
//       "population": "84000",
//       "capital": "Andorra la Vella",
//       "continentName": "Europe"
//   },
//     {
//     "countryCode": "AI",
//     "countryName": "Anguilla",
//     "population": "13254",
//     "capital": "The Valley",
//     "continentName": "North America"
//   },
//   {
//       "countryCode": "AO",
//       "countryName": "Angola",
//       "population": "13068161",
//       "capital": "Luanda",
//       "continentName": "Africa"
//   },
//    {
//       "countryCode": "AS",
//       "countryName": "American Samoa",
//       "population": "57881",
//       "capital": "Pago Pago",
//       "continentName": "Oceania"
//   },
//   {
//       "countryCode": "SX",
//       "countryName": "Sint Maarten",
//       "population": "37429",
//       "capital": "Philipsburg",
//       "continentName": "North America"
//   },
// ];

```
## Example 2:

Given the previous array of countries, write a function to sort the countries by population, highest to lowest.

```js
sortByHighestPopulation(countries) // => [
//   {
//     countryCode: 'AO',
//     countryName: 'Angola',
//     population: '13068161',
//     capital: 'Luanda',
//     continentName: 'Africa'
//   },
//   {
//     countryCode: 'AD',
//     countryName: 'Andorra',
//     population: '84000',
//     capital: 'Andorra la Vella',
//     continentName: 'Europe'
//   },
//   {
//     countryCode: 'AS',
//     countryName: 'American Samoa',
//     population: '57881',
//     capital: 'Pago Pago',
//     continentName: 'Oceania'
//   },
//   {
//     countryCode: 'SX',
//     countryName: 'Sint Maarten',
//     population: '37429',
//     capital: 'Philipsburg',
//     continentName: 'North America'
//   },
//   {
//     countryCode: 'AI',
//     countryName: 'Anguilla',
//     population: '13254',
//     capital: 'The Valley',
//     continentName: 'North America'
//   }
// ]
```
