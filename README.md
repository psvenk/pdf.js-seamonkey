# PDF.js

This is a fork of PDF.js with support for SeaMonkey 2.49.x.

For more information about pdf.js, see: https://github.com/mozilla/pdf.js

## Getting the Code

To get a local copy of the current code, clone it using git:

    $ git clone git://github.com/IsaacSchemm/pdf.js-seamonkey.git
    $ cd pdf.js

Next, install Node.js via the [official package](http://nodejs.org) or via
[nvm](https://github.com/creationix/nvm). You need to install the gulp package
globally (see also [gulp's getting started](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md#getting-started)):

    $ npm install -g gulp-cli

If everything worked out, install all dependencies for PDF.js:

    $ npm install

## Building PDF.js

To build the SeaMonkey extension, run:

    $ gulp seamonkey
