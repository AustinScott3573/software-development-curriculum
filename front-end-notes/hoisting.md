# Javascript Hoisting

 1. Parse the scope and detect all function definitions   
 2. Execute the code top-to-bottom with all functions found in step 1 available as variables

This behavior is called 'hoisting' because it is almost like the function definitions have been 'hoisted' up to the top of the function.

### Hoisting is JavaScript's default behavior of moving all declarations to the top of the current scope (to the top of the current script or the current function).

```javascript
x = 5; // Assign 5 to x

elem = document.getElementById("demo"); // Find an element 
elem.innerHTML = x;                     // Display x in the element

var x; // Declare x 
```

#### The next example shows the Javascript as IF it had been hoisted.

```Javascript
var x; // Declare x
x = 5; // Assign 5 to x

elem = document.getElementById("demo"); // Find an element 
elem.innerHTML = x;                     // Display x in the element
```

The declaration has been "hoisted" to the top.

http://www.w3schools.com/js/js_hoisting.asp


