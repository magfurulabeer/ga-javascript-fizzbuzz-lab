| Title | Type | Duration | Author |
| -- | -- | -- | -- |
| FizzBuzz Control Flow | Lesson | 1:00 | Sonyl Nagale (adapted from SEI) |


# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) FizzBuzz 

FizzBuzz is a game about division. Create a program that will iterate through numbers from one to 101 and log each number in the console.

- In the loop, every time a number is divisible by **three**, instead of logging the number itself, the word "fizz" should appear.
- If the number is divisible by **five**, the word "buzz" should be logged.
- If the number is divisible by both **three** and **five**, then the word "fizzbuzz" should be logged.

**Hint**: Go read about the [modulus operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators) on MDN and figure out how to use it to simplify this problem.

A typical output in Chrome's DevTools would look like this:

![](./images/fizzbuzz.png)

## Deliverables
You will create a repo `javascript-fizzbuzz` in your GitHub account. Create `fizzbuzz.js` file in it. Submit the link to the repo in homework tracker.

<!--<details> 
    <summary>Solution</summary>

```javascript
for (let i = 1; i < 101; i++) {

  if((i % 3 === 0) && (i % 5 === 0)) {
    console.log("fizzbuzz");
  } else if(i % 3 === 0) {
    console.log("fizz");
  } else if(i % 5 === 0) {
    console.log("buzz");
  } else {
    console.log(i);
  }
}
```

</details>-->