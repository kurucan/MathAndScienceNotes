# UC Irvine Statistics 131A - Michael C. Cranston Summer 2013


[UC Irvine:  Introduction to Probability and Statistics](http://ocw.uci.edu/courses/math_131a_introduction_to_probability_and_statistics.html)

[Lecture 1](#lecture-1) | [Lecture 2](#lecture-2) | [Lecture 3](#lecture-3) | [Lecture 4](#lecture-4) | [Lecture 5](#lecture-5) | [Lecture 6](#lecture-6) | [Lecture 7](#lecture-7) | [Lecture 8](#lecture-8) | [Lecture 9](#lecture-9) | [Lecture 10](#lecture-10) | [Lecture 11](#lecture-11) | [Lecture 12](#lecture-12) | [Lecture 13](#lecture-13) | [Lecture 14](#lecture-14) | [Lecture 15](#lecture-15) | [Lecture 16](#lecture-16) |

## Lecture 1
- [Video](https://youtu.be/GyN4FotAEt8)
### [12:20](https://youtu.be/GyN4FotAEt8?t=12m20s) Sample Spaces
- Defines the possible outcomes in an experiment
- Ω
### [26:43](https://youtu.be/GyN4FotAEt8?t=26m43s) Events
#### [28:00](https://youtu.be/GyN4FotAEt8?t=28m00s) Example: Three Heads when Tossing a Coin 6 Times
#### [32:00](https://youtu.be/GyN4FotAEt8?t=32m00s) Example: Straight Flush
#### [38:00](https://youtu.be/GyN4FotAEt8?t=38m00s) Example: k Successes Observed
#### [41:00](https://youtu.be/GyN4FotAEt8?t=41m00s) Union ∪/Intersection ∩/A-B (A \ B)/ of Two Events
- [43:00](https://youtu.be/GyN4FotAEt8?t=43m00s) A complement - Ac
- [45:12](https://youtu.be/GyN4FotAEt8?t=45m12s) Symmetric Difference of A and B
- [47:10](https://youtu.be/GyN4FotAEt8?t=47m10s) Assigning Probability to Events
### [49:45](https://youtu.be/GyN4FotAEt8?t=49m45s) Mutually Disjoint
- [51:54](https://youtu.be/GyN4FotAEt8?t=51m54s) Empty Set is an event with Probability of zero
- [53:58](https://youtu.be/GyN4FotAEt8?t=53m58s) P(A Complement) = 1 - P(A)
- [56:30](https://youtu.be/GyN4FotAEt8?t=56m30s) P(A) ≤ P(B), A subset B, A ⊆ B
 - [1:02:00](https://youtu.be/GyN4FotAEt8?t=1h2m) Counting
- [1:05:29](https://youtu.be/GyN4FotAEt8?t=1h5m29s) P(A) = #A/#Omega (Ω) Definition of Prob?
- [1:08:45](https://youtu.be/GyN4FotAEt8?t=1h8m45s) Derive above - All n disjoint events have same probability
- [1:14:25](https://youtu.be/GyN4FotAEt8?t=1h14m25s) Multiplication Principle: m x n ways
#### [1:17:45](https://youtu.be/GyN4FotAEt8?t=1h17m45s) Example: Select 3 people without replacement, ordered
#### [1:20:25](https://youtu.be/GyN4FotAEt8?t=1h20m25s) Example: Select people with replacement, and ordering
#### [1:21:32](https://youtu.be/GyN4FotAEt8?t=1h21m32s) Example: Committee of size 5 - consider over counting - Permutations
- [1:24:00](https://youtu.be/GyN4FotAEt8?t=1h24m) Permutations - n!
#### [1:27:00](https://youtu.be/GyN4FotAEt8?t=1h27m) Example: Select r objects from set of n without replacement Derived n! / (n-r)!r!
- [1:31:35](https://youtu.be/GyN4FotAEt8?t=1h31m35s) Find P(full house)
- [1:40:07](https://youtu.be/GyN4FotAEt8?t=1h40m7s) Find P(flush) - all cards of same suit


## Lecture 2
- [Video](https://youtu.be/zboOPK98aGk)
- Maximum Likelihood Estimator
- [1:50](https://youtu.be/zboOPK98aGk?t=1m50s) f(n+1)/f(n) > 1, when it stops being > 1, we have our estimator
### [12:00](https://youtu.be/zboOPK98aGk?t=12m) Discussion: Multinomial Theorem
- [16:18](https://youtu.be/zboOPK98aGk?t=16m18s) Multi-nomial coefficient
- [17:45](https://youtu.be/zboOPK98aGk?t=17m45s) Multinomial Thereom Definition
- [19:30](https://youtu.be/zboOPK98aGk?t=19m30s) Poker Example: 6 people, 5 cards each
- [22:20](https://youtu.be/zboOPK98aGk?t=22m20s) Number possible Bridge hands
- [23:30](https://youtu.be/zboOPK98aGk?t=23m30s) Misc Examples
### [25:00](https://youtu.be/zboOPK98aGk?t=25m) Conditional probability and independence
- P(A|B)=P(A intersect B)/P(B) - 
#### [26:30](https://youtu.be/zboOPK98aGk?t=26m30s) Example: Roll fair dice... P(roll six|dice is even)
- [30:30](https://youtu.be/zboOPK98aGk?t=30m30s) Law of Total Probability
#### [34:20](https://youtu.be/zboOPK98aGk?t=34m20s) Example: Urn Problem with Gumballs
#### [51:50](https://youtu.be/zboOPK98aGk?t=51m50s) Bayes Rule
#### [58:00](https://youtu.be/zboOPK98aGk?t=58m) Independence
#### P(A intersect B) = P(A)*P(B)
- [58:45](https://youtu.be/zboOPK98aGk?t=58m45s) Given independence, P(A|B) = P(A)
- First toss of coin does not affect second toss - no memory 
- [1:00:45](https://youtu.be/zboOPK98aGk?t=1h0m45s) Example: Toss Two Coins
- Consecutive rolls of dice are independent
#### [1:05:55](https://youtu.be/zboOPK98aGk?t=1h5m55s) Example: Dart Thrown Repeatedly, probability get at least one bullseye
- Use complement to get answer: Probability not hit a bullseye 

## Lecture 3
- Random Variables [Video](https://youtu.be/Pj5n3FLE0wM)
- Problem 74 - 
### [8:08](https://youtu.be/Pj5n3FLE0wM?t=8m08s) Random Variables r.v.s.- Assign values to outcomes
- Random/Chance Variables - Joe Doob, William Feller - tossed a coin to get name
#### [10:45](https://youtu.be/Pj5n3FLE0wM?t=10m45s) Example:
- [14:05](https://youtu.be/Pj5n3FLE0wM?t=14m05s) RV is a function on a sample space with real values
- [16:00](https://youtu.be/Pj5n3FLE0wM?t=16m) F(x)=P(X≤x)
- [16:40](https://youtu.be/Pj5n3FLE0wM?t=16m40s) 0≤ F(x) ≤ 1 - Another way of saying probabilities between 0 and 1
- [18:10](https://youtu.be/Pj5n3FLE0wM?t=18m10s) F(x) - P(X≤x) ≤ P(Y≤y) = F(y)
- F is a non-decreasing function (increasing, but not strictly)
- [21:00](https://youtu.be/Pj5n3FLE0wM?t=21m) F is right continuous
- [21:45](https://youtu.be/Pj5n3FLE0wM?t=21m45s) Distribution Function
- (e.g. Normal, Uniform,Poisson)
### [22:45](https://youtu.be/Pj5n3FLE0wM?t=22m45s) Two major classes of rvs
- Discrete - distribution function has jumps interrupted by flat spots
- [25:05](https://youtu.be/Pj5n3FLE0wM?t=25m05s) Continuous - distribution function is continuous
#### [26:15](https://youtu.be/Pj5n3FLE0wM?t=26m15s) Examples of Discrete r.v.
### Cumulative distribution function - CDF
### [27:45](https://youtu.be/Pj5n3FLE0wM?t=27m45s) Bernoulli Distribution/RV
- P(X=0) = 1-p
- P(X=1) = p
### [31:35](https://youtu.be/Pj5n3FLE0wM?t=31m35s) Binomial R.V.
- n independent Bernoulli trials are performed 
- X is # successes in n trials
- X will be number b/w 0 and n
- [38:00](https://youtu.be/Pj5n3FLE0wM?t=38m) PMF - probability mass function
- PMF to Distribution function - summation 
- [42:00](https://youtu.be/Pj5n3FLE0wM?t=42m) Jump size is equal to PMF at a given integer
#### [42:30](https://youtu.be/Pj5n3FLE0wM?t=42m30s) Example: Geometric Random Variable
- Perform independent Bernoulli trials until a success occurs
- eg. Toss a coin until heads/roll a die until 3
- [46:10](https://youtu.be/Pj5n3FLE0wM?t=46m10s) P(X=k) = (1-p)^k-1 * p
#### [50:00](https://youtu.be/Pj5n3FLE0wM?t=50m) Negative Binomial
- Perform Bernoulli trials until r successes occur 
- PMF: 
- [54:15](https://youtu.be/Pj5n3FLE0wM?t=54m15s)? CMF:
#### [55:54](https://youtu.be/Pj5n3FLE0wM?t=55m54s) Poisson Distribution/RV
- parameter λ (lambda)
- Used in counting where there are a large number of events, each with a small probability 
- [1:00:08](https://youtu.be/Pj5n3FLE0wM?t=1h0m8s) Relationship of Poisson to Binomial
- [1:04:35](https://youtu.be/Pj5n3FLE0wM?t=1h04m35s) Used L’Hospital’s Rule
- [1:15:45](https://youtu.be/Pj5n3FLE0wM?t=1h15m45s) General Solution
- Large trials with a small probability of success- Bernoulli RV is almost like a Poisson RV
### [1:18:55](https://youtu.be/Pj5n3FLE0wM?t=1h18m55s) Continuous random variables
- Law of Rare Events mentioned [aka Poisson distribution](https://en.wikipedia.org/wiki/Poisson_distribution)
- [1:20:25](https://youtu.be/Pj5n3FLE0wM?t=1h20m25s) If F has a derivative f, then (mostly true) little f is called density of capital F or of X.
- aka Probably Density Function 
#### [1:22:01](https://youtu.be/Pj5n3FLE0wM?t=1h22m1s) Example: The uniform on [0,1] r.v. U([0,1]) has density...
- [1:26:10](https://youtu.be/Pj5n3FLE0wM?t=1h26m10s) P(a<X≤b) = P(X≤b) - P(X≤a)
- Integrate from a to b
- [1:29:55](https://youtu.be/Pj5n3FLE0wM?t=1h29m55s) Normal Random Variable
#### [1:30:28](https://youtu.be/Pj5n3FLE0wM?t=1h30m28s) Example: X~N( u,sigma^2)
  - normal, mean u, variance sigma^2
  - [1:31:38](https://youtu.be/Pj5n3FLE0wM?t=1h31m38s) density is given by ...
- [1:32:15](https://youtu.be/Pj5n3FLE0wM?t=1h32m15s) if X~N(0,1) then ...
- [1:32:55](https://youtu.be/Pj5n3FLE0wM?t=1h32m55s) P(-infinity,X , infinity)
- Integral should be 1
- Can’t integrate - squaring...
- [1:37:40](https://youtu.be/Pj5n3FLE0wM?t=1h37m40s) Switch to polar coordinates
- [1:40:08](https://youtu.be/Pj5n3FLE0wM?t=1h40m08s) If X is Bin(n,1/2) - like tossing coin and counting heads
- When n is large, it is essentially a Normal Random Variable - Central Limit Theorem 

## Lecture 4
- Joint Distribution - [Video](https://youtu.be/BV7xnuJNkSQ)
- Bernoulli Random Variables led to most other rvs studied in the course  [5:40](https://youtu.be/BV7xnuJNkSQ?t=5m40s)
- PMF: Probability Mass Function of Bernoulli [6:01](https://youtu.be/BV7xnuJNkSQ?t=6m01s)
- Bernoulli led to Binomial [7:32](https://youtu.be/BV7xnuJNkSQ?t=7m32s)
- Bernoulli led to Geometric Distribution [10:54](https://youtu.be/BV7xnuJNkSQ?t=10m54s)
  - Distribution function [12:29](https://youtu.be/BV7xnuJNkSQ?t=12m29s)
- Bernoulli led to Poisson Distribution [13:04](https://youtu.be/BV7xnuJNkSQ?t=13m04s)
- Bernoulli led to Normal Distribution [15:01](https://youtu.be/BV7xnuJNkSQ?t=15m01s)
### Geometric Example [17:21](https://youtu.be/BV7xnuJNkSQ?t=17m21s)
- Probability that you have to wait k more trails
- Result is that it’s like starting at the beginning [30:30](https://youtu.be/BV7xnuJNkSQ?t=30m30s)
  - You are NOT due!

### Continuous Random Variables [31:50](https://youtu.be/BV7xnuJNkSQ?t=31m50s)
- Can have flat spots but no jumps [33:55](https://youtu.be/BV7xnuJNkSQ?t=33m55s)
#### Discussion: Exponential RV with parameter λ [33:08](https://youtu.be/BV7xnuJNkSQ?t=33m08s)
- Exponential RV with parameter λ are used to model waiting times eg bus, phone call [37:29](https://youtu.be/BV7xnuJNkSQ?t=37m29s)
- Same start over property as geometric [38:40](https://youtu.be/BV7xnuJNkSQ?t=38m40s)
#### Gamma function - closely related to exponential [41:55](https://youtu.be/BV7xnuJNkSQ?t=41m55s)
- integrate by parts
- Gamma(n)=(n-1)! [46:40](https://youtu.be/BV7xnuJNkSQ?t=46m40s)
  - Discussion: ...to find density [47:30](https://youtu.be/BV7xnuJNkSQ?t=47m30s)
  - Waiting until n occurrence [50:50](https://youtu.be/BV7xnuJNkSQ?t=50m50s)
  - Finishing Gamma Random Variable [51:34](https://youtu.be/BV7xnuJNkSQ?t=51m34s)

### Functions of Random Variables [56:55](https://youtu.be/BV7xnuJNkSQ?t=56m55s)
- A function of a rv is a rv [58:40](https://youtu.be/BV7xnuJNkSQ?t=58m40s)
- The distribution function of the new rv is P(g(X)≤x)
- If g(X) is decreasing... [1:04:40](https://youtu.be/BV7xnuJNkSQ?t=1h4m40s)
#### Example: Find P(Y≤x), given Y=...[1:10:15](https://youtu.be/BV7xnuJNkSQ?t=1hms)
- Density of distribution function is its derivative [1:13:54](https://youtu.be/BV7xnuJNkSQ?t=1h13m54s)

### Joint Distributions [1:25:30](https://youtu.be/BV7xnuJNkSQ?t=1h25m30s)
- eg. Shoe size father/son
- Joint PMF [1:31:20](https://youtu.be/BV7xnuJNkSQ?t=1h31m20s)
- We say (X,Y) has joint distribution function F if P(X≤x,Y≤y)=F(x,y) [1:34:38](https://youtu.be/BV7xnuJNkSQ?t=1h34m38s)
- Continuous Random Variable Case [1:36:35](https://youtu.be/BV7xnuJNkSQ?t=1h36m35s)
#### Example: [1:37:20](https://youtu.be/BV7xnuJNkSQ?t=1h37m35s)


## Lecture 5
- Expected Values - [Video](https://youtu.be/UdJr5xO5XzI)
### Jointly Distributed Random Variables [1:36](https://youtu.be/UdJr5xO5XzI?t=1m36s)
#### Example: (X,Y) is uniformly distribute on ...[5:40](https://youtu.be/UdJr5xO5XzI?t=5m40s)
- What does it mean that Z is uniformly distributed on interval [a,b]? [7:09](https://youtu.be/UdJr5xO5XzI?t=7m9s)
  - Means the density is equal to 1/length of interval if z is in interval, otherwise 0
  - Density is constant on interval
- [16:35](https://youtu.be/UdJr5xO5XzI?t=16m35s) Marginal Distributions 
  - When you have the joint distribution of X and Y, you can retrieve the individual distributions of X and Y.
  - Just integrate out the other variable. Take other var to infinity
#### [40:54](https://youtu.be/UdJr5xO5XzI?t=40m54s) Discussion: From a joint distribution function F(x,y) at (X,Y), we can retrieve the marginal distribution functions ... 
### [46:40](https://youtu.be/UdJr5xO5XzI?t=46m40s) Example: Suppose we have a pair of rvs and their joint density is...Find marginal densities of X and Y
- Integrate out one variable at a time
- [54:40](https://youtu.be/UdJr5xO5XzI?t=54m40s) Conditional Densities
- [56:50](https://youtu.be/UdJr5xO5XzI?t=56m50s) Discrete case: Joint probability mass function /Marginal
- [57:25](https://youtu.be/UdJr5xO5XzI?t=57m25s) Compute conditional densities for the example
- [58:30](https://youtu.be/UdJr5xO5XzI?t=58m30s) Integral sign stands for letter S
#### [1:10:15] Example: 3 coins in an urn
- [1:13:45](https://youtu.be/UdJr5xO5XzI?t=1h13m45s) Compute the Marginal Distributions
- X is the coin drawn
- Y = heads or tails
- PMF for X - fix X then sum over 2nd variable
- Marginal for Y - fix little y then sum over other variables
- [1:17:57](https://youtu.be/UdJr5xO5XzI?t=1h17m57s) Conditional Distributions
### [1:22:18](https://youtu.be/UdJr5xO5XzI?t=1h22m18s) Joint Normal Distribution
- (X,Y) has a joint normal distribution if its density is ...
- [1:29:45](https://youtu.be/UdJr5xO5XzI?t=1h29m45s) Independence for jointly distributed rvs: X,Y are independent if...


## Lecture 6
- [Video](https://www.youtube.com/watch?v=IGRl1PKevT4)
### Joint Distribution Review 

- [2:40](https://youtu.be/IGRl1PKevT4?t=2m40s) Densities or PMF’s
- [5:00](https://youtu.be/IGRl1PKevT4?t=5m0s) Conditional PMF’s and Densities
- [6:15](https://youtu.be/IGRl1PKevT4?t=6m15s) Independence
- [7:30](https://youtu.be/IGRl1PKevT4?t=7m30s) if the joint distribution factors into the product of the marginals then we say the random variables are independent
- [8:30](https://youtu.be/IGRl1PKevT4?t=8m30s) Can check for independence if you have the PMF or joint density
- [9:25](https://youtu.be/IGRl1PKevT4?t=9m25s) if the probability mass functions factor into the product of PMF’s then rvs are independent
- In continuous case, if joint density factors then rvs are independent 
- 
### [10:25](https://youtu.be/IGRl1PKevT4?t=10m25s) Sum of Random Variables
- [12:30](https://youtu.be/IGRl1PKevT4?t=12m30s) What’s the PMF of X+Y?
- PMF of P(X+Y=z) is itself a rv
- [14:30](https://youtu.be/IGRl1PKevT4?t=14m30s) If X & Y are independent then it factors - the Convolution
- #### [16:10](https://youtu.be/IGRl1PKevT4?t=16m10s) Example: Discrete case
- [22:20](https://youtu.be/IGRl1PKevT4?t=22m20s) Arrived at the binomial theorem
- #### [23:50](https://youtu.be/IGRl1PKevT4?t=23m50s) Example: A continuous case
- [34:05](https://youtu.be/IGRl1PKevT4?t=34m5s) Find density from the distribution
- [35:35](https://youtu.be/IGRl1PKevT4?t=35m35s) Special case where they are independent rvs
- [36:55](https://youtu.be/IGRl1PKevT4?t=36m55s) The convolution of F sub x and F sub y
#### [37:20](https://youtu.be/IGRl1PKevT4?t=37m20s) Example: ... find distribution of sum
- [49:19](https://youtu.be/IGRl1PKevT4?t=49m19s) ?? Reminder that integral of density is always 1
- [47:58](https://youtu.be/IGRl1PKevT4?t=47m58s) ?? So, it’s Normal with mean 0, variance 2
### [49:25](https://youtu.be/IGRl1PKevT4?t=49m25s) After Break
- Sum of two random variables is a special case of a function of two random variables
- ### [49:25](https://youtu.be/IGRl1PKevT4?t=49m25s) Distribution function for a ratio
- Another example of a function of two random variables
- [56:15](https://youtu.be/IGRl1PKevT4?t=56m15s) Example from book - It’s a Cauchy Distribution
### [57:55](https://youtu.be/IGRl1PKevT4?t=57m55s) You might have two functions ...
- [59:25](https://youtu.be/IGRl1PKevT4?t=59m25s) We can compute the density of two new rvs if we know the joint densities of the old ones, X & Y.
- Uses Jacobian 
#### [1:02:30](https://youtu.be/IGRl1PKevT4?t=1h2m30s) Example:
- [1:05:35](https://youtu.be/IGRl1PKevT4?t=1h5m35s) Invert matrix
- [1:08:20](https://youtu.be/IGRl1PKevT4?t=1h8m20s) Jacobian of transformation...
- Determinant is delta
- [1:09:25](https://youtu.be/IGRl1PKevT4?t=1h9m25s) Joint density of new rvs is ...
- [1:12:12](https://youtu.be/IGRl1PKevT4?t=1h12m12s) Simplify and identify rvs
- [1:15:45](https://youtu.be/IGRl1PKevT4?t=1h15m45s) Bivariate Normal
- [1:22:45](https://youtu.be/IGRl1PKevT4?t=1h22m45s) Every bivariate normal comes from linear transformation of independent normals of the form ...
#### [1:23:51](https://youtu.be/IGRl1PKevT4?t=1h23m51s) Example:
- [1:25:35](https://youtu.be/IGRl1PKevT4?t=1h25m35s) We’re just computing the distribution of polar coordinates of an independent normal means 0, variance  1 pair
- [1:27:20](https://youtu.be/IGRl1PKevT4?t=1h27m20s) Compute the Jacobian 
- [1:37:55](https://youtu.be/IGRl1PKevT4?t=1h37m55s) Find distribution of y/x

## Lecture 7
- Limit Theorems - [Video](https://youtu.be/r4R8aJE-BLo)
- [1:40](https://youtu.be/r4R8aJE-BLo?t=1m40s) Order Statistics
- Insurance claims
- Reorder sample so that X1 is largest. 
- If independent and identically distributed (iid) with distribution function...
- [8:28](https://youtu.be/r4R8aJE-BLo?t=8m28s) Independence: Joint distribution splits into product of individuals
- [10:45](https://youtu.be/r4R8aJE-BLo?t=10m45s) Finding the largest distribution function 
- [11:25](https://youtu.be/r4R8aJE-BLo?t=11m25s) If the largest is ≤ then they all are
- [12:50](https://youtu.be/r4R8aJE-BLo?t=12m50s) F(x)^n is distribution function for largest - Common distribution function to nth power
- [13:10](https://youtu.be/r4R8aJE-BLo?t=13m10s) The smallest rv ≤ x? Use complement 
- [17:18](https://youtu.be/r4R8aJE-BLo?t=17m18s) Reminder: Density is derivative of distribution function 
### [19:05](https://youtu.be/r4R8aJE-BLo?t=19m5s) Example: Exponential distributions
- Light bulbs burning out
- [24:25](https://youtu.be/r4R8aJE-BLo?t=24m25s) Density for maximum...
### [25:40](https://youtu.be/r4R8aJE-BLo?t=25m40s) Example:
- [27:10](https://youtu.be/r4R8aJE-BLo?t=27m10s) Density for largest 
- [28:18](https://youtu.be/r4R8aJE-BLo?t=28m18s) Density for the smallest 
- [29:02](https://youtu.be/r4R8aJE-BLo?t=29m2s) What’s the density for ith largest?
- [32:00](https://youtu.be/r4R8aJE-BLo?t=32m0s) Graph...
- Newton quotient 
- [40:45](https://youtu.be/r4R8aJE-BLo?t=40m45s) Equation ... answer?
### [41:35](https://youtu.be/r4R8aJE-BLo?t=41m35s) Example: The Uniform
- [42:25](https://youtu.be/r4R8aJE-BLo?t=42m25s) Density for ith largest
- [46:15](https://youtu.be/r4R8aJE-BLo?t=46m15s) Density of median
- [48:30](https://youtu.be/r4R8aJE-BLo?t=48m30s) Density gets concentrated?...graph
- [51:25](https://youtu.be/r4R8aJE-BLo?t=51m25s) Suppose i<j...
- e.g. quartiles
- [56:35](https://youtu.be/r4R8aJE-BLo?t=56m35s) Corrections after the break 
- [59:10](https://youtu.be/r4R8aJE-BLo?t=59m10s) Range: Largest minus smallest
- [59:43](https://youtu.be/r4R8aJE-BLo?t=59m43s) How can we find the distribution of the difference of two random variables?
- Need to know their joint distribution 
- [1:05:34](https://youtu.be/r4R8aJE-BLo?t=1h5m34s) Example: Uniform sample iid, joint density for pair ...
- [1:10:05](https://youtu.be/r4R8aJE-BLo?t=1h10m5s) Exercise: Find the density of ..
### [1:11:20](https://youtu.be/r4R8aJE-BLo?t=1h11m20s) Chapter 4: Expectations (integrals)
- Suppose X is a discrete r.v. with pdf p, define...
#### [1:14:45](https://youtu.be/r4R8aJE-BLo?t=1h14m45s) If X is Poisson with parameter λ distributed...
- [1:17:48](https://youtu.be/r4R8aJE-BLo?t=1h17m48s) Solution: Expected value of Poisson with parameter λ is λ
#### [1:18:20](https://youtu.be/r4R8aJE-BLo?t=1h18m20s) Example: Geometric Distribution
- [1:21:52](https://youtu.be/r4R8aJE-BLo?t=1h21m1s) Solution: E[X] = 1/p for geometric 
#### [1:25:01](https://youtu.be/r4R8aJE-BLo?t=1h25m1s) Continuous case for Expected Value
#### [1:27:20](https://youtu.be/r4R8aJE-BLo?t=1h27m20s) Example: Uniform
- Uniform: Given iid sample from Uniform, find E[X] of smallest, median, largest 
- [1:30:02](https://youtu.be/r4R8aJE-BLo?t=1h30m2s) There’s symmetry in problem
#### [1:37:15](https://youtu.be/r4R8aJE-BLo?t=1h37m15s) Example: Gamma distribution - E[X]
- Exponential decay wins so integral is finite
- [1:42:20](https://youtu.be/r4R8aJE-BLo?t=1h42m20s) Solution: E[X] = 1/λ


## Lecture 8
- Distributions from normal Distribution - [Video](https://youtu.be/yIn0h984TKg)

### Chapter 3: Problem 40
- [21:01](https://youtu.be/yIn0h984TKg?t=21m1s) We have the joint probability of the two by definition 
- [21:55](https://youtu.be/yIn0h984TKg?t=21m55s) That’s the Geometric series 
- [23:00](https://youtu.be/yIn0h984TKg?t=23m0s) We have the PMF is the conditional probability that we wanted
- ### [24:20](https://youtu.be/yIn0h984TKg?t=24m20s) Chapter 3: Problem 54
- [31:54](https://youtu.be/yIn0h984TKg?t=31m54s) Integrate over theta and phi to get density of R
- [36:45](https://youtu.be/yIn0h984TKg?t=36m45s) Choosing constant to normalize to 1
### [42:15](https://youtu.be/yIn0h984TKg?t=42m15s) Chapter 3: Problem 33B
- U[0,1]
- N is first time you get a head.  Geometric 
- E[X] = 1/p
- [46:45](https://youtu.be/yIn0h984TKg?t=46m45s) The frequency argument
- mu is used for mean because it’s the greek letter for m.
### [49:15](https://youtu.be/yIn0h984TKg?t=49m15s) Expected Value Review
### [52:15](https://youtu.be/yIn0h984TKg?t=52m15s) Example: Calculate the 3 expected values
- [55:35](https://youtu.be/yIn0h984TKg?t=55m35s) No integration required. The trick is...
- [59:20](https://youtu.be/yIn0h984TKg?t=59m20s) Part 2: Second Expected Value
- [1:05:50](https://youtu.be/yIn0h984TKg?t=1h5m50s) Solution: We get the variance: How far its square is from its average. 
- [1:07:48](https://youtu.be/yIn0h984TKg?t=1h7m48s) Part 3:
- Definition: var(X) for discrete and continuous cases
- [1:11:30](https://youtu.be/yIn0h984TKg?t=1h11m30s) Combine the exponentials
- [1:18:00](https://youtu.be/yIn0h984TKg?t=1h18m0s) The Moment Generating Function - Uniquely determine the distribution of the r.v.
### [1:20:20](https://youtu.be/yIn0h984TKg?t=1h20m20s) Example: Gamma Moment Generating Function 
- Don’t have to do integration with gammas
- [1:23:10](https://youtu.be/yIn0h984TKg?t=1h23m10s) Combine the exponential terms
- ### [1:24:48](https://youtu.be/yIn0h984TKg?t=1h24m48s) Expected Values: Jointly Distributed Random Variables
- ### [1:26:30](https://youtu.be/yIn0h984TKg?t=1h26m30s) Example
- [1:29:20](https://youtu.be/yIn0h984TKg?t=1h29m20s) If independent, expected value of product is the product of the individual expected values
### [1:29:49](https://youtu.be/yIn0h984TKg?t=1h29m49s) Example:
-  Compute moment generating function

## Lecture 9

[Video](https://youtu.be/lk-D9_XTbSc)
### Revisit moment generating function 
- Two different densities cannot give the same moment generating function 
### [1:45](https://youtu.be/lk-D9_XTbSc?t=1m45s) Moment generating function for Poisson
- PMF
- [2:30](https://youtu.be/lk-D9_XTbSc?t=ms) Calculate moment generating function
### [5:20](https://youtu.be/lk-D9_XTbSc?t=5m20s) Discussion: Suppose X,Y and independent r.v.  , what’s the momentary random function for the sum?
- [6:50](https://youtu.be/lk-D9_XTbSc?t=6m50s) It’s the product of the moment functions
### [7:08](https://youtu.be/lk-D9_XTbSc?t=7m8s) Example: Poisson
- [9:35](https://youtu.be/lk-D9_XTbSc?t=9m35s) Example: Bernoulli
- [11:35](https://youtu.be/lk-D9_XTbSc?t=11m35s) Example: Independent Bernoulli’s X1,...,Xn
- [22:00](https://youtu.be/lk-D9_XTbSc?t=22m0s) Now take p=1/2 then...
- [30:10](https://youtu.be/lk-D9_XTbSc?t=30m10s) Central Limit Theorem
- [31:25](https://youtu.be/lk-D9_XTbSc?t=31m25s) Called moment generating functions because if you differentiate once and evaluate at zero, you get the expected value...
- if you differentiate twice and evaluate at zero, you get the expected value of the square
### [32:47](https://youtu.be/lk-D9_XTbSc?t=32m47s) Discussion: Take ln (log) of moment generating function, then differentiate twice and evaluate at t=0
- [35:35](https://youtu.be/lk-D9_XTbSc?t=35m35s) We got the variance of X
### [36:00](https://youtu.be/lk-D9_XTbSc?t=36m0s) Example: 
- [37:00](https://youtu.be/lk-D9_XTbSc?t=37m0s) With Poisson 
- var(X)=lambda
- [38:40](https://youtu.be/lk-D9_XTbSc?t=38m40s) Example: Binomial
- [41:00](https://youtu.be/lk-D9_XTbSc?t=41m0s) Use moment generating function instead
- [43:10](https://youtu.be/lk-D9_XTbSc?t=43m10s) Have moment generating function for a Bernoulli with parameter p
- Binomial is same as sum of n independent Bernoulli’s with parameter p by uniqueness of moment generating functions 
- Calculate variance of binomial 
### [47:52](https://youtu.be/lk-D9_XTbSc?t=47m52s) Definition: Covariance
- [50:00](https://youtu.be/lk-D9_XTbSc?t=50m0s) If X,Y are independent then cov(X,Y)=0
- [55:55](https://youtu.be/lk-D9_XTbSc?t=55m55s) Variance of a sum = the sum of variances + twice the sum of the covariances
- [57:00](https://youtu.be/lk-D9_XTbSc?t=57m0s) If independent then Variance of a sum = the sum of variances 
### [58:20](https://youtu.be/lk-D9_XTbSc?t=58m20s) Variance of Binomial(n,p)
### [1:00:40](https://youtu.be/lk-D9_XTbSc?t=1h0m40s) Example:

## Lecture 10

Survey Sampling - [Video](https://youtu.be/srkdFzcjoS4)

### [1:10](https://youtu.be/srkdFzcjoS4?t=1m10s) Computations with Joint Normal Distributions
- [3:10](https://youtu.be/srkdFzcjoS4?t=3m10s) Compute Marginal Density
- [6:15](https://youtu.be/srkdFzcjoS4?t=6m15s) Complete the square in the exponent - Common technique in normals and joint normals
- [12:55](https://youtu.be/srkdFzcjoS4?t=12m55s) Arrive at marginal density for X
#### [14:16](https://youtu.be/srkdFzcjoS4?t=14m16s) Find the conditional density
- [16:55](https://youtu.be/srkdFzcjoS4?t=16m55s) Start simplifying the equation
- [24:30](https://youtu.be/srkdFzcjoS4?t=24m30s) Try to get it in form (x-mu)/sigma
- [26:20](https://youtu.be/srkdFzcjoS4?t=26m20s) One last step...
- [27:25](https://youtu.be/srkdFzcjoS4?t=27m25s) Solution: normal, with mean...
- [28:25](https://youtu.be/srkdFzcjoS4?t=28m25s) Observation: Joint normals are independent if and only if rho is zero
### [29:01](https://youtu.be/srkdFzcjoS4?t=29m1s) Conditional Expectations
- Are expectations using conditional PMF’s or conditional densities 
- Discrete
- Continuous
### [30:45](https://youtu.be/srkdFzcjoS4?t=30m45s) Example: Conditional Expectation of a Normal
### [31:10](https://youtu.be/srkdFzcjoS4?t=31m10s) Example: If (X,Y) is joint normal, compute E[X|Y=y]...
- [36:08](https://youtu.be/srkdFzcjoS4?t=36m8s) Marginal distribution of X
### [37:15](https://youtu.be/srkdFzcjoS4?t=37m15s) Example: Find conditional expectation for E[U|V=v]
- Need conditional density: Need joint and marginal densities to get this
- [38:50](https://youtu.be/srkdFzcjoS4?t=38m50s) Find joint density
- Jacobian
- [44:25](https://youtu.be/srkdFzcjoS4?t=44m25s) Conditional density of U given V
- [46:24](https://youtu.be/srkdFzcjoS4?t=46m24s) We have a gamma, parameter alpha=2 and lambda
- [47:02](https://youtu.be/srkdFzcjoS4?t=47m2s) Conditional density on U given V is Uniform on 0 to V
- [47:30] E[U|V=v] = v/2
### [49:15](https://youtu.be/srkdFzcjoS4?t=49m15s) E[X|Y] = G(Y)
- E[G(Y)] = 
- [52:01](https://youtu.be/srkdFzcjoS4?t=52m1s) Conditional Probability * Marginal = Joint
### [52:25](https://youtu.be/srkdFzcjoS4?t=52m25s) Example: N is Geometric ...
### [1:00:02](https://youtu.be/srkdFzcjoS4?t=1h0m2s) Example: Compute Moment Generating function
- [1:05:10](https://youtu.be/srkdFzcjoS4?t=1h5m10s) Reminds us of the geometric series but need to transform
- [1:08:30](https://youtu.be/srkdFzcjoS4?t=1h8m30s) we’re fine as long as we keep: p<t *lambda
- [1:10:25](https://youtu.be/srkdFzcjoS4?t=1h10m25s) The moment generating function
- Will see this in Markov Processes
### [1:12:30](https://youtu.be/srkdFzcjoS4?t=1h12m30s) Example: Markov’s Inequality/Chebychev’s Inequality -Suppose E[X^2] < infinity...
### [1:19:08](https://youtu.be/srkdFzcjoS4?t=1h19m8s) Example: Use last result: Chebychev’s Inequality
- [1:20:30](https://youtu.be/srkdFzcjoS4?t=1h20m30s) Start on problem here
- [1:24:40](https://youtu.be/srkdFzcjoS4?t=1h24m40s) We arrive at the "Weak Law of Large Numbers"
- [1:29:30](https://youtu.be/srkdFzcjoS4?t=1h29m30s) A stronger theorem is true
### [1:30:40](https://youtu.be/srkdFzcjoS4?t=1h30m40s) Example:
- [1:30:55](https://youtu.be/srkdFzcjoS4?t=1h30m55s) Fixed mistake in last problem: forgot to square a - million instead of 1000
- [1:32:10](https://youtu.be/srkdFzcjoS4?t=1h32m10s) Back to problem
- [1:34:01](https://youtu.be/srkdFzcjoS4?t=1h34m1s) We can do numerical integration

## Lecture 11

## Lecture 12

## Lecture 13

## Lecture 14

## Lecture 15

## Lecture 16
