# Firemap

## Wildfire Map 08/31/2017

_Eipcodus-JavaScript Group Project By Nicole Freed, Dylan Lewis, Jacob Ruleaux, Nathan Stewart_

## Description

The application displays current wild fire locations on a map. Additional fire data is displayed by clicking on the icons.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0.

## Prerequisites

You will need the following properly installed on your computer.

* [Node.js](https://nodejs.org/) (with NPM)
* [Angular2](https://angular.io/)
* [Angular CLI](https://github.com/angular/angular-cli)
* [TypeScript](http://www.typescriptlang.org/index.html)
* [Deepstream Server](https://deepstreamhub.com/open-source/)

* Once installed, you will need to install bower globally:
* `$ npm install bower -g`

## Configuration/Dependencies

* angular-cli
* bower
* bootstrap

The app will use angular-cli and assets and dependencies packaged with it.

## Setup/Installation

* `$ git clone <repository-url>` this repository
* `$ cd <repository-name>`
* `$ npm install`
* `$ bower install`

Notice: The d3 branch is vastly different than the master. If you wish to view the d3 branch, it will need to be cloned separately.

`$ git clone -b <branch-name> --single-branch <repository-url>`

#### API Keys

* Get an API key from [Google Maps](https://developers.google.com/maps/documentation/javascript/get-api-key).
* Create a file in your project app  folder called api-keys.ts.
* Within the api-keys.ts file, type "export var masterGoogleMapConfig = { apiKey: "YOUR-API-KEY" }". Be sure to add this file to .gitignore.

## Deepstream server

Run `deepstream start` in a new command line tab.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


### License

MIT License

Copyright &copy; 2017 Nicole Freed, Dylan Lewis, Jacob Ruleaux, Nathan Stewart

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
