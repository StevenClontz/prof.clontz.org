---
layout: page
title: "Part 5: Sequences and Series"
---




---

## 5.5 Comparison Tests

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.4

### 5.5.1 Direct Comparison Test

<iframe width="560" height="315" src="https://www.youtube.com/embed/5DYYL4GlBuw" frameborder="0" allowfullscreen></iframe><!-- TODO rerecord -->

- Suppose \\(\sum_{n=N}^\infty a_n\\) is a series with non-negative terms.
    - If there exists a convergent series \\(\sum_{n=M}^\infty b_n\\)
      with non-negative terms where \\(a_n\leq b_n\\) for sufficiently
      large \\(n\\), then \\(\sum_{n=N}^\infty a_n\\) converges as well.
    - If there exists a divergent series \\(\sum_{n=M}^\infty b_n\\)
      with non-negative terms where \\(a_n\geq b_n\\) for sufficiently
      large \\(n\\), then \\(\sum_{n=N}^\infty a_n\\) diverges as well.
- **Example**
  Show that \\(\sum_{n=0}^\infty\frac{n}{n^3+3n+2}\\) converges by
  comparing with the series \\(\sum_{n=1}^\infty\frac{1}{n^2}\\).
- Following is a list of sequence formulas ordered from larger to
  smaller (for sufficiently large \\(n\\)).
    - \\(n^n\\)
    - \\(n!\\)
    - \\(b^n\\) where \\(b>1\\) (such as \\(2^n,e^n,10^n\\)...)
    - \\(n^p\\) where \\(p>0\\) (such as \\(\sqrt{n},n,n^4\\)...)
    - \\(\log_b n\\) where \\(b>1\\)
      (such as \\(\log_{10}(n),\ln(n),\log_2(n)\\)...)
    - any positive constant
- **Example**
  Does \\(\sum_{n=1}^\infty\frac{2}{n^{1/3}+5}\\) converge or diverge?
- **Example**
  Does \\(\sum_{k=3}^\infty\frac{3^n}{n!}\\) converge or diverge?
- **Example**
  Does \\(\sum_{m=2}^\infty(m\ln m)^{-1/2}\\) converge or diverge?


### 5.5.2 Limit Comparison Test

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ug9mAWcbwp0" frameborder="0" allowfullscreen></iframe><!-- TODO rerecord, consider just 0<lim<infty -->

- Suppose \\(\sum_{n=N}^\infty a_n\\) is a series with non-negative terms.
    - If there exists a convergent series \\(\sum_{n=M}^\infty b_n\\)
      with non-negative terms where
      \\(\lim_{n\to\infty}\frac{a_n}{b_n}<\infty\\),
      then \\(\sum_{n=N}^\infty a_n\\) converges as well.
    - If there exists a divergent series \\(\sum_{n=M}^\infty b_n\\)
      with non-negative terms where
      \\(\lim_{n\to\infty}\frac{a_n}{b_n}>0\\) (including divergence
      to infinity),
      then \\(\sum_{n=N}^\infty a_n\\) diverges as well.
- **Example**
  Does \\(\sum_{n=1}^\infty\frac{2}{n^{1/3}+5}\\) converge or diverge?
- **Example**
  Does \\(\sum_{i=0}^\infty\frac{3i}{5^i}\\) converge or diverge?
- **Example**
  Does \\(\sum_{n=42}^\infty\frac{2^n+5^n}{3^n+4^n}\\) converge or diverge?

### Exercises for 5.5

1.  Does \\(\sum_{n=0}^\infty\sqrt{\frac{n}{n^4+7}}\\) converge or
    diverge? (Use Direct Comparison.)
1.  Does \\(\sum_{n=3}^\infty\frac{4}{n^{0.8}-1}\\) converge or
    diverge? (Use Direct Comparison.)
1.  Does \\(\sum_{j=2}^\infty\frac{e^j}{e^{2j}+1}\\) converge or diverge?
    (Use Direct Comparison.)
1.  Does \\(\sum_{k=10}^\infty\frac{\sin^2(k)}{k^3}\\) converge or diverge?
    (Use Direct Comparison.)
1.  Does \\(\sum_{m=4}^\infty\frac{1}{\ln m}\\) converge or diverge?
    (Use Direct Comparison.)
1.  Does \\(\sum_{n=4}^\infty\frac{5}{2n+3}\\) converge or diverge?
    (Use Direct Comparison.)
1.  Does \\(\sum_{n=0}^\infty\sqrt{\frac{n}{n^4+7}}\\) converge or
    diverge? (Use Limit Comparison.)
1.  Does \\(\sum_{n=3}^\infty\frac{4}{n^{0.8}-1}\\) converge or
    diverge? (Use Limit Comparison.)
1.  Does \\(\sum_{j=2}^\infty\frac{e^j}{e^{2j}+1}\\) converge or diverge?
    (Use Limit Comparison.)
1.  Does \\(\sum_{k=10}^\infty\frac{\sin^2(k)}{k^3}\\) converge or diverge?
    (Use Limit Comparison.)
1.  Does \\(\sum_{m=4}^\infty\frac{1}{\ln m}\\) converge or diverge?
    (Use Limit Comparison.)
