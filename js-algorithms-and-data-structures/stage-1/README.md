<p align="left">
    <img src="https://i.postimg.cc/brpV1vM8/image.png" />
</p>
JavaScript is a scripting language you can use to make web pages interactive. It is one of the core technologies of the web, along with HTML and CSS, and is supported by all modern browsers.

In this course, you'll learn fundamental programming concepts in JavaScript. You'll start with basic data structures like numbers and strings. Then you'll learn to work with arrays, objects, functions, loops, if/else statements, and more.

## Roadmap

### 01 - Comment Your Javascript Code

> ```js
> // This is an in-line comment.
>
> /* This is a
> multi-line comment */
> ```

#### 02 - Declare Javascript Variables

```js
var myName;
```

#### 03 - Storing Values with The Assignment Operator

```js
var a;

var myVar = 7;
a = myVar;
```

#### 04 - Assigning The Value of One Variable to Another

```js
var a;
a = 7;
var b;

b = a;
```

#### 05 - Initializing Variables with The Assignment Operator

```js
var a = 9;
```

#### 06 - Declare String Variables

```js
var myFirstName = "Jhon";
var myLastName = "Doe";

myFirstName + myLastName;
```

#### 07 - Understanding Uninitialized Variables

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

#### 08 - Understanding Case Sensitivity in Variables

```js
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```

#### 09 - Explore Differences between The var and let Keywords

```js
let catName = "Oliver";
let catSound = "Meow!";
```

#### 10 - Declare a read-only Variable with The const Keyword

```js
const FCC = "freeCodeCamp";
let fact = "is cool!";

fact = "is awesome!";
console.log(FCC, fact);
```

#### 11 - Add Two Number with Javascript

```js
const sum = 20 + 0;
```

#### 12 - Subtract One Number from Another with Javascript

```js
const difference = 45 - 33;
```

#### 13 - Multiply Two Numbers with Javascript

```js
const product = 8 * 10;
```

#### 14 - Divide One Number by Another with Javascript

```js
const quotient = 66 / 33;
```

#### 15 - Increment a Number with Javascript

```js
let myVar = 87;

myVar++;
```

#### 16 - Decrement a Number with Javascript

```js
let myVar = 11;

myVar--;
```

#### 17 - Create Decimal Number with Javascript

```js
const ourDecimal = 5.7;

const myDecimal = 5.7;
```

#### 18 - Multiply Two Decimals with JavaScript

```js
const product = 2.0 * 2.5;
```

#### 19 - Divide One Decimal by Another with Javascript

```js
const quotient = 4.4 / 2.0;
```

#### 20 - Finding a Remainder in JavaScript

```js
const remainder = 2 % 6;
```

#### 21 - Compound Assignment with Augmented Addition

```js
let a = 3;
let b = 17;
let c = 12;

a += 12;
b += 9;
c += 7;
```

#### 22 - Compound Assignment with Augmented Subtraction

```js
let a = 11;
let b = 9;
let c = 3;

a -= 6;
b -= 15;
c -= 1;
```

#### 23 - Compound Assignment with Augmented Multiplication

```js
let a = 5;
let b = 12;
let c = 4.6;

a *= 5;
b *= 3;
c *= 10;
```

#### 24 - Compound Assignment with Augmented Division

```js
let a = 48;
let b = 108;
let c = 33;

a /= 12;
b /= 4;
c /= 11;
```

#### 25 - Escaping Literal Quotes in Strings

```js
const myStr = 'I am a "double quoted" string inside "double quotes".';
```

#### 26 - Quoting Strings with Single Quotes

```js
const myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```

#### 27 - Escape Sequences in Strings

```js
const myStr = "FirstLine\n\t\\SecondLine\nThirdLine";
```

#### 28 - Concatenating Strings with Plus Operator

```js
const myStr = "This is the start. " + "This is the end.";
```

#### 29 - Concatenating Strings with Plus Equal Operator

```js
let myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";
```

#### 30 - Concatenating Strings with Variables

```js
const myName = "Jhon";
const myStr = "My name is " + myName + "and I am well!";
```
