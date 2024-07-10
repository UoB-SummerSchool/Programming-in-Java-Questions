# EulerQuestions

[Problem 1](https://projecteuler.net/problem=1)
If we list all the natural numbers below $10$ that are multiples of $3$ or $5$, we get $3, 5, 6$ and $9$. The sum of these multiples is $23$.
Find the sum of all the multiples of $3$ or $5$ below $1000$.

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


