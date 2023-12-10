# Math
Here I put the codes I write on some topics of mathematics.  
* There is no special topic or aim in the pattern of this project.  
* In below table the list of all available codes is brought.


| Item | File Name | Description | Link |
|:---------:|:--------:|:---------:|:---------:|
| 1 | find_primes.ipynb | Find list of all prime numbers not exeeding "n". Different Algorithms are implemented. | [link to Code](https://github.com/mohsenhy/Math/blob/main/find_primes.ipynb) |
| 2 |  |Fermat's Little Theorem |  |
| 3 |  |  |  |


# Fermat's Little Theorem

Fermat's Little Theorem states:

If `p` is a prime number, then for any integer `a` such that `a` is not divisible by `p`, the following equation holds true:  

$$
a^{p-1} \equiv 1 \pmod{p}
$$  

This means that `a` raised to the power of `p-1`, when divided by `p`, leaves a remainder of 1. The theorem essentially leverages the fact that when working modulo a prime number, the set of non-zero elements forms a mathematical structure known as a group under multiplication. In this group, every element except zero has a multiplicative inverse. Fermat's Little Theorem is a consequence of this group structure, stating that multiplying an element by itself 
�
−
1
p−1 times (where 
�
p is a prime) results in the multiplicative identity, which is 1 in modular arithmetic. The proof involves techniques from combinatorics and modular arithmetic, demonstrating that any number not divisible by a prime, when raised to one less than that prime, will always have a remainder of 1 when divided by that prime.

