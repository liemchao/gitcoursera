# Assignment Of JavaScript

                                   |

🧡🧡🧡 HAPPY CODING 🧡🧡🧡

<div>
<small>Support the <strong>author</strong> to create more educational materials</small> <br />
</div>

<div align="center">
  <h1> Assignment JavaScript: Introduction</h1>
<sub>Author:
<a href="#" target="_blank">Phạm Thanh Tùng</a><br>
<small> December, 2023</small>
</sub>

<div>

</div>

</div>
</div>


## Introduction

**Congratulations** on deciding to participate in 30 days of JavaScript programming challenge. In this challenge, you will learn everything you need to be a JavaScript programmer, and in general, the whole concept of programming. In the end of the challenge, you will get a 30DaysOfJavaScript programming challenge completion certificate. 

**Assignment** challenge is a guide for both beginners and advanced JavaScript developers. Welcome to JavaScript. JavaScript is the language of the web. I enjoy using and teaching JavaScript and I hope you will do so too.

In this step by step JavaScript challenge, you will learn JavaScript, the most popular programming language in the history of mankind.
JavaScript is used **_to add interactivity to websites, to develop mobile apps, desktop applications, games_** and nowadays JavaScript can be used for **server-side programming**, **_machine learning_** and **_AI_**.

**_JavaScript (JS)_** has increased in popularity in recent years and has been the leading
programming language for last ten years and is the most used programming language on
GitHub.
## Requirements

No prior knowledge of programming is required to follow this challenge. You need only:

1. Motivation
2. A computer
3. Internet
4. A browser
5. A code editor

## Setup

I believe you have the motivation and a strong desire to be a developer, a computer and Internet. If you have those, then you have everything to get started.

### Install Node.js

You may not need Node.js right now but you may need it for later. Install [node.js].

![Node download]

After downloading double click and install

![Install node]

We can check if node is installed on our local machine by opening our device terminal or command prompt.

```sh
adminpc $ node -v
v12.14.0
```

When making this tutorial I was using Node version 12.14.0, but now the recommended version of Node.js for download is v14.17.6, by the time you use this material you may have a higher Node.js version.

### Browser

There are many browsers out there. However, I strongly recommend Google Chrome.

#### Installing Google Chrome

Install [Google Chrome] if you do not have one yet. We can write small JavaScript code on the browser console, but we do not use the browser console to develop applications.

![Google Chrome]

#### Opening Google Chrome Console

You can open Google Chrome console either by clicking three dots at the top right corner of the browser, selecting _More tools -> Developer tools_ or using a keyboard shortcut. I prefer using shortcuts.

![Opening chrome]

To open the Chrome console using a keyboard shortcut.

```sh
Mac
Command+Option+J

Windows/Linux:
Ctl+Shift+J
```

![Opening console]

After you open the Google Chrome console, try to explore the marked buttons. We will spend most of the time on the Console. The Console is the place where your JavaScript code goes. The Google Console V8 engine changes your JavaScript code to machine code.
Let us write a JavaScript code on the Google Chrome console:

![write code on console]

#### Writing Code on Browser Console

We can write any JavaScript code on the Google console or any browser console. However, for this challenge, we only focus on Google Chrome console. Open the console using:

```sh
Mac
Command+Option+I

Windows:
Ctl+Shift+I
```

##### Console.log

To write our first JavaScript code, we used a built-in function **console.log()**. We passed an argument as input data, and the function displays the output. We passed `'Hello, World'` as input data or argument in the console.log() function.

```js
console.log("Hello, World!");
```

##### Console.log with Multiple Arguments

The **`console.log()`** function can take multiple parameters separated by commas. The syntax looks like as follows:**`console.log(param1, param2, param3)`**

![console log multiple arguments]

```js
console.log("Hello", "World", "!");
console.log("HAPPY", "NEW", "YEAR", 2020);
console.log("Welcome", "to", 30, "Days", "Of", "JavaScript");
```

As you can see from the snippet code above, _`console.log()`_ can take multiple arguments.

Congratulations! You wrote your first JavaScript code using _`console.log()`_.

##### Comments

We can add comments to our code. Comments are very important to make code more readable and to leave remarks in our code. JavaScript does not execute the comment part of our code. In JavaScript, any text line starting with // in JavaScript is a comment, and anything enclosed like this `//` is also a comment.

**Example: Single Line Comment**

```js
// This is the first comment
// This is the second comment
// I am a single line comment
```

**Example: Multiline Comment**

```js
/*
This is a multiline comment  
 Multiline comments can take multiple lines  
 JavaScript is the language of the web  
 */
```

##### Syntax

Programming languages are similar to human languages. English or many other language uses words, phrases, sentences, compound sentences and other more to convey a meaningful message. The English meaning of syntax is _the arrangement of words and phrases to create well-formed sentences in a language_. The technical definition of syntax is the structure of statements in a computer language. Programming languages have syntax. JavaScript is a programming language and like other programming languages it has its own syntax. If we do not write a syntax that JavaScript understands, it will raise different types of errors. We will explore different kinds of JavaScript errors later. For now, let us see syntax errors.

![Error]

I made a deliberate mistake. As a result, the console raises syntax errors. Actually, the syntax is very informative. It informs what type of mistake was made. By reading the error feedback guideline, we can correct the syntax and fix the problem. The process of identifying and removing errors from a program is called debugging. Let us fix the errors:

```js
console.log("Hello, World!");
console.log("Hello, World!");
```

So far, we saw how to display text using the _`console.log()`_. If we are printing text or string using _`console.log()`_, the text has to be inside the single quotes, double quotes, or a backtick.
**Example:**

```js
console.log("Hello, World!");
console.log("Hello, World!");
console.log(`Hello, World!`);
```

#### Arithmetics

Now, let us practice more writing JavaScript codes using _`console.log()`_ on Google Chrome console for number data types.
In addition to the text, we can also do mathematical calculations using JavaScript. Let us do the following simple calculations.
It is possible to write JavaScript code on Google Chrome console can directly without the **_`console.log()`_** function. However, it is included in this introduction because most of this challenge would be taking place in a text editor where the usage of the function would be mandatory. You can play around directly with instructions on the console.

![Arithmetic]

```js
console.log(2 + 3); // Addition
console.log(3 - 2); // Subtraction
console.log(2 * 3); // Multiplication
console.log(3 / 2); // Division
console.log(3 % 2); // Modulus - finding remainder
console.log(3 ** 2); // Exponentiation 3 ** 2 == 3 * 3
```

### Code Editor

We can write our codes on the browser console, but it won't be for bigger projects. In a real working environment, developers use different code editors to write their codes. In this 30 days of JavaScript challenge, we will be using Visual Studio Code.

#### Installing Visual Studio Code

Visual Studio Code is a very popular open-source text editor. I would recommend to [download Visual Studio Code](https://code.visualstudio.com/), but if you are in favor of other editors, feel free to follow with what you have.

![Vscode]

If you installed Visual Studio Code, let us start using it.

#### How to Use Visual Studio Code

Open the Visual Studio Code by double-clicking its icon. When you open it, you will get this kind of interface. Try to interact with the labeled icons.

![Vscode ui]

![Vscode add project]

![Vscode open project]

![script file]

![Installing Live Server]

![running script]

![coding running]

## Adding JavaScript to a Web Page

JavaScript can be added to a web page in three different ways:

- **_Inline script_**
- **_Internal script_**
- **_External script_**
- **_Multiple External scripts_**

🎉 CONGRATULATIONS ! 🎉
