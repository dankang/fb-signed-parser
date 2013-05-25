fb_signed_parser
======

facebook signed request parser for node.js

You can use this module when you want to parse requests from facebook.

## Usage

```js
var fb_signed_parser = require('fb_signed_parser');

...
var signed_request = req.param('signed_request');
var data = fb_signed_parser.parse(signed_request, FB_APP_SECRET);
console.log(data);
```