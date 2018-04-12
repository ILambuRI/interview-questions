JavaScript
  ES6 additions
  Babel and translators
  Arrow/lambda functions
  Promises
  Lexical scopes
  Prototypal inheritance
js
  hoisting
  scopes
  immediate function call
  what are closures, why are they used
    to return a function which has a shared state on each call
  hoisting:
    var x = 1;

    (function(){
      alert(x);
      var x = 2;
    })()
    // https://codepen.io/neurodeep/pen/OvoyrB

factorial