#Project Euler: Problem 1: Multiples of 3 and 5

###Find the sum of all the multiples of 3 or 5 below the provided parameter value number.


```javascript
function multiplesOf3and5(number) {
  // Good luck!
  let i = 0;
  let n;
  let sum = 0;
  while (i < number) {
    if (Math.floor(i/3) === i/3 | Math.floor(i/5) === i/5) {
      sum = sum +i;
      i++;
      }
    else {
      i++;
    }
  }
return sum;
}

multiplesOf3and5(1000);
```
