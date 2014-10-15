## A server part code generator from a Swagger 2.0 Specification file

swagger-server-gen
==================

This is a server part code generator for [swagger-code-gen](https://github.com/tmalbonph/swagger-code-gen) project.

### What is swagger-server-gen?

This software is a [NodeJS](http://nodejs.org) application.

It is intended for generating server side [NodeJS](http://nodejs.org) codes from a Swagger Specification file in [version 2.0](https://github.com/reverb/swagger-spec/blob/master/versions/2.0.md) document format.

It is design to be run with [npm](https://www.npmjs.org/package/npm) using `npm run-script {XXXX};` where XXXX is one of demo, generate.

### How to install

* install [grunt-cli](https://github.com/gruntjs/grunt)

 `npm install -g grunt-cli`

* install its dependencies

 `npm install`

### How to create the provided sample demo

* create demo with npm

 `npm demo`

* create demo with node

 `node demo.js`

### How to generate server code from your swagger 2.0 file

* generate with npm

 `npm run-script server -s PATH/TO/YOUR/SWAGGER/FILE -d FOLDER/TO/SAVE/GENERATED/CODES`

* generate with node

 `node server.js -s PATH/TO/YOUR/SWAGGER/FILE -d FOLDER/TO/SAVE/GENERATED/CODES`

### Sample codes

* TODO : soon will add code snippets here

### License

[MIT](https://github.com/tmalbonph/swagger-server-gen/blob/master/LICENSE)

The MIT License (MIT)

Copyright (c) 2014 tmalbonph <tmalbonph@yahoo.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

### Current status

The current version of this software is under development and working in local repository. Will soon publish beta version.

