# country-rus-to-eng
Minor utility library (browser-side and server-side) Translate countries RUS to ENG

Introduces new global object: Country.

Mapping was taken from Wikipedia (http://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements)

Library can be used both in browser or on server as NPM module.

  npm install country-rus-to-eng
How to use:

`var country = require('country');
console.log(country['Украина']);//should print Ukraine`
