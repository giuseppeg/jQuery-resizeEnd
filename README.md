#jQuery resizeEnd

A resizeEnd event for jQuery.


jQuery resizeEnd defines a special event
that is fired when the JavaScript "resize" event has finished.

It also defines an alias function named after the event name
which binds an event handler to the "resizeEnd" event,
or trigger that event on an element.

## Usage

Basic usage:

```javascript
$(window).on("resizeEnd", function (event) {
  // go nuts
});
```

or use its alias function:

```javascript
$(window).resizeEnd(function (event) {
  // go nuts
});
```

## TODO
* Write tests

## Author

[@giuseppegurgone](http://twitter.com/giuseppegurgone)

## License (MIT)

Copyright (c) 2013 Giuseppe Gurgone

This work is licensed for reuse under the MIT license.
See the included [LICENSE] (LICENSE) file for details.
