# chia-mocha-node-test-for-coffee-browser

This sample project uses Chia and Mocha to provide unit test capabilities to be handled by node.js. Code is written on Coffeescript, ready to be used on browser without further steps and uses pseudo namespaces to keep more organized.

To see if the project code works, just load index.dev.html on Firefox or run it trough a web-server if using Chrome.
To run the tests:
    .1 please refer to project/build.bat to install dependencies with node.js
    .2 run the tests from project root using the following command:
        mocha --compilers coffee:coffee-script/register --recursive
