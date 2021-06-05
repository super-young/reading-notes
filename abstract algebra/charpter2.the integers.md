# The Integers
## 2.1 Mathematical Induction
+ Principle 2.1 - First Principle of Mathematical Induction:
  Let S(n) be a statement about integers for n $\in$ N and suppose S(n<sub>0</sub>) is true for some n<sub>0</sub>
  ,if for all integers with k>=n<sub>0</sub> , S(k) implies S(k+1) is true , then S(n) is true for all integers greater than or equals to n<sub>0</sub>

  ### this principle can be used to prove a statement true 
+ **Principle 2.1 - Second Principle of Mathematical Induction:**
  Let s(n) be a statement about integers for n $\in$ N and suppose s(n<sub>0</sub>) ,s(n<sub>0</sub>+1) ...S(k) implies S(K+1) for k >= n<sub>0</sub>, then S(n) is true for all integers greater than or equals to n<sub>0</sub>

+ **Definition of Well-Ordered** : A nonempty set is **well-ordered** if it contains a least number.
+ **Principle 2.6 - Principle of Well-Ordering:** every noempty set of natural number is well-ordered.(Equivalent to The Principle of Matchmatical Induction).
+ **Lemma 2.7** : The Principle of Mathematical Induction implies that 1 is the least postive natural number.
+ **Theroem 2.8** : The Principle of Mathematical Induction implies the Principle of Well-Ordering, that is every nonempty set of natural number is well-ordered.
+ **Tips** : Induction can also be very useful in formulating definitions. For instance, two way of define n!,
  - explicit definition: n! = 1 $\cdot$ 2 $\cdot$ 3 $\cdot$ 4 $\cdot$$\cdot$$\cdot$ n
  - implicit definition: 1! = 1 and n! = (n-1)! $\cdot$ n for n > 1
## 2.2 The Division Algrithm

+ **Theroem 2.9** Division Algrithm. Let a and b be integers with b > 0, there exists unique intgers q and r such that a = bq + r, where 0 <= r < b.
+ **Definition of Greatest Common Divisor:** . Let a and b be integers, we write a | b if a = bk for some integer k. An integer d is called a common divisor of a and b if d|a and d|b. The greatest common divisor of integers a and b is a postive integer d such that d is a common divisor of a and b and if there exists any d<sup>'</sup> is a common divisor of a and b, d = d<sup>'</sup> $\cdot$ k for some integer k(d<sup>'</sup>|d), denoted by d = gcd(a,b).Two integers a and b are reletively prime if gcd(a,b) = 1. The greatest common divisor of integers a and b is unique.
+ **Theroem 2.10** Let a and b be nonzero integers ,then there exists integers s and q such that 
   gcd(a,b) = ar+bs
+ **Corollary 2.11** Let a and b be are relatively prime integers, then there exists integers s and q such that ar+bs = 1
+ **Prime Numbers**: Let p be an integer such that p > 1, we say that p is prime if the only positive numbers divide p are 1 and itself. An integer is not prime is said to be compositive.
+ **Lemma 2.13** Euclid. Let a and b be integers and p be a prime number,if p|ab then either p|a or p|b.
+ **Theroem 2.14** Euclid. There exists only infinite number of primes.
+ **Theroem 2.15** Fundamental Theroem of Arithmetic. Let n be  an integer such that n > 1. Then n = p<sub>1</sub> $\cdot$ p<sub>2</sub> $\cdot$ $\cdot$ $\cdot$p<sub>k</sub>, where p<sub>1</sub> ...p<sub>k</sub> are primes (not necessarily distinct). Furthermore, this factorization is unique; that is if n = q<sub>1</sub> $\cdot$ q<sub>2</sub> $\cdot$ $\cdot$ $\cdot$q<sub>l</sub> then k = l and p<sub>i</sub>'s are just the p<sub>i</sub>'s rearranged.
+ 