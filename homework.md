---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 287 homework

[Submit with gradescope](https://www.gradescope.com/courses/159026)

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