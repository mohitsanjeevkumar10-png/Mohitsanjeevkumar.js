# Mohitsanjeevkumar.js

let a = 15, b = 4;
console.log("Addition:", a + b);
console.log("Subtraction:", a - b);
console.log("Multiplication:", a * b);
console.log("Division:", a / b);
console.log("Modulus:", a % b);

let a = 10, b = 20;
console.log("a > b:", a > b);
console.log("a < b:", a < b);
console.log("a == b:", a == b);
console.log("a != b:", a != b);

let x = true, y = false;
console.log("x && y:", x && y);
console.log("x || y:", x || y);
console.log("!x:", !x);

let num = 10;
if (num > 0) {
    console.log("The number is positive.");
}

let num = 7;
if (num % 2 === 0) {
    console.log("Even number.");
} else {
    console.log("Odd number.");
}

let age = 18;
if (age >= 18) {
    console.log("Eligible to vote.");
} else {
    console.log("Not eligible to vote.");
}

let num = -5;
if (num > 0) {
    console.log("Positive");
} else if (num < 0) {
    console.log("Negative");
} else {
    console.log("Zero");
}

let marks = 82;
if (marks >= 90) {
    console.log("Grade: A");
} else if (marks >= 75) {
    console.log("Grade: B");
} else if (marks >= 60) {
    console.log("Grade: C");
} else {
    console.log("Grade: Fail");
}

let a = 12, b = 25;
if (a > b) {
    console.log("Largest is:", a);
} else {
    console.log("Largest is:", b);
}

let year = 2024;
if ((year % 4 === 0 && year % 100 !== 0) || (year % 400 === 0)) {
    console.log("Leap Year");
} else {
    console.log("Not a Leap Year");
}

for (let i = 1; i <= 10; i++) {
    console.log(i);
}

let num = 5;
for (let i = 1; i <= 10; i++) {
    console.log(`${num} x ${i} = ${num * i}`);
}

let n = 10;
let sum = 0;
for (let i = 1; i <= n; i++) {
    sum += i;
}
console.log("Sum:", sum);

for (let i = 2; i <= 50; i += 2) {
    console.log(i);
}

let count = 0;
for (let i = 1; i <= 100; i++) {
    if (i % 3 === 0) {
        count++;
    }
}
console.log("Count:", count);

let a = 10, b = 45, c = 25;
let largest = Math.max(a, b, c);
console.log("Largest number is:", largest);


let num = 15;
if (num % 3 === 0 && num % 5 === 0) {
    console.log("Divisible by both 3 and 5");
} else {
    console.log("Not divisible by both");
}

let n = 5;
let factorial = 1;
for (let i = 1; i <= n; i++) {
    factorial *= i;
}
console.log("Factorial:", factorial);

for (let i = 50; i >= 1; i--) {
    console.log(i);
}

let oddSum = 0;
for (let i = 1; i <= 100; i += 2) {
    oddSum += i;
}
console.log("Sum of odd numbers:", oddSum);



