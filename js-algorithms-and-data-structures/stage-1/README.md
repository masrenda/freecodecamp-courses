<p align="left">
    <img src="https://i.postimg.cc/brpV1vM8/image.png" />
</p>
JavaScript is a scripting language you can use to make web pages interactive. It is one of the core technologies of the web, along with HTML and CSS, and is supported by all modern browsers.

In this course, you'll learn fundamental programming concepts in JavaScript. You'll start with basic data structures like numbers and strings. Then you'll learn to work with arrays, objects, functions, loops, if/else statements, and more.

## Table of Contents

1. [Comment Your Javascript Code](#1-comment-your-javascript-code)
2. [Declare Javascript Variales](#2-declare-javascript-variables)
3. [Storing Values with The Assignment Operator](#3-storing-values-with-the-assignment-operator)
4. [Assigning The Value of One Variable to Another](#4-assigning-the-value-of-one-variable-to-another)
5. [Initializing Variables with The Assignment Operator](#5-initializing-variables-with-the-assignment-operator)
6. [Declare String Variables](#6-declare-string-variables)
7. [Understanding Uninitialized Variables](#7-understanding-uninitialized-variables)
8. [Understanding Case Sensitivity in Variables](#8-understanding-case-sensitivity-in-variables)
9. [Explore Differences between The var and let Keywords](#9-explore-differences-between-the-var-and-let-keywords)
10. [Declare a read-only Variable with The const Keyword](#10-declare-a-read-only-variable-with-the-const-keyword)
11. [Add Two Number with Javascript](#11-add-two-number-with-javascript)
12. [Subtract One Number from Another with Javascript](#12-subtract-one-number-from-another-with-javascript)
13. [Multiply Two Numbers with Javascript](#13-multiply-two-numbers-with-javascript)
14. [Divide One Number by Another with Javascript](#14-divide-one-number-by-another-with-javascript)
15. [Increment a Number with Javascript](#15-increment-a-number-with-javascript)
16. [Decrement a Number with Javascript](#16-decrement-a-number-with-javascript)
17. [Create Decimal Number with Javascript](#17-create-decimal-number-with-javascript)
18. [Multiply Two Decimals with JavaScript](#18-multiply-two-decimals-with-javascript)
19. [Divide One Decimal by Another with Javascript](#19-divide-one-decimal-by-another-with-javascript)
20. [Finding a Remainder in JavaScript](#20-finding-a-remainder-in-javascript)
21. [Compound Assignment with Augmented Addition](#21-compound-assignment-with-augmented-addition)
22. [Compound Assignment with Augmented Subtraction](#22-compound-assignment-with-augmented-subtraction)
23. [Compound Assignment with Augmented Multiplication](#23-compound-assignment-with-augmented-multiplication)
24. [Compound Assignment with Augmented Division](#24-compound-assignment-with-augmented-division)
25. [Escaping Literal Quotes in Strings](#25-escaping-literal-quotes-in-strings)
26. [Quoting Strings with Single Quotes](#26-quoting-strings-with-single-quotes)
27. [Escape Sequences in Strings](#27-escape-sequences-in-strings)
28. [Concatenating Strings with Plus Operator](#28-concatenating-strings-with-plus-operator)
29. [Concatenating Strings with Plus Equal Operator](#29-concatenating-strings-with-plus-equal-operator)
30. [Constructing Strings with Variables](#30-constructing-strings-with-variables)
31. [Appending Variables to Strings](#31-appending-variables-to-strings)
32. [Find the Length of a String](#32-find-the-length-of-a-string)
33. [Use Bracket Notation to Find the First Character in a String](#33-use-bracket-notation-to-find-the-first-character-in-a-string)
34. [Understand String Immutability](#34-understand-string-immutability)
35. [Use Bracket Notation to Find the Nth Character in a String](#35-use-bracket-notation-to-find-the-nth-character-in-a-string)
36. [Use Bracket Notation to Find the Last Character in a String](#36-use-bracket-notation-to-find-the-last-character-in-a-string)
37. [Use Bracket Notation to Find the Nth-to-Last Character in a String](#37-use-bracket-notation-to-find-the-nth-to-last-character-in-a-string)
38. [Word Blanks](#38-word-blanks)
39. [ Store Multiple Values in one Variable using JavaScript Arrays](#39-store-multiple-values-in-one-variable-using-javascript-arrays)
40. [Nest one Array within Another Array](#40-nest-one-array-within-another-array)
41. [Access Array Data with Indexes](#41-access-array-data-with-indexes)
42. [Modify Array Data With Indexes](#42-modify-array-data-with-indexes)
43. [Access Multi-Dimensional Arrays With Indexes](#43-access-multi-dimensional-arrays-with-indexes)
44. [Manipulate Arrays With push()](#44-manipulate-arrays-with-push)
45. [Manipulate Arrays With pop()](#45-manipulate-arrays-with-pop)
46. [Manipulate Arrays With shift()](#46-manipulate-arrays-with-shift)

## Roadmap

### 1. Comment Your Javascript Code

Try creating one of each type of comment.

```js
// This is an in-line comment.

/* This is a
multi-line comment */
```

[Back to Top](#table-of-contents)

### 2. Declare Javascript Variables

Use the `var` keyword to create a variable called `myName`.

```js
var myName;
```

[Back to Top](#table-of-contents)

### 3. Storing Values with The Assignment Operator

Assign the value `7` to variable `a`.

```js
var a;

var myVar = 7;
a = myVar;
```

[Back to Top](#table-of-contents)

### 4. Assigning The Value of One Variable to Another

Assign the contents of `a` to variable `b`.

```js
var a;
a = 7;
var b;

b = a;
```

[Back to Top](#table-of-contents)

### 5. Initializing Variables with The Assignment Operator

Define `a` variable a with `var` and initialize it to a value of `9`.

```js
var a = 9;
```

[Back to Top](#table-of-contents)

### 6. Declare String Variables

Create `two` new string variables: `myFirstName` and `myLastName` and assign them the values of your first and last name, respectively.

```js
var myFirstName = "Jhon";
var myLastName = "Doe";

myFirstName + myLastName;
```

[Back to Top](#table-of-contents)

### 7. Understanding Uninitialized Variables

Initialize the three variables `a`, `b`, and `c` with `5`, `10`, and `"I am a"` respectively so that they will not be `undefined`.

```js
var a;
var b;
var c;

var a = 5;
var b = 10;
var c = "I am a";

a = a + 1;
b = b + 5;
c = c + " String!";
```

[Back to Top](#table-of-contents)

### 8. Understanding Case Sensitivity in Variables

Modify the existing declarations and assignments so their names use _camelCase_. Do not create any new variables.

```js
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```

[Back to Top](#table-of-contents)

### 9. Explore Differences between The var and let Keywords

Update the code so it only uses the `let` keyword.

```js
let catName = "Oliver";
let catSound = "Meow!";
```

[Back to Top](#table-of-contents)

### 10. Declare a read-only Variable with The const Keyword

Change the code so that all variables are declared using `let` or `const`. Use `let` when you want the variable to change, and `const` when you want the variable to remain constant. Also, rename variables declared with `const` to conform to common practices. Do not change the strings assigned to the variables.

```js
const FCC = "freeCodeCamp";
let fact = "is cool!";

fact = "is awesome!";
console.log(FCC, fact);
```

[Back to Top](#table-of-contents)

### 11. Add Two Number with Javascript

Change the `0` so that sum will equal `20`.

```js
const sum = 20 + 0;
```

[Back to Top](#table-of-contents)

### 12. Subtract One Number from Another with Javascript

Change the `0` so the difference is `12`.

```js
const difference = 45 - 33;
```

[Back to Top](#table-of-contents)

### 13. Multiply Two Numbers with Javascript

Change the `0` so that product will equal `80`.

```js
const product = 8 * 10;
```

[Back to Top](#table-of-contents)

### 14. Divide One Number by Another with Javascript

Change the `0` so that the `quotient` is equal to `2`.

```js
const quotient = 66 / 33;
```

[Back to Top](#table-of-contents)

### 15. Increment a Number with Javascript

Change the code to use the `++` operator on `myVar`.

```js
let myVar = 87;

myVar++;
```

[Back to Top](#table-of-contents)

### 16. Decrement a Number with Javascript

Change the code to use the `--` operator on `myVar`.

```js
let myVar = 11;

myVar--;
```

[Back to Top](#table-of-contents)

### 17. Create Decimal Number with Javascript

Create a variable `myDecimal` and give it a decimal value with a fractional part (e.g. `5.7`).

```js
const ourDecimal = 5.7;

const myDecimal = 5.7;
```

[Back to Top](#table-of-contents)

### 18. Multiply Two Decimals with JavaScript

Change the `0.0` so that product will equal `5.0`.

```js
const product = 2.0 * 2.5;
```

[Back to Top](#table-of-contents)

### 19. Divide One Decimal by Another with Javascript

Change the `0.0` so that `quotient` will equal to `2.2`.

```js
const quotient = 4.4 / 2.0;
```

[Back to Top](#table-of-contents)

### 20. Finding a Remainder in JavaScript

Set `remainder` equal to the remainder of `11` divided by `3` using the remainder (`%`) operator.

```js
const remainder = 2 % 6;
```

[Back to Top](#table-of-contents)

### 21. Compound Assignment with Augmented Addition

Convert the assignments for `a`, `b`, and `c` to use the `+=` operator.

```js
let a = 3;
let b = 17;
let c = 12;

a += 12;
b += 9;
c += 7;
```

[Back to Top](#table-of-contents)

### 22. Compound Assignment with Augmented Subtraction

Convert the assignments for `a`, `b`, and `c` to use the `-=` operator.

```js
let a = 11;
let b = 9;
let c = 3;

a -= 6;
b -= 15;
c -= 1;
```

[Back to Top](#table-of-contents)

### 23. Compound Assignment with Augmented Multiplication

Convert the assignments for `a`, `b`, and `c` to use the `*=` operator.

```js
let a = 5;
let b = 12;
let c = 4.6;

a *= 5;
b *= 3;
c *= 10;
```

[Back to Top](#table-of-contents)

### 24. Compound Assignment with Augmented Division

Convert the assignments for `a`, `b`, and `c` to use the `/=` operator.

```js
let a = 48;
let b = 108;
let c = 33;

a /= 12;
b /= 4;
c /= 11;
```

[Back to Top](#table-of-contents)

### 25. Escaping Literal Quotes in Strings

Use backslashes to assign a string to the `myStr` variable so that if you were to print it to the console, you would see:

> I am a "double quoted" string inside "double quotes".

```js
const myStr = 'I am a "double quoted" string inside "double quotes".';
```

[Back to Top](#table-of-contents)

### 26. Quoting Strings with Single Quotes

Change the provided string to a string with single quotes at the beginning and end and no escape characters.

Right now, the `<a>` tag in the string uses double quotes everywhere. You will need to change the outer quotes to single quotes so you can remove the escape characters.

```js
const myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```

[Back to Top](#table-of-contents)

### 27. Escape Sequences in Strings

Assign the following three lines of text into the single variable `myStr` using escape sequences.

> FirstLine <br>
>       \SecondLine <br>
> ThirdLine

You will need to use escape sequences to insert special characters correctly. You will also need to follow the spacing as it looks above, with no spaces between escape sequences or words.

Note: The indentation for `SecondLine` is achieved with the tab escape character, not spaces.

```js
const myStr = "FirstLine\n\t\\SecondLine\nThirdLine";
```

[Back to Top](#table-of-contents)

### 28. Concatenating Strings with Plus Operator

Build `myStr` from the strings `This is the start`. and `This is the end`. using the `+` operator. Be sure to include a space between the two strings.

```js
const myStr = "This is the start. " + "This is the end.";
```

[Back to Top](#table-of-contents)

### 29. Concatenating Strings with Plus Equal Operator

Build `myStr` over several lines by concatenating these two strings: `This is the first sentence`. and `This is the second sentence`. using the `+=` operator. Use the `+=` operator similar to how it is shown in the example and be sure to include a space between the two strings. Start by assigning the first string to `myStr`, then add on the second string.

```js
let myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";
```

[Back to Top](#table-of-contents)

### 30. Constructing Strings with Variables

Set `myName` to a string equal to your name and build `myStr` with `myName` between the strings `My name is` and `and I am well!`

```js
const myName = "Jhon";
const myStr = "My name is " + myName + "and I am well!";
```

[Back to Top](#table-of-contents)

### 31. Appending Variables to Strings

Set `someAdjective` to a string of at least 3 characters and append it to `myStr` using the `+=` operator.

```js
const someAdjective = "Hello Jhon Doe";
let myStr = "Learning to code is ";

myStr += someAdjective;
```

[Back to Top](#table-of-contents)

### 32. Find the Length of a String

Use the `.length` property to set `lastNameLength` to the number of characters in `lastName`.

```js
let lastNameLength = 0;
const lastName = "Lovelace";

lastNameLength = lastName.length;
```

[Back to Top](#table-of-contents)

### 33. Use Bracket Notation to Find the First Character in a String

Use bracket notation to find the first character in the `lastName` variable and assign it to `firstLetterOfLastName`.

```js
let firstLetterOfLastName = "";
const lastName = "Lovelace";

firstLetterOfLastName = lastName[0];
```

[Back to Top](#table-of-contents)

### 34. Understand String Immutability

Correct the assignment to `myStr` so it contains the string value of `Hello World` using the approach shown in the example above.

```js
let myStr = "Jello World";

myStr = "Hello World";
```

[Back to Top](#table-of-contents)

### 35. Use Bracket Notation to Find the Nth Character in a String

Let's try to set `thirdLetterOfLastName` to equal the third letter of the `lastName` variable using bracket notation.

```js
const lastName = "Lovelace";

const thirdLetterOfLastName = lastName[2];
```

[Back to Top](#table-of-contents)

### 36. Use Bracket Notation to Find the Last Character in a String

Use _bracket notation_ to find the last character in the `lastName` variable.

```js
const lastName = "Lovelace";

const lastLetterOfLastName = lastName[lastName.length - 1];
```

[Back to Top](#table-of-contents)

### 37. Use Bracket Notation to Find the Nth-to-Last Character in a String

Use _bracket notation_ to find the second-to-last character in the `lastName` string.

```js
const lastName = "Lovelace";

const secondToLastLetterOfLastName = lastName[lastName.length - 2];
```

[Back to Top](#table-of-contents)

### 38. Word Blanks

In this challenge, we provide you with a noun, a verb, an adjective and an adverb. You need to form a complete sentence using words of your choice, along with the words we provide.

You will need to use the string concatenation operator `+` to build a new string, using the provided variables: `myNoun`, `myAdjective`, `myVerb`, and `myAdverb`. You will then assign the formed string to the `wordBlanks` variable. You should not change the words assigned to the variables.

You will also need to account for spaces in your string, so that the final sentence has spaces between all the words. The result should be a complete sentence.

```js
const myNoun = "dog";
const myAdjective = "big";
const myVerb = "ran";
const myAdverb = "quickly";

const wordBlanks = myNoun + " " + myAdjective + " " + myVerb + " " + myAdverb;
```

[Back to Top](#table-of-contents)

### 39. Store Multiple Values in one Variable using JavaScript Arrays

Modify the new array `myArray` so that it contains both a string and a number (in that order).

```js
const myArray = ["jhon", 2];
```

[Back to Top](#table-of-contents)

### 40. Nest one Array within Another Array

Create a nested array called `myArray`.

```js
const myArray = [["Jhon"], ["Doe"]];
```

[Back to Top](#table-of-contents)

### 41. Access Array Data with Indexes

Create a variable called `myData` and set it to equal the first value of `myArray` using bracket notation.

```js
const myArray = [50, 60, 70];

const myData = myArray[0];
```

[Back to Top](#table-of-contents)

### 42. Modify Array Data With Indexes

Modify the data stored at index `0` of `myArray` to a value of `45`.

```js
const myArray = [18, 64, 99];

myArray[0] = 45;
```

[Back to Top](#table-of-contents)

### 43. Access Multi-Dimensional Arrays With Indexes

Using bracket notation select an element from `myArray` such that `myData` is equal to `8`.

```js
const myArray = [
	[1, 2, 3],
	[4, 5, 6],
	[7, 8, 9],
	[[10, 11, 12], 13, 14],
];

const myData = myArray[2][1];
```

[Back to Top](#table-of-contents)

### 44. Manipulate Arrays With push()

Push `["dog", 3]` onto the end of the `myArray` variable.

```js
const myArray = [
	["John", 23],
	["cat", 2],
];

myArray.push(["dog", 3]);
```

[Back to Top](#table-of-contents)

### 45. Manipulate Arrays With pop()

Use the `.pop()` function to remove the last item from `myArray` and assign the popped off value to a new variable, `removedFromMyArray`.

```js
const myArray = [
	["John", 23],
	["cat", 2],
];

const removedFromMyArray = myArray.pop();
```

[Back to Top](#table-of-contents)

### 46. Manipulate Arrays With shift()

Use the `.shift()` function to remove the first item from `myArray` and assign the "shifted off" value to a new variable, `removedFromMyArray`.

```js
const myArray = [
	["John", 23],
	["dog", 3],
];

const removedFromMyArray = myArray.shift();
```

[Back to Top](#table-of-contents)

### 47. Manipulate Arrays With unshift()

Add `["Paul", 35]` to the beginning of the `myArray` variable using `unshift()`.

```js
const myArray = [
	["John", 23],
	["dog", 3],
];
myArray.shift();

myArray.unshift(["Paul", 35]);
```

[Back to Top](#table-of-contents)

### 48. Shopping List

Create a shopping list in the variable `myList`. The list should be a multi-dimensional array containing several sub-arrays.

The first element in each sub-array should contain a string with the name of the item. The second element should be a number representing the quantity i.e.

> ```js
> ["Chocolate Bar", 15];
> ```

There should be at least 5 sub-arrays in the list.

```js
var myList = [
	["Canned Beans", 3],
	["Milk Galon", 1],
	["Cereal", 2],
	["Toilet Paper", 12],
	["Sack of Rice", 1],
];
```

[Back to Top](#table-of-contents)

### 49. Write Reusable JavaScript with Functions

1. Create a function called `reusableFunction` which prints the string `Hi World` to the dev console.
2. Call the function.

```js
function reusableFunction() {
	console.log("Hi World");
}

reusableFunction();
```

[Back to Top](#table-of-contents)

### 50. Passing Values to Functions with Arguments

1. Create a function called `functionWithArgs` that accepts two arguments and outputs their sum to the dev console.
2. Call the function with two numbers as arguments.

```js
function functionWithArgs(param1, param2) {
	console.log(param1 + param2);
}

functionWithArgs(7, 3);
```

[Back to Top](#table-of-contents)

### 51.

[Back to Top](#table-of-contents)

### 52.

[Back to Top](#table-of-contents)

### 53.

[Back to Top](#table-of-contents)

### 54.

[Back to Top](#table-of-contents)

### 55.

[Back to Top](#table-of-contents)

### 56.

[Back to Top](#table-of-contents)

### 57.

[Back to Top](#table-of-contents)

### 58.

[Back to Top](#table-of-contents)

### 59.

[Back to Top](#table-of-contents)

### 60.

[Back to Top](#table-of-contents)

### 61.

[Back to Top](#table-of-contents)

### 62.

[Back to Top](#table-of-contents)

### 63.

[Back to Top](#table-of-contents)

### 64.

[Back to Top](#table-of-contents)

### 65.

[Back to Top](#table-of-contents)

### 66.

[Back to Top](#table-of-contents)

### 67.

[Back to Top](#table-of-contents)

### 68.

[Back to Top](#table-of-contents)

### 69.

[Back to Top](#table-of-contents)

### 70.

[Back to Top](#table-of-contents)
