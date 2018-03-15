# PDF.js

This is a fork of the last known version of PDF.js with support for SeaMonkey 2.49.x.

For more information about pdf.js, see: https://github.com/mozilla/pdf.js

## Getting the Code

To get a local copy of the current code, clone it using git:

    $ git clone git://github.com/IsaacSchemm/seamonkey-pdf.js.git
    $ cd pdf.js

Next, install Node.js via the [official package](http://nodejs.org) or via
[nvm](https://github.com/creationix/nvm). You need to install the gulp package
globally (see also [gulp's getting started](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md#getting-started)):

    $ npm install -g gulp-cli

If everything worked out, install all dependencies for PDF.js:

    $ npm install

Finally, you need to start a local web server as some browsers do not allow opening
PDF files using a `file://` URL. Run:

    $ gulp server

and then you can open:

+ http://localhost:8888/web/viewer.html

It is also possible to view all test PDF files on the right side by opening:

+ http://localhost:8888/test/pdfs/?frame

## Building PDF.js

To build the Firefox / SeaMonkey extension, run:

    $ gulp firefox

You will want to make sure that "zip" and "git" are in your PATH. On Windows,
this is not necessarily the case by default. You can set the PATH in the
command prompt with a command like:

    SET PATH=C:\folder1;C:\folder2;%PATH%
