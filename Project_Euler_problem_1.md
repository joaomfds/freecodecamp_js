#Project Euler: Problem 1: Multiples of 3 and 5

###Find the sum of all the multiples of 3 or 5 below the provided parameter value number.


```javascript
function multiplesOf3and5(number) {
  // Good luck!

  //Firstly we need to loop through each number from zero until our given number
  let i = 0;
  let n;
  let sum = 0;
  while (i < number) 
  //For each of these numbers we need to verify if it is a multiple of 3 or 5
    {
    if (Math.floor(i/3) === i/3 | Math.floor(i/5) === i/5) 
      {
        //If it's a multiple of 3 or 5 we add it to our sum and check the next number
      sum = sum +i;
      i++;
      }
    else {
      //If it's not a multiple of 3 or 5 we check the next number
      i++;
    }
  }
return sum;
}

multiplesOf3and5(1000);
```
