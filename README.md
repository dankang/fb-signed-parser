fb_signed_parser
======

facebook signed request parser for node.js

## Usage

  var fb_signed_parser = require('fb_signed_parser');

  var data = fb_signed_parser.parse(signed_request, FB_APP_SECRET);
  console.log(data);
