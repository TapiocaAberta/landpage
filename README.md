# Cultural Ubuntu

SJC Digital Portfólio's

# How to Build

This project use [yeoman](http://yeoman.io/learning/) suite, that uses  three core tools for improving productivity and satisfaction when building a web app. These tools are:

- [yo](http://yeoman.io/learning/) - the scaffolding tool from Yeoman
- [Bower](http://bower.io/) and [NPM](https://www.npmjs.com/) as a package manager.
- [Gulp](http://gulpjs.com/) as a build tool.

# Pre requisites

That tools requires [Nodejs](http://nodejs.org) version > 0.10.x

# Getting start

Go to the source folder:

	cd landpage

then, install the dependencies:

	npm install -g yo bower grunt-cli gulp && npm install && bower install

# Useful commands:

Preview an app you have generated (with Livereload):

	$ gulp serve

Build an optimized, production-ready version of your app:

	$ gulp

## Deploy

Deploy the production version of the app to a remote server:

	$ gulp && gulp deploy


# License

The MIT License (MIT)

Copyright (c) 2015 cultural-ubuntu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

