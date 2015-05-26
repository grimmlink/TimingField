TimingField
=================

A jquery plugin to transform a timestamp field into an hours/minutes/seconds selector.

Requirements
------------

 * jQuery
 * Twitter Bootstrap

Installation
------------

Installation with composer :

```json
    ...
    "require": {
        ...
        "grimmlink/timingfield": "1.0",
        ...
    },
    ...
```

Configuration
-------------

As of now, the only configuration available is the max hour value.

```javascript
$.fn.timingfield.defaults = {
    maxHour: 23
};
```

Usage
-----

```javascript
...
$('.timestamp').timingfield();
...
```
