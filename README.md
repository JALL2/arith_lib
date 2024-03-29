## arith_lib: A set of functions for miscellaneous arithmetic calculation

### List of implemented functions

* **gcd(\*arg):**
Greatest common divisor of a set of integers

* **lcm(\*arg):**
Least common multiple of a set of integers

* **bezout(a, b):**
Provides a particular solution to diophantine equation a.u+b.v=gcd(a, b)

* **modulo_inv(a, b):**
Inverse of a modulo b

* **chinese_remainder(r, m):**
Solves the modular system:
   * x = r1 mod m1
   * x = r2 mod m2
   * ...
   * x = r_n mod m_n

* **gene_pseudo_prime():**
A generator which provides 2, 3, 5 and then all integers non multiple of 2, 3, 5

* **is_prime(n):**
Check for n primality. Miller-Rabin primality test is used

* **next_prime(n):**
Provides the first prime greater or equal to n

* **previous_prime(n)**
Provides the first prime smaller or equal to n

* **prime_factorization(n, frmt):**
Prime factorization of n
 
* **divisors(n):**
Provides all divisors of n

* **phi(n):**
Euler totient function

* **moebius(n):**
Moebius function

* **to_base(n, \*kwarg):**
Conversion from base 10 to base B

* **frobenius(\*A, n=None):**
Solves equation a1.x1 + a2.x2 + .. + ap.xp = n or finds
the greatest n for which this equation has no solution.
a1, a2, ... are positive integers.
x1, x2, ... are the unknowns, positive integers
	
* **isqrt(n)**
Provides the integer part of the square root of n
where n is an integer of any size

* **is_miller_rabin_witness(a, n)**
Return True if 'a' is a Miller-Rabin witness for n

* **get_random_prime(nbits, lessthan)**
Provides a random prime with exactly or at most 'nbits' bits

* **is_strong_pseudoprime(a, n)**
Return True is n is a strong pseudo prime to base 'a'


### Installation

pip install arith_lib


### Utilization

from arith_lib import \*

\>>> gcd(15, 20)
5




