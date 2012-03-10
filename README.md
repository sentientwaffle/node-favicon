# Favicon
A Node.js module for finding the URL of a web site's
[favicon](http://en.wikipedia.org/wiki/Favicon).

# Installation

    $ npm install favicon

# Usage

In this example, `favicon_url` is a `String` if an icon is found, or
`null` otherwise.

    var favicon = require('favicon');
    
    favicon("http://nodejs.org/", function(err, favicon_url) {
      // ...
    });

# License

See LICENSE.
