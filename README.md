# my-6th-project

Code Explanation (Multiple Variable Declaration Example)
Overview

This TypeScript code demonstrates how to declare multiple variables in a single statement, assign values to them, perform an addition operation, and print the result to the console.

Step-by-Step Explanation
let num1, num2, num3: number;


Three variables are declared in one line: num1, num2, and num3.

The type number applies to num3.

In TypeScript, when declaring multiple variables this way, only the last variable (num3) is explicitly typed as number.

To ensure all variables are strictly typed, it is better practice to write:

let num1: number, num2: number, num3: number;

num1 = 30, num2 = 90, num3 = 10;


Values are assigned to the variables:

num1 = 30

num2 = 90

num3 = 10

Commas are used here to separate assignment expressions.

console.log(num1 + num2 + num3);


The + operator is used to add the three numbers.

console.log() prints the result to the console.

The calculation:

30 + 90 + 10 = 130

The output will be:

130

 What the Code Does

Declares three variables.

Assigns numeric values to each variable.

Adds the three numbers together.

Prints the final result to the console.

 Learning Purpose

Understanding multiple variable declaration in TypeScript.

Learning how type annotations work in grouped declarations.

Performing addition with multiple numbers.
