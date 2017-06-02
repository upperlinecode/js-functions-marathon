# Marathon Functions

![Karlie](karlie-run.jpg)

Karlie is training for the New York Marathon this year, and she needs your help! In this lab, you'll be building javascript functions to help calculate pace, distance, travel time, and more. Good luck!

## Instructions

Fork and clone this lab, and then cd into the lab directory. Run `npm install` to install the needed dependencies. Open `index.html` to see the tests, and follow along with the instructions below to get them to pass.

You'll be writing javascript functions inside of `marathon_functions.js` - each function will perform a different task to help Karlie with her training! Remember that a marathon is 26.2 Miles of running!

+ Create a function called `timeToDecimal()` that takes in a string with hours, minutes and seconds, and converts this to decimal number of hours. For example:

```js
timeToDecimal("0:30:0") // 0 hours, 30 minutes, 0 seconds
//RETURNS 0.5

timeToDecimal("1:45:30") // 1 hour, 45 minutes, 30 seconds
//RETURNS 1.7583 (round to four decimal places)

timeToDecimal("4:15:12") // 4 hours, 15 minutes, 12 seconds
//RETURNS 4.2528
```

+ Now for the opposite: Create a function called `decimalToTime()` that takes in one argument, the time in hours as a decimal, and converts this to hours, minutes, and seconds. Return For example:

```js
decimalToTime(0.75)
//returns "00:45:00"

decimalToTime(1.7583)
//returns "01:45:30"

decimalToTime(4.25)
//returns "04:15:00"
```

(You'll want to use those two functions as part of the next few)

+ Create a function `paceToMarathonTime()` that takes in the pace per mile and returns the total amount of time the marathon will take to complete (this should return a string that says "Expected Marathon time 4:25:13")

```js
paceToMarathonTime("00:08:15")
//returns "Expected marathon time 03:36:09"

paceToMarathonTime("00:09:18")
//returns "Expected marathon time 04:03:39"

paceToMarathonTime("00:11:12")
//returns "Expected marathon time 04:53:26"
```

+ Perhaps Karlie is trying to run her race under a certain time. If so, she'll need to know her pace per mile. Create a function `marathonToPacePerMile()` that takes in a total marathon time and returns the pace per mile to hit that time:

```js
marathonToPacePerMile("04:20:02")
//returns "Pace time 09:55"

marathonToPacePerMile("03:33:12")
//returns "Pace time 08:08"
```
## Bonus
*There are no tests for this bonus*
Find out the distance covered in each NYC Borough for the NYC marathon. Create a function `paceInBoroughToTime()` that takes in the name of the borough and the running pace. The function should return the total time that the runner will be in that borough

## Concepts to Google

+ Rounding in javascript
+ Splitting a string up into an array
+ Converting strings into integers
