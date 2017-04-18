# Welcome to Nemo

Nemo is a framework and set of conventions for automated testing of web and even native applications. How you use it is only limited by your imagination. A common starting point is to pair Nemo with a task runner (e.g. Grunt) and a test runner (e.g. Mocha). But if you have a different task and test runner, Nemo will work with that as well.

Get a grounding in [selenium-webdriver Promises and Control Flow](promises-and-control-flow.md)

## Meet the players

The following modules are essential for getting started with Nemo

### [generator-nemo](https://github.com/paypal/generator-nemo)
To get everything off the ground quickly, start here.

### [nemo](https://github.com/paypal/nemo)

Nemo lovingly hugs selenium-webdriver, bundles up the plugins of your choice, and gives it all back to you in a single namespace for your testing pleasure.

### [nemo-view](https://github.com/paypal/nemo-view)

Nemo view replaces nemo's built-in "view" functionality with a much cooler interface. Use it in concert with nemo-drivex and nemo-locatex.

## [Try the sample app](https://github.com/paypal/nemo-example-app)

Follow the README instructions to get the sample app installed and run Nemo tests.

## [Selenium Webdriver Docs](https://seleniumhq.github.io/selenium/docs/api/javascript/index.html)

The [selenium-webdriver](https://www.npmjs.com/package/selenium-webdriver) instance is exposed via `nemo.driver`, so it helps to know the API that you have access to.

