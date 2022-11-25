# let and const Exercise

In this exercise, you’ll refactor some ES5 code into ES2015.

## ES5 Global Constants

var PI = 3.14;

PI = 42; // stop me from doing this!

## ES2015 Global Constants

/* Write an ES2015 Version */

let PI = 3.14;

PI = 42;

## Quiz

- What is the difference between var and let?

`var` :
  - Can be Reassign,
  - Can be Redeclare,
  - Can be Mutate
  -	has function scope // that means can be available everywhere
  	
`let` :
  - Can be Reassign,
  - Cannot be Redeclare,
  - Can be Mutate
  -	block scope // that means it is available in the curly braces where is defined

- What is the difference between var and const?

`var` :
  - Can be Reassign,
  - Can be Redeclare,
  - Can be Mutate
  -	has function scope // that means can be available everywhere	

`const` :
  - Cannot be Reassign,
  - Cannot be Redeclare,
  - Can be Mutate
  -	block scope // that means it is available in the curly braces where is defined

- What is the difference between let and const?

`let` :
  - Can be Reassign,
  - Cannot be Redeclare,
  - Can be Mutate
  -	block scope // that means it is available in the curly braces where is defined

`const` :
  - Cannot be Reassign,
  - Cannot be Redeclare,
  - Can be Mutate
  -	block scope // that means it is available in the curly braces where is defined

- What is hoisting?
 Hoisting is a behavior of `var`, `let` and `const` keywords.
