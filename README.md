# beginner-friendly-problems-js

Certainly! Here are  10 beginner-level programming problems involving `for` loops and `if...else` statements in JavaScript. Each problem comes with a brief description and a solution.

### Problem  1: Sum of Numbers
Write a program that calculates the sum of all numbers from  1 to  10 using a `for` loop.

**Solution:**
```javascript
let sum =  0;
for (let i =  1; i <=  10; i++) {
    sum += i;
}
console.log(sum); // Output:  55
```

### Problem  2: Even Numbers
Write a program that prints out all even numbers between  1 and  20 using a `for` loop and an `if` statement.

**Solution:**
```javascript
for (let i =  1; i <=  20; i++) {
    if (i %  2 ===  0) {
        console.log(i);
    }
}
```

### Problem  3: Odd Numbers
Similar to Problem  2, write a program that prints out all odd numbers between  1 and  20 using a `for` loop and an `if` statement.

**Solution:**
```javascript
for (let i =  1; i <=  20; i++) {
    if (i %  2 !==  0) {
        console.log(i);
    }
}
```

### Problem  4: Factorial
Write a program that calculates the factorial of a number using a `for` loop. The factorial of a number n is the product of all positive integers less than or equal to n.

**Solution:**
```javascript
const n = 5;
let result =  1;
for (let i =  1; i <= n; i++) {
    result *= i;
}
```


### Problem  5: Check Prime Number
Write a program that checks if a number is prime using a `for` loop and an `if` statement.

**Solution:**
```javascript
let num =   7;
let isPrime = true;
if (num <=   1) {
    isPrime = false;
} else {
    for (let i =   2; i < num; i++) {
        if (num % i ===   0) {
            isPrime = false;
            break;
        }
    }
}
console.log(isPrime); // Output: true

```
### Problem 6: Find the smallest Number
Write a program that will find the smalles number among three numbers.

**Solution**
```javascript
let num1 =  5;
let num2 =  3;
let num3 =  7;

let smallest;

if (num1 < num2 && num1 < num3) {
    smallest = num1;
} else if (num2 < num1 && num2 < num3) {
    smallest = num2;
} else {
    smallest = num3;
}

console.log(smallest); // Output will be the smallest number among num1, num2, and num3

```

### Problem 7: Find the sum of the odd numbers between 1 - 20
Write a program that will find the sum of the odd numbers between 1 - 20

**Solution**
```javascript
let sum = 0;
for(let i = 1; i <= 20; i++){
if(i%2 !== 0){
sum+=i;
}
}
console.log(sum)

```


