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

## Roadmap

### 1. Comment Your Javascript Code

Try creating one of each type of comment.

```js
// This is an in-line comment.

/* This is a
multi-line comment */
```

### 2. Declare Javascript Variables

Use the `var` keyword to create a variable called `myName`.

```js
var myName;
```

### 3. Storing Values with The Assignment Operator

Assign the value `7` to variable `a`.

```js
var a;

var myVar = 7;
a = myVar;
```

### 4. Assigning The Value of One Variable to Another

Assign the contents of `a` to variable `b`.

```js
var a;
a = 7;
var b;

b = a;
```

### 5. Initializing Variables with The Assignment Operator

Define `a` variable a with `var` and initialize it to a value of `9`.

```js
var a = 9;
```

### 6. Declare String Variables

Create `two` new string variables: `myFirstName` and `myLastName` and assign them the values of your first and last name, respectively.

```js
var myFirstName = "Jhon";
var myLastName = "Doe";

myFirstName + myLastName;
```

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

### 9. Explore Differences between The var and let Keywords

Update the code so it only uses the `let` keyword.

```js
let catName = "Oliver";
let catSound = "Meow!";
```

### 10. Declare a read-only Variable with The const Keyword

Change the code so that all variables are declared using `let` or `const`. Use `let` when you want the variable to change, and `const` when you want the variable to remain constant. Also, rename variables declared with `const` to conform to common practices. Do not change the strings assigned to the variables.

```js
const FCC = "freeCodeCamp";
let fact = "is cool!";

fact = "is awesome!";
console.log(FCC, fact);
```

### 11 - Add Two Number with Javascript

```js
const sum = 20 + 0;
```

### 12 - Subtract One Number from Another with Javascript

```js
const difference = 45 - 33;
```

### 13 - Multiply Two Numbers with Javascript

```js
const product = 8 * 10;
```

### 14 - Divide One Number by Another with Javascript

```js
const quotient = 66 / 33;
```

### 15 - Increment a Number with Javascript

```js
let myVar = 87;

myVar++;
```

### 16 - Decrement a Number with Javascript

```js
let myVar = 11;

myVar--;
```

### 17 - Create Decimal Number with Javascript

```js
const ourDecimal = 5.7;

const myDecimal = 5.7;
```

### 18 - Multiply Two Decimals with JavaScript

```js
const product = 2.0 * 2.5;
```

### 19 - Divide One Decimal by Another with Javascript

```js
const quotient = 4.4 / 2.0;
```

### 20 - Finding a Remainder in JavaScript

```js
const remainder = 2 % 6;
```

### 21 - Compound Assignment with Augmented Addition

```js
let a = 3;
let b = 17;
let c = 12;

a += 12;
b += 9;
c += 7;
```

### 22 - Compound Assignment with Augmented Subtraction

```js
let a = 11;
let b = 9;
let c = 3;

a -= 6;
b -= 15;
c -= 1;
```

### 23 - Compound Assignment with Augmented Multiplication

```js
let a = 5;
let b = 12;
let c = 4.6;

a *= 5;
b *= 3;
c *= 10;
```

### 24 - Compound Assignment with Augmented Division

```js
let a = 48;
let b = 108;
let c = 33;

a /= 12;
b /= 4;
c /= 11;
```

### 25 - Escaping Literal Quotes in Strings

```js
const myStr = 'I am a "double quoted" string inside "double quotes".';
```

### 26 - Quoting Strings with Single Quotes

```js
const myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```

### 27 - Escape Sequences in Strings

```js
const myStr = "FirstLine\n\t\\SecondLine\nThirdLine";
```

### 28 - Concatenating Strings with Plus Operator

```js
const myStr = "This is the start. " + "This is the end.";
```

### 29 - Concatenating Strings with Plus Equal Operator

```js
let myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";
```

### 30 - Constructing Strings with Variables

```js
const myName = "Jhon";
const myStr = "My name is " + myName + "and I am well!";
```

### 31 - Appending Variables to Strings

```js
const someAdjective = "Hello Jhon Doe";
let myStr = "Learning to code is ";

myStr += someAdjective;
```

### 32 - Find the Length of a String

```js
let lastNameLength = 0;
const lastName = "Lovelace";

lastNameLength = lastName.length;
```

### 33 - Use Bracket Notation to Find the First Character in a String

```js
let firstLetterOfLastName = "";
const lastName = "Lovelace";

firstLetterOfLastName = lastName[0];
```

### 34 - Understand String Immutability

```js
let myStr = "Jello World";

myStr = "Hello World";
```

### 34 - Use Bracket Notation to Find the Nth Character in a String

```js
const lastName = "Lovelace";

const thirdLetterOfLastName = lastName[2];
```

### 35 - Use Bracket Notation to Find the Last Character in a String

```js
const lastName = "Lovelace";

const lastLetterOfLastName = lastName[lastName.length - 1];
```

### 36 - Use Bracket Notation to Find the Nth-to-Last Character in a String

```js
const lastName = "Lovelace";

const secondToLastLetterOfLastName = lastName[lastName.length - 2];
```

### 37 - Word Blanks

```js
const myNoun = "dog";
const myAdjective = "big";
const myVerb = "ran";
const myAdverb = "quickly";

const wordBlanks = myNoun + " " + myAdjective + " " + myVerb + " " + myAdverb;
```

### 38 - Store Multiple Values in one Variable using JavaScript Arrays

```js
const myArray = ["jhon", 2];
```

### 39 - Nest one Array within Another Array

```js
const myArray = [["Jhon"], ["Doe"]];
```

### 40 - Access Array Data with Indexes

```js
const myArray = [50, 60, 70];

const myData = myArray[0];
```

### 41 - Modify Array Data With Indexes

```js
const myArray = [18, 64, 99];

myArray[0] = 45;
```

### 42 - Access Multi-Dimensional Arrays With Indexes

```js
const myArray = [
	[1, 2, 3],
	[4, 5, 6],
	[7, 8, 9],
	[[10, 11, 12], 13, 14],
];

const myData = myArray[2][1];
```

### 43 - Manipulate Arrays With push()

```js
const myArray = [
	["John", 23],
	["cat", 2],
];

myArray.push(["dog", 3]);
```

### 44 - Manipulate Arrays With pop()

```js
const myArray = [
	["John", 23],
	["cat", 2],
];

const removedFromMyArray = myArray.pop();
```

### 45 - Manipulate Arrays With shift()

```js
const myArray = [
	["John", 23],
	["dog", 3],
];

const removedFromMyArray = myArray.shift();
```
