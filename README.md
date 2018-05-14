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
        "grimmlink/timingfield": "1.1",
        ...
    },
    ...
```

Configuration
-------------

This is the current available configuration :

```javascript
$.fn.timingfield.defaults = {
    maxHour:        23
    width:          263,
    hoursText:      'H',
    minutesText:    'M',
    secondsText:    'S',
    hasSeconds:     true
};
```

Usage
-----

```javascript
...
$('.timestamp').timingfield();
...
```
