---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 287 homework

[Submit with gradescope](https://www.gradescope.com/courses/159026)

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
3. Let $f\colon A\to B$ be a function and $Y\subset B$. Prove that $f(f^{-1}(Y))=Y$.
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