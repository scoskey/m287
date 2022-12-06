---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 287 homework

[Submit with gradescope](https://www.gradescope.com/courses/413852)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Week 15 Take-home Final (Due Monday, December 12)

**Instructions** (a) You may not consult with any other person. Your work must be *completely your own*. (b) You may refer to class notes and materials freely. (c) If you use any outside resources, please provide citations. (d) To receive full credit, use only the methods *we learned in our class*. (e) To receive full credit, please show all work. 

1. Please copy the following paragraph, and sign your name below it: "My solutions are my own original work. I completed this exam without consulting any other person. I followed Boise State University's policies on academic integrity."
2. Answer each problem using one of the concepts from the twelvefold way. Please explain briefly how you know your choice is correct (e.g. what do the cups and balls represent, what are the restrictions, etc).  
  * How many ways are there for a judging panel of $J$ many judges to vote for one of $C$ many candidates to win an award? (The voting is not anonymous.)
  * How many ways are there to distribute $R$ many numbered raffle tickets into $E$ many identical envelopes?
  * How many ways are there to express an integer $N$ as a sum of $m$ many nonnegative integers?
3. Recall that $P(k,n)$ satisfies the recurrence $P(k,n)=P(k-1,n-1)+P(k-n,n)$. Use this recurrence (plus values you already know) to build up a larger table of values and calculate $P(12,6)$. Show all work regarding the calculation of the $n=6$ line of the table.
4. Use combinatorial proof to show that the number of ways to put $k$ unlabeled balls into $n$ labeled cups, with every cup used at least once, is equal to $\binom{k-1}{n-1}$. **Hint** Lay the balls out from left to right, and for each space between balls, choose whether or not to put a divider. How many spaces are there? How many dividers do you need? How does this answer the question?
5. Let $t(k,n)$ be the number of ways to put $k$ unlabeled balls in $n$ labeled cups, assuming each cup must contain *at least two balls*.  
  * Collect a table of values of $t(k,n)$ for $n\leq 5$ and $k\leq 8$.
  * In your data, you may observe the binomial coefficients appear. Prove that $t(k,n)=(\binom{n}{k-2n})$.
6. Solve the following absolute value inequalities. Write your answers in interval notation.  
  * $\abs{2x-3}\leq\abs{x+1}$
  * $\abs{x^2-4}\leq\abs{x+2}$
7. Is there a positive number $x$ such that $x\lt\frac1n$ for all $n\in\mathbb{N}$? Describe such a number or prove none exists.
8. Let $x\_n$ be a sequence, and assume that $\lim(x\_n)^2=0$. Prove that $\lim x\_n=0$. **Hint** Given $\epsilon>0$, apply the definition of $\lim(x\_n)^2=0$ with $\epsilon'=\sqrt{\epsilon}$.
9. Use the properties of limits to calculate the following limits.  
  * $\lim\frac{(2n+2)(3n+1)}{12n^2+5\sqrt{n}+10}$
  * $\lim\frac{\sqrt{3n^3}+\sqrt{4n}}{\sqrt{5n^3}+\sqrt{6n}}$

## Week 14 (Due Tuesday, December 6)

1. For each sequence $a\_n$, proposed limit $L$, and given tolerance $\epsilon$, find a suitable $N$ that makes the definition true.  
  * $a\_n=\frac{1}{\ln(n)}$, $L=0$, $\epsilon=0.1$
  * $a\_n=\frac{n}{2n+1}$, $L=1/2$, $\epsilon=0.01$
  * $a\_n=\frac{n}{2n+1}$, $L=1/2$, $\epsilon=0.001$
2. Use the $\epsilon$-definition of limit to prove that the limit of $a\_n=\frac{n}{2n+1}$ is $L=\frac12$.
3. Use the $\epsilon$-definition of limit to prove that if $\lim a\_n=L$ and $\lim a\_n=M$ then $L=M$. (Thus the symbol $\lim(a_n)$ is justified.)
4. Use the $\epsilon$-definition of limit to prove that $\lim(ca\_n)=c(\lim a\_n)$.
5. Calculate the following limits using the algebraic limit laws.
  * $\lim \frac{15n^2-1}{1+2n+5n^2}$  
  &nbsp;
  * $\lim \frac{\sqrt{9n^5}+\sqrt{14n^3}+\sqrt{6n}}{\sqrt{25n^5}+\sqrt{12n^3}+\sqrt{5n}}$  
  &nbsp;
  * $\lim \frac{(4n^3+3n^2+2n+1)^{120}}{(3n^5+2n+1)^{72}}$


## Week 13 (Due Tuesday, November 29)

1. Suppose that $S$ has a maximum element $b$. Show that the supremum of $S$ is $b$.
2. Use the $\epsilon$ definition of supremum to show that the supremum of the set $S=\set{x\mid x^2\lt9}$ is $b=3$.
3. Suppose that the supremum of $S$ is $b$. Show that there exists a sequence $a\_n$ of elements of $S$ such that the supremum of $a\_n$ is also $b$.
4. Please use $\LaTeX$ to write your solution to this question. Let x\_n and y\_n be sequences which are bounded above. Prove that $\sup(x\_n+y\_n)\leq\sup(x\_n)+\sup(y\_n)$. Show with an example that we cannot replace the $\leq$ with $=$ in general.
5. Please use $\LaTeX$ to write your solution to this question. Show that if b is any real number, then there exists a sequence x\_n whose values are rational and whose supremum is equal to b. [Hint: Consider the decimal expansion of b.]

## Week 12 (Due Tuesday, November 15)

1. Solve the inequalities. Express your answers using intervals.  
  * $\abs{x-3}\leq\abs{x-10}$
  * $\abs{8x}\leq\abs{x^2-9}$
2. Decide whether the statement is always true or sometimes false. Prove it or give a counterexample. $\abs{x+c}-c=\abs{x}$
3. Decide whether the statement is always true or sometimes false. Prove it or give a counterexample. $\abs{x+y}\geq\abs{\abs{x}-\abs{y}}$
4. For a subset $A\subset\mathbb R$, let $\mathrm{abs}(A)$ be the set $\set{\abs{a}:a\in A}$. Show that $\mathrm{abs}(A)$ has an upper bound if and only if $A$ has both a lower bound and an upper bound.
5. Please use $\LaTeX$ to write your solution to this question. Let $A\subset\mathbb R$ and $b\in\mathbb R$. Suppose that any number greater than $b$ is an upper bound of $A$. Show that $b$ is an upper bound of $A$.

## Week 11 (Due Tuesday, November 8)

1. Please complete the Twelvefold Way notebook.

## Week 10 (Due Tuesday, November 1 - now Thursday, November 3)

1. How many ways are there to put $k$ unlabeled balls into $n$ labeled cups, if each cup must be used at least once? (Hint: The answer involves a multichoose.)
2. Recall that $SS(k,2)$ is the number of ways to put $k$ labeled balls in $2$ unlabeled cups. Prove that $SS(k,2)=2^{k-1}$.
3. Recall that $S(k,n)$ is the number of ways to put $k$ labeled balls in $n$ unlabeled cups, if every cup must be used at least once. Prove the that $S(k,n)$ satisfies the recurrence relation $S(k,n)=S(k-1,n-1)+n\cdot S(k-1,n)$.
4. Please use $\LaTeX$ to write your solution to this question. Prove that $S(k,2)=2^{k-1}-1$.
5. Please use $\LaTeX$ to write your solution to this question. Prove that $S(k,k-1)=\binom{k}{2}$.

## Week 9 (Due Tuesday, October 25)

1. 
  * How many ways are there to pass out 9 different candies to three children?
  * How many ways are there to paint 15 numbered balls, each with one color chosen from red, black, green, and blue?
  * How many ways are there to number the corners of a square, if two such numberings are considered equivalent when one is a rotation of the other?
  * A tennis club has 12 members. How many ways are there to pair the players by twos for singles matches?
2. (See Scheinerman 17.14) You have a set $A$ with $n$-many elements. How many $k$-element subsets $B\subset A$ are there? How many subsets $B\subset A$ are there in total? Explain your answers. Use the above reasoning to give a proof of the equation: $\sum\_{k=0}^n\binom{n}{k}=2^n$.
3. (See Scheinerman 17.16) How many ways are there to choose a committee of $k$ people from a pool of $n$ people, with one committee member as the committee chair? Explain why the answer is $k\binom{n}{k}$. Explain why the answer is $n\binom{n-1}{k-1}$. Use the above reasoning to conclude that $k\binom{n}{k}=n\binom{n-1}{k-1}$.
4. A monomial is a product of variables to powers. The total degree of the monomial is the sum of the powers. For example $x^2y^3z^4$ is a monomial in three variables with total degree $9$. How many monomials are there with $v$-many variables and total degree $d$? Explain your reasoning.
5. In our data about $\left(\binom{n}{k}\right)$ we observed that $\left(\binom{n}{k}\right)=\left(\binom{n-1}{k}\right)+\left(\binom{n}{k-1}\right)$. Use reasoning about voting to explain why this is the case. [Hint: Consider all possibilities for $k$ voters voting on $n$ candidates. In how many possibilities did the last candidate receive no votes? In how possibilities did the last candidate receive at least one vote? The total number of possibilities is the sum of these two cases.]

## Week 8 Take-home Midterm (Due Sunday, October 16)

**Instructions** (a) You may not consult with any other person. Your work must be *completely your own*. (b) You may refer to class notes and materials freely. (c) If you use any outside resources, please provide citations. (d) To receive full credit, use only the methods *we learned in our class*. (e) To receive full credit, please show all work. 

1. Please copy the following quotation, and sign your name: "My solutions are my own original work. I completed this exam without consulting any other person. I followed Boise State University's policies on academic integrity."
2. Use induction for each of the following.
  * For all $n\geq1$, prove that $1+4+7+\cdots(3n-2)=\frac{3n^2-n}{2}$.
  * Let $x\_1=1$ and $x\_{n+1}=\frac{1}{3-x\_n}$. For all $n\geq1$, prove that $x\_{n+1}\lt x\_n$.
3. 
  * Use a LHS/RHS argument to prove that $P(A\cap B)=P(A)\cap P(B)$.
  * Give an example to explain why $P(A\cup B)$ is not generally equal to $P(A)\cup P(B)$.
4. Let $f(x)=\frac{1}{x+1}$ (the domain is $\mathbb R\setminus\{-1\}$).
  * Let $Y=(-1,1)$ and find $f^{-1}(Y)$.
  * Decide whether $f$ is injective, and prove your answer.
5. Consider the permutation $\pi=(12)(123)(1234)(3456)$ in $S_6$.
  * Simplify the expression to write $\pi$ in standard cycle notation (where the cycles are disjoint)
  * Write $\pi$ in brackets notation
  * Find the order of $\pi$
  * Find the inverse of $\pi$ in cycle notation
  * Find $\pi^2$ in cycle notation
6. Use the method of repeated squaring to find the representative of $a^k\pmod{n}$.
  * $10^{512}\pmod{13}$
  * $10^{983}\pmod{13}$
7. Use the method of repeated division and back-solving to find each multiplicative inverse.
  * $3^{-1}$ in $(\mathbb Z\_{101})^\ast$
  * $13^{-1}$ in $(\mathbb Z\_{865})^\ast$
8. Let $G$ be a finite group.
  * Prove that for any $g$ in $G$, the order of $g^2$ is less than or equal to the order of $g$.
  * Give an example of a group $G$ and an element $g$ where the order of $g^2$ is less than the order of $g$.
  * Give an example of a group $G$ and an element $g$ where the order of $g^2$ is equal to the order of $g$.
9. Let $m$ and $n$ be natural numbers. Suppose there exist integers $x$ and $y$ such that $mx+ny=1$. Show that $m$ and $n$ have no common factors (other than $1$).

## Week 7 (Due Tuesday, October 11)

1. Let $G$ be a group, let $a$ be an element of $G$, and $a^{-1}$ its inverse. Show that the order of $a$ is equal to the order of $a^{-1}$. 
2. Let $G$ be a group and let $a,b$ be elements of $G$. Show that the order of $ab$ is equal to the order of $ba$.
3. (Scheinerman 43.1,2 modified) For all $a\in(\mathbb Z\_{13})^\ast$ calculate $a^{13}$. For all $a\in(\mathbb Z\_\{15})^\ast$ calculate $a^{15}$.
4. (Scheinerman 43.3,4 modified) Without any big calculations, what is $3^{205}\pmod{101}$? What is $2^{1,000,000}\pmod{101}$?
5. Let $n$ be any integer, and let $\phi(n)$ denote the number of elements of $(\mathbb Z\_n)^\ast$. Show that if $a,n$ have no common factors, then $a^\phi(n)\equiv1\pmod{n}$.

## Week 6 (Due Tuesday, October 4)

1. (Scheinerman 40.2) Define an operation on $\mathbb R$ by $x\cdot y=x+y-xy$. Is it closed? Associative? Commutative? Is there an identity element? If there is an identity, are there inverses? In sum, is it a group?
2. (Scheinerman 40.9 & 17) Show that if $G$ is a group, then $(g^{-1})^{-1}=g$ and $(gh)^{-1}=h^{-1}\cdot g^{-1}$.
3. Show that if $a$ and $n$ have a common factor greater than $1$, then $a$ does not have an inverse in $\mathbb{Z}\_n$.
4. Use successive division and back-solving to find the inverse of $137$ in $\mathbb{Z}\_{350}$. Verify that your answer is correct by showing that $137$ times your answer is equivalent to $1$.
5. (Scheinerman 40.15) Please use $\LaTeX$ to write your solution to this question. Show that if $G$ is a group, then the function $f(g)=g^{-1}$ is a bijection of $G$ with itself.

## Week 5 (Due Tuesday, September 27)

1. (See Scheinerman 37.2) Solve the equations in the specified $\mathbb Z\_n$.  
  * $3x=4$ in $\mathbb Z\_{11}$
  * $4x-8=9$ in $\mathbb Z\_{11}$
  * $3x+8=1$ in $\mathbb Z\_{10}$
2. Consider the permutation of the set $\set{1,\ldots,10}$ defined by $\pi(i)=3i\pmod{11}$. Write $\pi$ in cycle notation.
3. Use your work from the group activity on repeated squaring to calculate the modular powers.  
  * $2^{120}\pmod{9}$
  * $3^{1500}\pmod{11}$
4. (Scheinerman 37.10) In usual arithmetic, $ab=0$ if and only if $a=0$ or $b=0$. For which $n$ is this statement true in $\mathbb Z\_n$? Prove your answer.
5. (Scheinerman 37.13) Working in $\mathbb Z\_n$, prove that $n-1$ is its own inverse.
6. Let's do some $\LaTeX$! Write a practice document of 1-2 pages on Overleaf. Your writing doesn't have to make any sense, just show me you can use some of the common features of $\LaTeX$. You can copy some of the text and equations from the textbook or an article that you find online! Make sure to include at least one of each of the following:  
  * A title and author
  * A section and subsection
  * A paragraph with some inline equations
  * A big gnarly centered equation with lots and lots of symbols
  * An equation with a fraction in it
  * An equation with multiple lines (learn the "align" environment)
  * A theorem, lemma, definition, or exercise environment
  * A short table

## Week 4 (Due Tuesday, September 20)

1. (Scheinerman 27.2) Convert each of the following permutations to cycle notation.  
  * $\sigma=\begin{bmatrix}1&2&3&4&5&6\\\\2&4&6&1&3&5\end{bmatrix}$
  * $\pi=\begin{bmatrix}1&2&3&4&5&6\\\\2&3&4&5&6&1\end{bmatrix}$
  * $\pi^2$
  * $\pi^{-1}$
  * The identity of $S\_5$
  * $(1,2)\circ(2,3)\circ(3,4)\circ(4,5)\circ(5,1)$
  * (skip part g)
2. (Scheinerman 27.7 modified) Suppose that $\sigma,\tau$ are transpositions, that is, they are cycles of length $2$. When is it true that $\sigma\circ\tau=\tau\circ\sigma$? Prove your answer.
3. (Scheinerman 27.13) Let $\pi=(1,2)(3,4,5,6,7)(8,9,10,11)(12)\in S\_{12}$. Find the least natural number $k$ such that $\pi^k=()$. (The symbol () means the identity permutation.) Then generalize your method to answer the question: if $\pi$ consists of disjoint cycles of length $n\_1,\ldots,n\_m$, then what is the least $k$ such that $\pi^k=()$? Explain your answer (you do not need to give a formal proof).
4. (Scheinerman 27.15 and 16)  
  * Prove that if $\pi,\sigma\in S\_n$ and $\pi\circ\sigma=\sigma$, then $\pi=$ the identity.
  * Prove that if $\pi,\sigma,\tau\in S\_n$ and $\pi\circ\sigma=\pi\circ\tau$, then $\sigma=\tau$.
5. Draw a square and label the corners $1,2,3,4$ in clockwise order. Some permutations of the set $\set{1,2,3,4}$ leave the square intact, while others "break" it. (For example, $(1234)$ rotates the square clockwise, leaving the square intact. On the other hand, $(12)$ makes $1$ be between $2$ and $3$, breaking the square.) Find all eight permutations that leave the square intact, and write them all in cycle notation.

## Week 3 (Due Tuesday, September 13)

1. (Similar to Scheinerman 24.23)  
  * Let $f(x)=\abs{x}$ and $X=(-4,-2)\cup(1,3)$. Find $f(X)$.
  * Let $f(x)=\sin(x)$ and $X=[0,\pi]$. Find $f(X)$.
  * Let $f(x)=2^x$ and $X=[-1,1]$. Find $f(X)$.
  * Let $f(x)=3x-1$ and $X=\set{1}$. Find $f(X)$. Compare the answer with $f(1)$.
  * If $X$ is the domain of $f$, what is another name for $f(X)$?
2. (Similar to Scheinerman 24.24)  
  * Let $f(x)=\abs{x}$ and $Y=\set{-1,1,2,3}$. Find $f^{-1}(Y)$.
  * Let $f(x)=x^2$ and $Y=[1,2]$. Find $f^{-1}(Y)$.
  * Let $f(x)=1/(1+x^2)$ and $Y=\set{1/2}$. Find $f^{-1}(Y)$.
  * Let $f(x)=1/(1+x^2)$ and $Y=\set{-1/2}$. Find $f^{-1}(Y)$.
3. Let $f\colon A\to B$ be a function and $X\subset A$. Prove that $f^{-1}(f(X))\supset X$. Give an example where equality is true. Give an example where equality is not true. [Hint for the last part: use the old favorite $f(x)=x^2$.]

## Week 2 (Due Thursday, September 8)

For background, read Scheinerman section 12, or MCC chapter 4.

1. Use induction to prove the following: If $A$ is a set of size $n$ then $P(A)$ is a set of size $2^n$.
2. Use a LHS/RHS argument to prove that $A\triangle(B\triangle C)=(A\triangle B)\triangle C$.
3. Use a LHS/RHS argument to prove that $(A\setminus B)\cup(B\setminus A)=(A\cup B)\setminus(A\cap B)$.
4. (Scheinerman 12.17) Assume $A,B$ are nonempty. Prove that $A\times B=B\times A$ if and only if $A=B$. What goes wrong if either $A$ or $B$ is empty?
5. (Scheinerman 24.14) Decide with proof whether each of the functions is injective, surjective, both or neither.  
  * $f\colon\mathbb Z\to\mathbb Z$ defined by $f(x)=2x$
  * $f\colon\mathbb Z\to\mathbb Z$ defined by $f(x)=10+x$
  * $f\colon\mathbb N\to\mathbb N$ defined by $f(x)=10+x$
  * $f\colon\mathbb Z\to\mathbb Z$ defined by $f(x)=x/2$ if $x$ is even and $f(x)=(x-1)/2$ if $x$ is odd
  * $f\colon\mathbb Q\to\mathbb Q$ defined by $f(x)=x^2$
6. For each pair of sets $A,B$, find a bijective function with domain $A$ and codomain $B$.
  * $A=(2,3)$, $B=(4,7)$
  * $A=\mathbb R$, $B=(0,\infty)$
  * $A=\mathbb R$, $B=(0,1)$
  * $A=\mathbb [0,1]$, $B=[0,1)$

## Week 1 (Due Tuesday, August 30)

For background, read Scheinerman section 22 book, or MCC section 3.6. You can also watch [Khan's video](https://youtu.be/wblW_M_HVQ8) on induction. Then use induction to solve each of the following exercises.

1. Prove that for all $n\geq1$, we have $2^0+2^1+2^2+\cdots+2^n=2^{n+1}-1$.
2. Prove that for all $n\geq1$, we have $\left(\frac12\right)^0+\left(\frac12\right)^1+\left(\frac12\right)^2+\cdots+\left(\frac12\right)^n=2-\left(\frac12\right)^n$.
3. Prove that for all $n\geq1$, the quantity $n^3+5n+6$ is divisible by $3$.
4. Consider the recursive definition: $x\_1=0$ and $x\_{n+1}=\sqrt{2+x\_n}$. Prove that for all $n\geq1$, we have $x\_n\lt2$.
5. Using the same recursive definition as above, prove that for all $n\geq1$, we have $x_n\lt x_{n+1}$.


<script type='text/x-mathjax-config'>
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [['$','$'], ['\\(','\\)']],
      processEscapes: true
    },
    TeX: {
      Macros: {
        set: ["{\\left\\{ #1 \\right\\}}", 1],
        abs: ["{\\left| #1 \\right|}", 1],
        lt: ["<"]
      }
    }
  });
</script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-AMS_HTML'></script>