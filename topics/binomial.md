---
layout: default
title: Binomial Theorem
---

<div>
  <h2>Binomial Theorem</h2>

  <hr>

  <h3>1. What is a Binomial?</h3>
  <p>A binomial is an expression with two terms, like \((a + b)\) or \((x - 2)\).</p>
  <p>The Binomial Theorem helps us expand expressions of the form \((a + b)^n\) without multiplying everything out manually.</p>

  <hr>

  <h3>2. Binomial Coefficients</h3>
  <p>In the expansion of \((a + b)^n\), the numbers in front of each term are called binomial coefficients.</p>
  <p>They come from Pascal’s Triangle or can be calculated using combinations:</p>
  <div>$$
  \binom{n}{r} = \frac{n!}{r!(n - r)!}
  $$</div>

  <p><strong>Examples:</strong></p>
  <ul>
    <li>\(\binom{4}{0} = 1,\quad \binom{4}{1} = 4,\quad \binom{4}{2} = 6,\quad \binom{4}{3} = 4,\quad \binom{4}{4} = 1\)</li>
  </ul>

  <hr>

  <h3>3. Binomial Expansion Formula</h3>
  <p>The full expansion of \((a + b)^n\) is given by:</p>
  <div>$$
  (a + b)^n = \sum_{r = 0}^{n} \binom{n}{r} a^{n - r} b^r
  $$</div>

  <p><strong>Example:</strong> Expand \((x + 2)^3\)</p>
  <p>Use \(n = 3,\ a = x,\ b = 2\)</p>
  <div>$$
  = \binom{3}{0}x^3(2)^0 + \binom{3}{1}x^2(2)^1 + \binom{3}{2}x^1(2)^2 + \binom{3}{3}x^0(2)^3
  $$</div>
  <div>$$
  = 1x^3 + 3x^2(2) + 3x(4) + 1(8) = x^3 + 6x^2 + 12x + 8
  $$</div>

  <hr>

  <h3>4. The General Term</h3>
  <p>The general term (also called the \(r^{\text{th}}\) term or \(T_{r+1}\)) in the expansion of \((a + b)^n\) is:</p>
  <div>$$
  T_{r+1} = \binom{n}{r} a^{n - r} b^r
  $$</div>

  <p><strong>Example:</strong> Find the 3rd term in the expansion of \((2x - 3)^5\)</p>
  <p>This is \(T_3\), so \(r = 2\), \(a = 2x\), \(b = -3\), \(n = 5\)</p>
  <div>$$
  T_3 = \binom{5}{2}(2x)^{5 - 2}(-3)^2 = 10 \cdot (2x)^3 \cdot 9 = 10 \cdot 8x^3 \cdot 9 = 720x^3
  $$</div>

  <hr>

  <h3>5. Special Cases</h3>
  <ul>
    <li><strong>Binomial with subtraction:</strong> \((a - b)^n\) works the same, but the signs alternate.</li>
    <li><strong>Fractional or negative powers:</strong> There is a more advanced version called the Binomial Series (not usually required at second level).</li>
  </ul>

</div>
