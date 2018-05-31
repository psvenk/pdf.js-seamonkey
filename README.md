# PDF.js [![Build Status](https://travis-ci.org/mozilla/pdf.js.svg?branch=master)](https://travis-ci.org/mozilla/pdf.js)

This is a fork of PDF.js which works with SeaMonkey 2.49.x and Firefox 52 ESR.
It probably won't work with later versions of SeaMonkey or Firefox, and I don't
currently plan on supporting them in this fork.

For more information about pdf.js, see: https://github.com/mozilla/pdf.js

Until pdf.js 2.0 is released, all releases posted here will be based on pre-release versions of pdf.js.

## Getting the Code

To get a local copy of the current code, clone it using git:

    $ git clone git://github.com/IsaacSchemm/pdf.js-seamonkey.git
    $ cd pdf.js

Next, install Node.js via the [official package](https://nodejs.org) or via
[nvm](https://github.com/creationix/nvm). You need to install the gulp package
globally (see also [gulp's getting started](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md#getting-started)):

    $ npm install -g gulp-cli

If everything worked out, install all dependencies for PDF.js:

    $ npm install

## Building PDF.js

To build the SeaMonkey extension, run:

    $ gulp seamonkey

## Installing

You can get the latest release of this fork from the
[releases page on GitHub](https://github.com/IsaacSchemm/pdf.js-seamonkey/releases).
