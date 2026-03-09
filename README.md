1. What is the difference between var, let, and const?

--> var: This is the traditional way of declaring variables in JavaScript. It is Function Scoped and allows you to redeclare the same variable name multiple times. It also supports Hoisting (the variable can be used before it is declared).

--> let: Introduced in ES6 (modern JavaScript). It is Block Scoped, meaning it only exists within the {} where it is defined. It cannot be redeclared in the same scope, but its value can be updated.

--> const: Also Block Scoped, but its value cannot be changed once it is assigned (it is a constant). It is the most recommended way to declare variables in modern coding unless you know the value needs to change.

2. What is the spread operator (...)?

--> The spread operator (...) is used to expand or "spread" the elements of an array or object into another array or object.

--> Example: const newArray = [...oldArray, 4, 5]; This copies all elements from oldArray into newArray and adds 4 and 5 at the end.

3. What is the difference between map(), filter(), and forEach()?

--> map(): Iterates through each element of an array and returns a new array containing the results of a function applied to those elements.

--> filter(): Checks each element against a specific condition and returns a new array containing only the elements that meet that condition.

--> forEach(): Used simply to loop through an array. It does not return anything (it returns undefined); it is mainly used to perform actions (like console.log) on each item.

4. What is an arrow function?

--> An arrow function is a shorter and more modern syntax for writing functions in JavaScript. It looks like this: const myFunction = () => { ... }

--> It removes the need for the function keyword, making the code cleaner. Additionally, it handles the this keyword differently than regular functions, as it inherits this from its parent scope.

5. What are template literals?

--> Template literals are a modern way to create strings using backticks ( ` ) instead of quotes.

--> They allow you to easily embed variables or expressions directly into a string using the ${variableName} syntax and support writing multi-line strings without special characters.