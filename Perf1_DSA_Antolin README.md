1.Differentiation of let, const, and var in JavaScript
var, let, and const are used to store values in JavaScript. var is the old way and can be used anywhere in a function  but it can be changed anytime which can cause mistakes. let is better because it only works inside {} where it was made, and while you can change its value, you can’t declare it again in the same place. const is like let but once you set a value, you can’t change it at all. It’s best to use const for values that don’t change and let for ones that do while var is not recommended.

references:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var
https://javascript.info/variables

2. Concept of Falsy Values in JavaScript
Falsy values in JavaScript are values that act like false when used in conditions. If a falsy value is inside an if statement, the code won’t run because JavaScript sees it as false. Some common falsy values are 0, "" (empty string), null, undefined, NaN, and false. These values are useful when checking if a variable has real data or not. Knowing them helps avoid mistakes when working with user input or missing values.
examples:
0 is falsy, so if you write if (0), the code inside won’t run.
An empty string ("") is also falsy, so if ("") will not work because it's seen as false.
null is falsy, so using if (null) will make the condition fail. 

references:
https://www.w3schools.com/js/js_booleans.asp
https://developer.mozilla.org/en-US/docs/Glossary/Falsy
