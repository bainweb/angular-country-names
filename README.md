# angular-country-names
Angular module which registers an array of country names as an angular constant.

# Usage

```
// Include countryNames module in your module
angular.module('myModule', ['countryNames']);

// Inject countryNames constant into your controller
angular.module('myModule').controller('myCountroller', Controller);

Controller.$inject = ['countryNames'];

function Controller(countryNames) {
  console.log(countryNames);
}
```
