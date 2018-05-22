# Frontend

## General

* What are progressive apps?
* CSS vs JS animation.

## JavaScript

* ES6 additions
* Babel and translators
* Arrow/lambda functions
* call() & apply() vs bind()
* Promises
* Lexical scopes
* Prototype inheritance
* How classes are defined and inherited?
* Nuances
  * Scopes
  * Immediate function call
  * What are closures, why and how are they used?
    * To return a function which has a shared state on each call (e.g., timer, counter).
  * Hoisting:
  ```
    var x = 1;

    (function(){
      alert(x);
      var x = 2;
    })()
    // https://codepen.io/neurodeep/pen/OvoyrB
  ```
  * What happens here?
  ```
  var x = 1;
  var obj = {
    x: 2,
    prop: {
        x: 3,
        getX: function() {
          return this.x;
        }
    }
  };
  console.log(obj.prop.getX());
  var test = obj.prop.getX;
  console.log(test());
  ```

## HTML

* What is the difference between HTML and HTML5?

## CSS

* Flexbox
* SASS
