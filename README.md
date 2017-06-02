# Marathon Functions

![Karlie](karlie-run.jpg)

Karlie is training for the New York Marathon this year, and she needs your help! In this lab, you'll be building javascript functions to help calculate pace, distance, travel time, and more. Good luck!

## Instructions

You'll be writing javascript functions inside of `marathon_functions.js` - each function will perform a different task to help Karlie with her training! Remember that a marathon is 26.2 Miles of running!

+ Create a function called timeToDecimal() that takes in three integers (hours, minutes, seconds) and converts this to decimal number of hours. For example:

```js
timeToDecimal(0,30,0) // 0 hours, 30 minutes, 0 seconds
//RETURNS 0.5

timeToDecimal(1,45,30) // 1 hour, 45 minutes, 30 seconds
//RETURNS 1.7583 (round to four decimal places)

timeToDecimal(4,15,12) // 4 hours, 15 minutes, 12 seconds
//RETURNS 4.2528
```

+ Now for the opposite: Create a function called decimalToTime() that takes in one argument, the time in hours as a decimal, and converts this to hours, minutes, and seconds. Return For example:

+ Create a function calculateMarathonTime() that takes in the pace per mile as two integers and returns the total amount of time the marathon will take to complete (this should also return a string that says "Expected Marathon time 4:")
