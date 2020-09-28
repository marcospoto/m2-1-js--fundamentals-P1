# JavaScript Fundamentals - Part 1

Today we will be learning the fundamentals of JavaScript!

---

## ✋ Pre-lecture work

This workshop includes some reading and exercises that should be done prior to attending the lecture.

Read all of the `.md` files in `__pre-lecture-work`. It covers the initial fundamental concepts that we will be starting with during the lecture.

There are also some exercises that you should complete.

---

## Workshop Setup

Before starting the workshop, please run the following in the terminal. It will install all of the required dependencies. (More on that later.)

Type `ctrl`+ `j` to open the terminal inside of VS Code.

```bash
yarn install
```

In order to more easily evaluate your answers, you will need a `node` environment. VS Code provides us with a terminal, and in the terminal we can evaluate js files with Node.

It really **NOT** recommended that you use the browser console.

You can toggle the terminal window in VS Code with the following keyboard shortcut:

- `[ctrl + j]` on Windows
- `[cmd + j]` on Mac

This will open an instance of the terminal (Mac) or the PowerShell (Win).

## Type JS directly into the Node Env.

- Type `node` in the terminal, and hit `enter`.

This will turn that terminal into a Node environment for you to play with.

You can type JavaScript in the same way I did while using the web browser console.

You can also copy/paste your code from your file into the node environment.

### Exit the Node Environment

To exit/quit Node and get back to the terminal, do `[ctrl + c]` twice.

<img src="./__lecture/assets/demo_node.gif" alt="node demo" />

---

## Testing

This workshop can "test" your code and validate your answers. (We will talk more about this later.)

If you want to test your code/validate your answer, you can type `yarn test <FILE_NAME>` in the terminal (without the `.js`).

<img src="./__lecture/assets/demo_test.gif" alt="test demo" />

In this workshop, there will be a reminder to do this at the end of every exercise file.

---

## The Workshop

Each question is a `JS` file, except for the `exercise-2.md`. The question, including guidelines and hints, are also located each exercise file.

These first exercises are heavily commented. In order to implement unit tests and allow you to verify your own code, each file contains extra lines of code that are _not_ related to the actual exercise. _These lines should not be modified at all._

---

### Exercise 1

_This is a series of theory questions for you to answer. - Open [exercise-1.js](workshop/exercise-1.js) and answer in the file._

Write your answer inside of the provided `console.log()`.

```js
// Example
console.log("1.1. ( )"); /* "I am a "Horse""    */
```

### Exercise 2

_This a series of code jumble questions. Answer directly in the [exercise-2.md](workshop/exercise-2.md) file._

There is no automated testing for this file.

---

For exercises 3 to 13, you should only write the needed code to solve the exercise between the provided lines.

```js
// Write code between the lines (below)
// -----------------------------------------------------------------
// WRITE YOUR CODE HERE <--

// -----------------------------------------------------------------
// Write code between the lines (above)
```

---

### Exercise 3 - Fix this program

It is should print to the console the numbers 1, 2, 3, 4, 5.

- Open [exercise-3.js](workshop/exercise-3.js) file.

### Exercise 4 - Fix this program

It should output the squares of all numbers between 0 and 12

Open [exercise-4.js](workshop/exercise-4.js) file.

### Exercise 5 - Fix this program

It should output all of the odd numbers between 1 and 25 (including 1 and 25).

Open [exercise-5.js](workshop/exercise-5.js) file.

### Exercise 6

This exercise contains 5 questions (6.1 to 6.5) that all start with _Write a loop that ..._

- Open [exercise-6.1.js](workshop/exercise-6.1.js) file.
- Open [exercise-6.2.js](workshop/exercise-6.2.js) file.
- Open [exercise-6.3.js](workshop/exercise-6.3.js) file.
- Open [exercise-6.4.js](workshop/exercise-6.4.js) file.
- Open [exercise-6.5.js](workshop/exercise-6.5.js) file.

### Exercise 7

Life in the army is regimented!

Write a loop that will output every hour of the day (0 to 23) and determine whether it is time to sleep, eat or train.

- Open [exercise-7.js](workshop/exercise-7.js) file.

---

<center>🟡 - Minimally complete workshop (75%) - 🟡</center>

---

### Exercise 8

Write a program that will output the sum of all of the multiples of four between 0 and 5000

- Open [exercise-8.js](workshop/exercise-8.js) file.

### Exercise 9

Write a program that goes through every number between 1 and 100, and follows the following rules:

- If the number is divisible by 3 (eg. 6), print "Fizz".
- If the number is divisible by 5 (eg. 10), print "Buzz".
- If the number is divisible by 3 AND 5 (eg. 15), print "FizzBuzz".
- For all other numbers, print the number itself.

- Open [exercise-9.js](workshop/exercise-9.js) file.

### Exercise 10

Write a loop that makes seven calls to console.log to output the following triangle:

```
#
##
###
####
#####
######
#######
```

- Open [exercise-10.js](workshop/exercise-10.js) file.

---

<center>🟢 - Complete workshop (100%) - 🟢</center>

---

### Exercise 11 - Stretch

Write a program that creates a string that represents an 8×8 grid, using newline characters to separate lines.

- Open [exercise-11.js](workshop/exercise-11.js) file.

### Exercise 12 - Stretch

Write a program that generates a list of all prime numbers between 1 and 200.

- Open [exercise-12.js](workshop/exercise-12.js) file.

### Exercise 13 - Stretch

Write a program which calculates the 50th number in the fibonacci sequence.

- Open [exercise-13.js](workshop/exercise-13.js) file.
[![Run on Repl.it](https://repl.it/badge/github/marcospoto/m2-1-js--fundamentals-P1)](https://repl.it/github/marcospoto/m2-1-js--fundamentals-P1)
