---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 287 homework

[Submit with gradescope](https://www.gradescope.com/courses/413852)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Week 2 (Due Tuesday, September 6)

For background, read Scheinerman section 12, or MCC chapter 4.

1. TBA

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