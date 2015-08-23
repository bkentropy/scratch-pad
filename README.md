# scratch-pad
A blank node app for learning JavaScript


## app.js

The app.js file is an executable JavaScript file, a template for you to write and test JavaScript in the node.js environment.

You can execute it by opening it and clicking the green "Run" button - this will allow you to use breakpoints on the file and debug and step-thru your code, which is very handy for understanding complex algothrithms, especially higher order functions.

You can also execute this file from the commandline: if you're in the same directory as the app.js file, simply run the command `./app.js`.

You can duplicate this file and rename it to represent whatever other studies you're undertaking, ie, strings.js, or, recursion.js, or, functions.js, etc.

## lodown

1. Implement the lodown.js as a `node.js` module, duplicating the API of the wonderful lodash library (see <a href="lodash.com" target="_blank">lodash.com</a>).
2. Test your higher order functional programming you've implemented in `lodown.js` by implementing the `customers.js` file, which should load both the `lodash` module and the `customers.json` file, located in the directory, `lodown/data/customers.json`.  The code you write in your `customers.js` app should load the `customers.json`, then make use of your `lodash` module's API, testing your functional methods, like each, filter, map, reduce, pluck, where, every, find, etc.  If you do not know how these functions operate, see the lodash.com docs.  Try to decipher things like, how many customer's names begin with some letter, how many customer's friend's names begin with some letter, how many customers are friends, or, how many customers are friends in common.
3. If you do not know how to create a node module, Google it!
4. If you do not know how to load a json file in node, Google it!