1.  Does \\(\sum_{n=4}^\infty\frac{5}{2n+3}\\) converge or diverge?
    (Use Limit Comparison.)
1.  (OPTIONAL)
    Does \\(\sum_{m=1}^\infty\frac{1}{1+2+\dots+(m-1)+m}\\) converge or diverge?
    (Hint: show that \\(
      \frac{1}{1+2+\dots+(m-1)+m}
        =
      \frac{2}{(1+m)+(2+m-1)+\dots+(m-1+2)+(m+1)}
    \\).)
1.  (QUIZ)
    Does \\(\sum_{m=0}^\infty\frac{2m}{(m^2+1)^2}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It both converges and diverges.
1.  (QUIZ) <!-- TODO add as actual exercise -->
    Does \\(\sum_{n=1}^\infty\sqrt{\frac{n+1}{n^2+3}}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It neither converges nor diverges.

[Solutions 1-8]({{site.baseurl}}public/solutions/5.5a.pdf)

[Solutions 9-15]({{site.baseurl}}public/solutions/5.5b.pdf)




---

## 5.7 Ratio and Root Tests

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.5 <!-- TODO consider putting before 5.6 -->

### 5.7.1 Ratio Test

<iframe width="560" height="315" src="https://www.youtube.com/embed/gYkp0LuVi5g" frameborder="0" allowfullscreen></iframe>

- The Ratio Test states that the series \\(\sum_{n=N}^\infty a_n\\)
  absolutely converges when \\(\lim_{n\to\infty}\|\frac{a_{n+1}}{a_n}\|<1\\)
  and diverges when \\(\lim_{n\to\infty}\|\frac{a_{n+1}}{a_n}\|>1\\).
- **Example**
  Show that \\(\sum_{n=0}^\infty\frac{3^n+1}{4^n}\\) absolutely converges
  using the Ratio Test. Then give its value.
- **Example**
  Does \\(\sum_{k=3}^\infty\frac{(2k)!}{3(k!)^2}\\) converge or diverge?
- Another test must be used when
  \\(\lim_{n\to\infty}\|\frac{a_{n+1}}{a_n}\|=1\\).
- **Example**
  Show that the divergent series
  \\(\sum_{n=1}^\infty\frac{1}{n}\\) and the absolutely convergent series
  \\(\sum_{n=1}^\infty\frac{1}{n^2}\\) both satisfy
  \\(\lim_{n\to\infty}\|\frac{a_{n+1}}{a_n}\|=1\\).

### 5.7.2 Root Test

<iframe width="560" height="315" src="https://www.youtube.com/embed/gMnZOesL3wY" frameborder="0" allowfullscreen></iframe>

- The Root Test states that the series \\(\sum_{n=N}^\infty a_n\\)
  absolutely converges when \\(\lim_{n\to\infty}\sqrt[n]{\|a_n\|}<1\\)
  and diverges when \\(\lim_{n\to\infty}\sqrt[n]{\|a_n\|}>1\\).
- **Example**
  Show that \\(\sum_{n=0}^\infty\frac{5^n}{2^{3n}}\\) absolutely converges
  using the Root Test. Then give its value.
- **Example**
  Does \\(\sum_{m=3}^\infty\frac{m^{10}}{(-3)^m}\\) converge or diverge?
- Another test must be used when
  \\(\lim_{n\to\infty}\sqrt[n]{\|a_n\|}=1\\).

### Exercises for 5.7

1.  Does \\(\sum_{k=1}^\infty\frac{k^2+4}{(k+2)!}\\) converge or diverge?
1.  Does \\(\sum_{n=0}^\infty\frac{(2n)!}{n+3}\\) converge or diverge?
1.  Does \\(\sum_{m=2}^\infty\frac{5^m}{m!}\\) converge or diverge?
1.  Does \\(\sum_{n=0}^\infty(-1)^n\frac{n!}{2^n(n+2)!}\\) converge or diverge?
1.  Does \\(\sum_{p=0}^\infty\frac{3^p}{(p+7)^p}\\) converge or diverge?
1.  Does \\(\sum_{n=9}^\infty(1+\frac{2}{n})^{n^2}\\) converge or diverge?
    (Hint: \\(e^x=\lim_{n\to\infty}(1+\frac{x}{n})^n\\).)
1.  Does \\(\sum_{j=3}^\infty(-3)^j\frac{1}{j4^j}\\) converge or diverge?
1.  Does \\(\sum_{n=1}^\infty\left(\frac{1-4n^2}{(n+1)(3n+1)}\right)^{n+3}\\)
    converge or diverge?
1.  (OPTIONAL)
    Does \\(\sum_{m=4}^\infty(-1)^{m+1}\frac{me^{-m}}{(2m+1)\ln(m+1)}\\)
    converge or diverge?
1.  (QUIZ)
    Does \\(\sum_{n=1}^\infty\frac{(n-1)!}{10^n}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It explodes.
1.  (QUIZ)
    Does \\(\sum_{k=3}^\infty(1-\frac{1}{k})^{k^2}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It converges some of the time, and diverges the rest of the time.
1.  (QUIZ)
    Does \\(\sum_{m=2}^\infty\frac{1}{m^2}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It is impossible to determine.

[Solutions]({{site.baseurl}}public/solutions/5.7.pdf)
