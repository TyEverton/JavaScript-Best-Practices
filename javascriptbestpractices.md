1) Don't Use new Object()
Use {} instead of new Object()
Use "" instead of new String()
Use 0 instead of new Number()
Use false instead of new Boolean()
Use [] instead of new Array()
Use /()/ instead of new RegExp()
Use function (){} instead of new Function()

2)Avoid Global Variables
Minimize the use of global variables.

This includes all data types, objects, and functions.

Global variables and functions can be overwritten by other scripts.

Use local variables instead, and learn how to use closures.

Local variable is declared inside a function whereas Global variable is declared outside the function.


3) Use === Comparison
The == comparison operator always converts (to matching types) before comparison.

The === operator forces comparison of values and type:

4) Use arrow functions
 //Longhand 
function add(a, b) { 
   return a + b; 
} 
//Shorthand 
const add = (a, b) => a + b;

5) Comment and label your code 

6) Lookup conditions shorthand

7) Space out your code

8) Stick to a strict coding style

9) Avoid mixing with other technologies
  Keep CSS, HTML, JS etc within their designated locations/files


10)Remove duplicate code