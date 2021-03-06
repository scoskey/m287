---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 287 homework

[Submit with gradescope](https://www.gradescope.com/courses/159026)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Week 14 (due Thursday, December 10)

Please prepare this assignment using LaTeX. Consider using the template above.

1. Prove that $\lim(ca\_n)=c(\lim a\_n)$.
2. Calculate the limits using the algebraic laws for limits.
  * $\lim \frac{15n^2-1}{1+2n+5n^2}$  
  &nbsp;
  * $\lim \frac{\sqrt{9n^5}+\sqrt{14n^3}+\sqrt{6n}}{\sqrt{25n^5}+\sqrt{12n^3}+\sqrt{5n}}$  
  &nbsp;
  * $\lim \frac{(4n^3+3n^2+2n+1)^{120}}{(3n^2+2n+1)^{72}}$ (Oops this one doesn't exist, please explain why)
3. Prove that limits are unique, that is, if $\lim a\_n=L$ and $\lim a\_n=M$ then $L=M$.
4. Prove that if $a\_n$ is bounded (above) by $b$, and $\lim a\_n$ exists, then $\lim a\_n\leq b$.


## Week 13 (due Thursday, December 3)

Please prepare this assignment using LaTeX. Consider using the template above.

1. Use the $\epsilon$ characterization of supremum to show that the set $S=\set{x\mid x^2\lt9}$ has the supremum $b=3$.
2. For each sequence $a\_n$, proposed limit $L$, and given tolerance $\epsilon$, find a suitable $N$ that makes the definition true.  
  * $a\_n=\frac{1}{\ln(n)}$, $L=0$, $\epsilon=0.1$
  * $a\_n=\frac{n}{2n+1}$, $L=1/2$, $\epsilon=0.01$
  * $a\_n=\frac{n}{2n+1}$, $L=1/2$, $\epsilon=0.001$
3. Prove that the limit of the sequence $a\_n=\frac{2n+1}{5n+4}$ is $L=\frac25$.
4. Show that the following statement is false by providing a counterexample: If $a\_n$ is bounded, then $a\_n$ has a limit.
5. Prove that if $a\_n$ has a limit, then $a\_n$ is bounded. Hint: Apply the definition of limit to $\epsilon=1$. Then argue that the sequence consists of a finite initial part, plus a bounded tail part.

## Week 12 (due Thursday, November 19)

Please prepare this assignment using LaTeX. Consider using the template above.

1. Prove or give a counterexample: $\abs{x+c}-c=\abs{x}$
2. Prove or give a counterexample: $\abs{x}\lt\abs{y}\iff x^2\lt y^2$
3. Prove or give a counterexample: $\abs{x+y}\geq\abs{\abs{x}-\abs{y}}$
4. Write the definitions of: upper bound for $S$, lower bound for $S$, and  bound for $S$. Show that if $S$ is has an upper bound and a lower bound, then $S$ has a bound.
5. Suppose that the maximum element of $S$ is $b$. Prove that the supremum of $S$ is $b$.
6. Suppose the supremum of $S$ is $10$. Show that for all $x\lt 10$, there exists $s\in S$ such that $x\lt s$.

## Week 11 (due Thursday, November 12)

1. Complete the Twelvefold Way notebook (you can find it in blackboard with the blank activities).

## Week 10 (due Thursday, November 5)

1. (Scheinerman 18.11) Prove that $\left(\binom{2a}{a}\right)=2\left(\binom{a}{2a}\right)$. (Brownie points for a combinatorial proof.)
2. Recall that $SS(k,2)$ is the number of ways to put $k$ labeled balls in $n$ unlabeled urns. Prove that $SS(k,2)=2^{k-1}$.
3. Recall that $S(k,2)$ is the number of ways to put $k$ labeled balls in $n$ unlabeled urns if we must use every urn at least once. Prove that $S(k,2)=2^{k-1}-1$.
4. Prove that $S(k,k-1)=\binom{k}{2}$.
5. Prove the that $S(k,n)$ satisfies the recurrence relation $S(k,n)=S(k-1,n-1)+n\cdot S(k-1,n)$.
6. Start working on your Twelvefold Way summary packet. It will be due next week!

## Week 9 (due Thursday, October 29)

1. (Scheinerman 17.5 modified) A group of $p$-many people attend an outdoor party with adequate social distancing measures. Everyone air-hugs everyone else. How many air-hugs were there? Explain your answer using balls and urns.
2. (Scheinerman 17.14 modified) You have a set $A$ with $n$-many elements. How many $k$-element subsets $B\subset A$ are there? How many subsets $B\subset A$ are there in total? Explain your answer. Use the above reasoning to give a proof of the equation: $\sum\_{k=0}^n\binom{n}{k}=2^n$.
3. (Scheinerman 17.16 modified) How many ways are there to choose a committee of $k$ people from a pool of $n$ people, with one committee member as the committee chair? Explain why the answer is $k\binom{n}{k}$. Explain why the answer is $n\binom{n-1}{k-1}$. Use the above reasoning to conclude that $k\binom{n}{k}=n\binom{n-1}{k-1}$.
4. A monomial is a product of variables to powers. The total degree of the monomial is the sum of the powers. For example $x^2y^3z^4$ is a monomial in three variables with total degree $9$. How many monomials are there with $v$-many variables and total degree $d$? Explain your answer using balls and urns.
5. In our data about $\left(\binom{n}{k}\right)$ we observed that $\left(\binom{n}{k}\right)=\left(\binom{n-1}{k}\right)+\left(\binom{n}{k-1}\right)$. Use ball/urn reasoning to explain why this is the case. Hint: Consider all the configurations of $k$ unlabeled balls in $n$ labeled urns. In how many is the last urn empty, and why? In how many is the last urn nonempty, and why? The total number is the sum of the these two cases.
6. (Scheinerman 18.14 modified) How many ways are there to put $k$-many balls in $n$-many urns if we assume that every urn is used at least once? Prove that the answer is $\left(\binom{n}{k-n}\right)$.

## Week 8

(midterm week, no homework)

## Week 7 (due Monday, October 12 at noon)

(graded for completeness only)

1. (Schinerman 42.1,2,8 modified) Find all subgroups of $\mathbb Z\_6$, of $\mathbb Z\_9$, and of $\mathbb Z_{10}$.
2. Find all subgroups of $S\_3$.
3. (Scheinerman 43.1,2 modified) For all $a\in\mathbb Z\_{13}$ calculate $a^{13}$. For all $a\in\mathbb Z_\{15}^*$ calculate $a^{15}$.
4. (Scheinerman 43.3,4 modified) Without a calculator, what is $3^{102}\pmod{101}$? Without a calculator, what is $2^{1,000,000}\pmod{101}$?

## Week 6 (due Thursday, October 8)

1. (Scheinerman 40.2) Define an operation on $\mathbb R$ by $x\cdot y=x+y-xy$. Is it closed? Associative? Commutative? Is there an identity? Inverses? Is it a group?
2. (Scheinerman 40.9) Show that if $G$ is a group then $(g^{-1})^{-1}=g$.
3. (Scheinerman 40.15) Show that if $G$ is a group then the function $f(g)=g^{-1}$ is a bijection of $G$ with itself.
4. (Scheinerman 40.16) Show that if $G$ is a group then in the multiplication table for $G$, every element of $G$ appears in every row and every column exactly once.  
   Give a counterexample showing that there can be such a table which doesn't arise from a group (and prove it doesn't).
5. (Scheinerman 40.17) Show that if $G$ is a group with $\cdot$ then $(gh)^{-1}=h^{-1}\cdot g^{-1}$.
6. (Scheinerman 40.20) Use $\LaTeX$ to write your solution to this question. Let $G$ be a group of even size. Show that there exists a non-identity element $g$ such that $g^{-1}=g$.

## Week 5 (due Thursday, October 1)

1. (Scheinerman 37.2) Solve the equations in the specified $\mathbb Z\_n$.  
  * $3x=4$ in $\mathbb Z\_{11}$
  * $4x-8=9$ in $\mathbb Z\_{11}$
  * $3x+8=1$ in $\mathbb Z\_{10}$
  * This is just a bonus challenge: $342x+448=73$ in $\mathbb Z\_{1003}$
2. (Scheinerman 37.10) In usual arithmetic, $ab=0$ if and only if $a=0$ or $b=0$. For which $n$ is this statement true in $\mathbb Z\_n$? Prove your answer.
3. Suppose that $a,b\in\mathbb Z\_n\setminus\set{0}$, and $ab=0$. Prove that $a$ does not have an inverse in $\mathbb Z\_n$.
4. (Scheinerman 37.13) Working in $\mathbb Z\_n$, prove that $n-1$ is its own inverse.
5. Let's do some $\LaTeX$. Write a practice document of 1-2 pages on Overleaf. Your writing doesn't have to make any sense, Just show me you can use some of the common features of $\LaTeX$. You can copy some of the text and equations from a textbook or article that you find online! Make sure to include at least one of each of the following:  
  * A title and author
  * A section and subsection
  * A paragraph with some inline equations
  * A big gnarly centered equation with lots and lots of symbols
  * An equation with a fraction in it
  * An equation with multiple lines (learn the "align" environment)
  * A theorem, lemma, definition, or exercise environment
  * A short table


## Week 4 (due Thursday, September 24)

1. (Scheinerman 27.2) Write the following permutations in disjoint cycle notation.  
  * $\sigma=\begin{bmatrix}1&2&3&4&5&6\\\\2&4&6&1&3&5\end{bmatrix}$
  * $\pi=\begin{bmatrix}1&2&3&4&5&6\\\\2&3&4&5&6&1\end{bmatrix}$
  * $\pi^2$
  * $\pi^{-1}$
  * The identity of $S\_5$
  * $(1,2)\circ(2,3)\circ(3,4)\circ(4,5)\circ(5,1)$
  * (skip part g)
2. (Scheinerman 27.7 modified) Suppose that $\sigma,\tau$ are transpotitions, that is, they are $2$-cycles. When is it true that $\sigma\circ\tau=\tau\circ\sigma$? Prove your answer.
3. (Scheinerman 27.13) Let $\pi=(1,2)(3,4,5,6,7)(8,9,10,11)(12)\in S\_{12}$. What is the least $k$ such that $\pi^k=()$? Generalize your method to answer the question: if $\pi$ consists of cycles of length $n\_1,\ldots,n\_t$, then what is the least $k$ such that $\pi^k=()$?
4. (Scheinerman 27.15 and 16)  
  * Prove that if $\pi,\sigma\in S\_n$ and $\pi\circ\sigma=\sigma$, then $\pi=$ the identity.
  * Prove that if $\pi,\sigma,\tau\in S\_n$ and $\pi\circ\sigma=\pi\circ\tau$, then $\sigma=\tau$.
5. Complete Activity 4, page 4. Find all eight permutations of $\set{1,2,3,4}$ that preserve the square. Write them in cycle notation. Give them short descriptive names. Write an $8\times8$ multiplication table for this set.

## Week 3 (due Thursday, September 17)

1. (Scheinerman 24.23)  
  * Let $f(x)=\abs{x}$ and $X=\set{-1,0,1,2}$. Find $f(X)$.
  * Let $f(x)=\sin(x)$ and $X=[0,\pi]$. Find $f(X)$.
  * Let $f(x)=2^x$ and $X=[-1,1]$. Find $f(X)$.
  * Let $f(x)=3x-1$ and $X=\set{1}$. Find $f(X)$. Compare the answer with $f(1)$.
  * If $A$ is the domain of $f$, what is another name for $f(A)$?
2. (Scheinerman 24.24)  
  * Let $f(x)=\abs{x}$ and $Y=\set{1,2,3}$. Find $f^{-1}(Y)$.
  * Let $f(x)=x^2$ and $Y=[1,2]$. Find $f^{-1}(Y)$.
  * Let $f(x)=1/(1+x^2)$ and $Y=\set{1/2}$. Find $f^{-1}(Y)$.
  * Let $f(x)=1/(1+x^2)$ and $Y=\set{-1/2}$. Find $f^{-1}(Y)$.
3. Let $f\colon A\to B$ be a surjective function and $Y\subset B$. Prove that $f(f^{-1}(Y))=Y$. [**Note** Updated to add the surjective hypothesis.]
4. Let $f\colon A\to B$ be a function and $X\subset A$. Prove that $f^{-1}(f(X))\supset X$. Give an example where equality is true. Give an example where equality is not true. [Hint: use the old favorite $f(x)=x^2$ and $X=(2,3)$.]

## Week 2 (due Thursday, September 10)

1. Use induction to prove the following: If $A$ is a set of size $n$ then $P(A)$ is a set of size $2^n$.
2. Use a LHS=RHS argument to prove that $A\triangle(B\triangle C)=(A\triangle B)\triangle C$.
3. Use a LHS=RHS argument to prove that $(A\setminus B)\cup(B\setminus A)=(A\cup B)\setminus(A\cap B)$.
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

## Week 1 (Due Thursday, September 3)

For background, read section 22 of Scheinerman's book, and watch [Khan's video](https://youtu.be/wblW_M_HVQ8) on induction. Then use induction to prove that the following are true for all natural numbers $n$.

1. $1^3+2^3+\cdots+n^3=\frac{n^2(n+1)^2}{4}$
2. $\left(\frac12\right)^0+\left(\frac12\right)^1+\left(\frac12\right)^2+\cdots+\left(\frac12\right)^n=2-\left(\frac12\right)^n$
3. $n^3+5n+6$ is divisible by $3$.
4. Let $x\_1=0$ and $x\_{n+1}=\sqrt{2+x\_n}$ for all $n$. Prove that for all $n$ we have $x\_n\lt2$.
5. (Scheinerman 22.10) For $n\geq3$, the sum of the angles of a (convex) polygon with $n$ sides is $180(n-2)$ degrees.

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