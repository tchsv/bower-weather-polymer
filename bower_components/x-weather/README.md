x-weather
=========

A Polymer element for accessing OpenWeatherMap current API

Install
-------

With Bower:
```bash
$ bower install --save x-weather
```

Usage
-----

1. Import the element
```html
<link rel="import" href="src/x-instagram.html">
```

2. Use it as follows
```html
<x-weather city="London"></x-weather>
```
or
```html
<x-weather city="London" units="imperial"></x-weather>
```
or
```html
<x-weather city="Birmingham" country="US"></x-weather> <!-- Not Bham UK!! -->
```
or
```html
<x-weather idc="2172797"></x-weather>
```

Attributes
----------
Attribute  | Default             | Description
---        | ---                 | ---
`idc`      | `undefined`         | The city ID (mandatory - without city)
`city`     | `London`            | The name of the city (mandatory - without idc)
`country`  | `undefined`         | The country code (optional - e.g. `GB`)
`units`    | `undefined`         | The unit system used (optional, default is internal, choices are 'metric' and 'imperial'