---
layout: default
title: Mathematical Induction
---

<div>
  <h2>Mathematical Induction</h2>

  <hr>

  <h3>1. What is Mathematical Induction?</h3>
  <p>Mathematical induction is a method used to prove statements that are true for all natural numbers \(n\), starting from a base case and then proving that if it works for \(n = k\), it must also work for \(n = k + 1\).</p>

  <p><strong>Steps:</strong></p>
  <ol>
    <li><strong>Base Case:</strong> Prove the statement is true for the first value (usually \(n = 1\))</li>
    <li><strong>Inductive Step:</strong> Assume the statement is true for \(n = k\)</li>
    <li><strong>Prove it is true for \(n = k + 1\)</strong> using the assumption from step 2</li>
  </ol>

  <hr>

  <h3>2. Example 1: Sum of Terms of a Sequence</h3>
  <p>Prove that for all \(n \in \mathbb{N}\):</p>
  <div>$$
  1 + 2 + 3 + \dots + n = \frac{n(n+1)}{2}
  $$</div>

  <p><strong>Base Case:</strong> \(n = 1\)</p>
  <div>Left Side = 1, Right Side = \(\frac{1(1+1)}{2} = 1\) ✅</div>

  <p><strong>Inductive Step:</strong> Assume true for \(n = k\):</p>
  <div>$$
  1 + 2 + \dots + k = \frac{k(k+1)}{2}
  $$</div>

  <p><strong>Show it's true for \(n = k+1\):</strong></p>
  <div>Left Side = \(1 + 2 + \dots + k + (k+1)\)</div>
  <div>= \(\frac{k(k+1)}{2} + (k + 1)\)</div>
  <div>= \(\frac{k(k+1) + 2(k+1)}{2} = \frac{(k+1)(k+2)}{2}\)</div>

  <p>This matches the formula with \(n = k + 1\). ✅</p>

  <hr>

  <h3>3. Example 2: Divisibility Proof</h3>
  <p>Prove that \(5^n - 1\) is divisible by 4 for all \(n \in \mathbb{N}\).</p>

  <p><strong>Base Case:</strong> \(n = 1\)</p>
  <div>$$
  5^1 - 1 = 4 \Rightarrow \text{divisible by 4} ✅
  $$</div>

  <p><strong>Inductive Step:</strong> Assume \(5^k - 1\) is divisible by 4, so:</p>
  <div>$$
  5^k - 1 = 4m \text{ for some integer } m
  $$</div>

  <p><strong>Prove for \(n = k + 1\):</strong></p>
  <div>$$
  5^{k+1} - 1 = 5 \cdot 5^k - 1 = 5(5^k - 1) + 4
  $$</div>

  <p>Since \(5^k - 1 = 4m\), we get:</p>
  <div>$$
  5^{k+1} - 1 = 5(4m) + 4 = 20m + 4 = 4(5m + 1)
  $$</div>

  <p>So \(5^{k+1} - 1\) is also divisible by 4 ✅</p>

  <hr>

  <h3>4. Example 3: Inequality Proof</h3>
  <p>Prove that \(2^n \geq n + 1\) for all \(n \geq 1\)</p>

  <p><strong>Base Case:</strong> \(n = 1\)</p>
  <div>$$
  2^1 = 2,\quad 1 + 1 = 2 \Rightarrow \text{True} ✅
  $$</div>

  <p><strong>Inductive Step:</strong> Assume \(2^k \geq k + 1\)</p>
  <p><strong>Prove for \(n = k + 1\):</strong></p>
  <div>$$
  2^{k+1} = 2 \cdot 2^k \geq 2(k + 1)
  $$</div>

  <p>Now check if \(2(k + 1) \geq (k + 1) + 1\)</p>
  <div>$$
  2(k + 1) \geq k + 2 \Rightarrow \text{True for } k \geq 1
  $$</div>

  <p>Therefore, \(2^{k+1} \geq (k + 1) + 1\), so the inequality holds ✅</p>

</div>
