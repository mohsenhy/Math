# Math
Here I put the codes I write on some topics of mathematics.  
* There is no special topic or aim in the pattern of this project.  
* In below table the list of all available codes is brought.


| Item |  Type   |                Name             | File Name | Description | Link |
|:----:|:-------:|:-------------------------------:|:---------:|:-----------:|:----:|
| 1    | code    | find_primes.ipynb               | Find list of all prime numbers not exeeding "n". Different Algorithms are implemented. | [link to Code](https://github.com/mohsenhy/Math/blob/main/find_primes.ipynb) |
| 2    | Theorem |  Fermat's Little Theorem        |                |
| 3    | code    | Summation                       |                |Summation in any base |  |
| 4    | code    | Subtraction                     |                |Subtraction in any base |  |
| 5    | code    | Multiplication            |                |Multiplication in any base  |  |
| 6    | code    | Division                  |                |Division in any base  |  |
| 7    | Theorem | Recurrent Sequence        |                |  |
| 8    |         |                           |                |  |
| 9    |         |                           |                |  |
| 10   |         |                           |                |  |
| 11   |         |                           |                |  |
| 12   |         |                           |                |  |
| 13   |         |                           |                |  |
| 14   |         |                           |                |  |
| 15   |         |                           |                |  |

##### *Finding Prime Numbers*

<blockquote>
  
Different methods can be used to identify prime numbers:
<blockquote>

  1. **Trial Division**: Check if a number `n` is divisible by any integer from 2 to the square root of `n`. If not, `n` is prime.
  2. **Sieve of Eratosthenes**: Efficiently finds all primes smaller than a given number `n` by marking multiples of each prime number starting from 2.
  3. **Primality Tests**: For large numbers, probabilistic tests like Miller-Rabin are used, which provide a high degree of confidence in primality but do not guarantee it.

Each method has its trade-offs between simplicity and efficiency, especially for large numbers.

</blockquote></blockquote>

##### *Fermat's Little Theorem*
<blockquote>
Fermat's Little Theorem states:
<blockquote>

If `p` is a prime number, then for any integer `a` such that `a` is not divisible by `p`, the following equation holds true:  

$$
a^{p-1} \equiv 1 \pmod{p}
$$  

This means that `a` raised to the power of `p-1`, when divided by `p`, leaves a remainder of 1.  
The theorem essentially leverages the fact that when working modulo a prime number, the set of non-zero elements forms a mathematical structure known as a group under multiplication. In this group, every element except zero has a multiplicative inverse. Fermat's Little Theorem is a consequence of this group structure, stating that multiplying an element by itself p−1 times (where p is a prime) results in the multiplicative identity, which is 1 in modular arithmetic. The proof involves techniques from combinatorics and modular arithmetic, demonstrating that any number not divisible by a prime, when raised to one less than that prime, will always have a remainder of 1 when divided by that prime.
</blockquote></blockquote>


##### *Recurrent Sequence*
<blockquote>
This theorem states:
<blockquote>

Any recurrent sequence is periodic to any modulus.

</blockquote>  
</blockquote>

