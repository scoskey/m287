---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 287 homework

[Submit with gradescope](https://www.gradescope.com/courses/413852)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

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
3. (Scheinerman 27.13) Let $\pi=(1,2)(3,4,5,6,7)(8,9,10,11)(12)\in S\_{12}$. Find the least natural number $k$ such that $\pi^k=()$. (The symbol () means the identity permutation.) Then generalize your method to answer the question: if $\pi$ consists of cycles of length $n\_1,\ldots,n\_m$, then what is the least $k$ such that $\pi^k=()$? Explain your answer (you do not need to give a formal proof).
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