# Project Euler Questions 

## [Problem 1](https://projecteuler.net/problem=1)
If we list all the natural numbers below $10$ that are multiples of $3$ or $5$, we get $3, 5, 6$ and $9$. The sum of these multiples is $23$.
Find the sum of all the multiples of $3$ or $5$ below $1000$.

You might want to approach this by considering the sum of an arithmetic progression or by iterating from 1 to 1000 and adding the current number to the total if it is divisable by either 3 or 5.

<details>
    <summary>Hint 1 - using arithmetic progression formula</summary>
    Since we need to find the sum of all multiples, it would make sense to list out all the
	multiple of a number in a sequence. Since it is a sequence, we can discuss as to what type
	of sequence it is. This one turns out to be an arithmetic progression. The sum of an A.P is
	n*(2*a + (n-1)*d)/2 where 'n' is the number of terms, 'a' is the first term of the series
	and 'd' is the difference between any two consecutive terms of the sequence.
	Use the formula of sum of arithmetic progressions and add the progressions of 3 and 5 
	and subtract the common progression once from them i.e the progression of 15. This gives us
	the sum of all the multiples of both 5 and 3.
</details>

<details>
<summary>Hint 2 - handy if statement for loop solution</summary>
	
```Java
if (i % 3 == 0 || i % 5 == 0){...}
```
</details>

=======================================================================================
## [Problem 2](https://projecteuler.net/problem=2)
Each new term in the Fibonacci sequence is generated by adding the previous two terms. By starting with $1$ and $2$, the first $10$ terms will be:
$$1, 2, 3, 5, 8, 13, 21, 34, 55, 89, \dots$$

By considering the terms in the Fibonacci sequence whose values do not exceed four million, find the sum of the even-valued terms.

<details>
<summary>Hint 1 - initialise variables</summary>
	
```Java
int sum = 0;
int x = 1;  // Represents the current Fibonacci number being processed
int y = 2;  // Represents the next Fibonacci number in the sequence
```
</details>

<details>
<summary>Hint 2 - While loop is handy here</summary>
	
```Java
while (x <= 4000000) {...}
```
</details>

<details>
<summary>Hint 3 - Use modulus operator ('%') to check for even numberss</summary>
	
```Java
if (x % 2 == 0)
```
</details>

=======================================================================================
