# Question Summary

Oh no! We had a bunch of perfectly-fine code running along smoothly, but then
the Hamburglar swooped in and jumbled our code. We still have all the right
pieces, but they're in the wrong order!

Your mission is to rearrange each line of code so that it forms a coherent
program, and solves the given problem.

_NOTE:_ The lines don't include any indentation (since that would give the
answer away). You should add indentation as appropriate (see example)

_ANOTHER NOTE:_ There may be more than 1 correct answer. If multiple variables
are declared in a row, the order doesn't matter.

_LAST NOTE:_ Feel free to add blank lines between the lines of code, to make it
easier to read. Like the gap between 2. and 1. in the example's solution.

---

## EXAMPLE - log all even numbers

1. if (isEven) {
2. let isEven = i % 2 === 0;
3. console.log(i, 'is an even number!');
4. }
5. for (let i = 0; i < 10; i++) {
6. }

#### Solution:

```
5. for (let i = 0; i < 10; i++) {
2.   let isEven = i % 2 === 0;

1.   if (isEven) {
3.     console.log(i, 'is an even number!');
4.   }
6. }
```

## Question 1: Check if the sentence includes the word "Hello".

4. let sentence = 'Hello world!';
5. if (sentence.includes('Hello')) {
6. console.log('Sentence DOES contain the word "Hello"');
7. } else {
8. console.log('Sentence DOES NOT contain the word "Hello"');
9. }

Put your solution between the ```:
_THIS IS SUPER IMPORTANT_, otherwise Prettier might destroy your solution:

```
// Your solution here!

```

## Question 2: Get the specified item in the nested array

12. const array = [[1, [2, 3]]];
1. const firstIndex = array[0][0];
1. const secondIndex = array[0][1][0];
1. const thirdIndex = array[0][1][1];
1. console.log(array[firstIndex][secondindex][thirdIndex])

```
// Your solution here!

```

## Question 3: Log all numbers from 10 to 5

2. let currentNum = 10;
3. let min = 5;
4. while (currentNum >= min) {
5. console.log(currentNum);
6. currentNum-- ;
7. }

```
// Your solution here!

```

## Question 4: Reverse the string to check for hidden messages

4. const encodedMessage = 'gnidliub gruobuaF eht rednu deirub si erusaert ehT';
5. const letterArray = encodedMessage.split('');
6. const reversedArray = letterArray.reverse();
7. const reversedString = reversedArray.join('');
8. if (reversedString.includes('treasure')) {
9. console.log('Your message:', reversedString)
10. }

```
// Your solution here!

```

## Question 5: Add all the numbers from 10 to 0

6. let count = 10;
7. let total = 0;
8. while (count > 0) {
9. total = total + count;
10. count = count - 1;
11. console.log('The total is:', total)
12. }

```
// Your solution here!

```

## Question 6: Check if the array includes a specific number

7. let numberToSearchFor = 5;
8. let includesNumber;
9. let array = [1, 3, 7, 4, 5, 2, 1];
10. for (let i = 0; i < array.length; i++) {
11. let item = array[i];
12. if (item === numberToSearchFor) {
13. console.log('Array includes the number!')
14. }
15. }

```
// Your solution here!

```
