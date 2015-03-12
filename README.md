# Ember Cordova Base

Building an Ember-Cordova app? Start here. 

## Pre-req's

You will need the following things properly installed on your computer.

**New stuffs**

* [ember-cli](http://www.ember-cli.com/) 
* [cordova](https://www.npmjs.com/package/cordova)

**Stuff you may already have**

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://www.ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)


## Installation

* `git clone <repository-url>` this repository
* change into the new directory
* `npm install`
* `bower install`
* `npm install --save-dev ember-cli-cordova`
* `ember generate cordova-init com.my-app.app` (Answer `Y` to all the overwrite questions) 

## Running / Development

This repo is set up to run with live updating turned on. Edit files, save them, and the app refreshes (whether it's browser or device emulation)

* `ember serve`
* `ember cordova emulate ios` (in another terminal) 
* Visit your app at [http://localhost:4200](http://localhost:4200) or in the ios emulator and watch the app update as you save files!

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.
