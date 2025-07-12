---
layout: default
title: Sequences and Series
---

<div>
  <h2>Sequences and Series</h2>

  <hr>

  <h3>1. What Is a Sequence?</h3>
  <p>A sequence is an ordered list of numbers that follow a pattern.</p>
  <p>Each number in the list is called a term. The \(n\)th term is usually written as \(T_n\) or \(a_n\).</p>

  <p><strong>Example:</strong> The sequence 2, 4, 6, 8, ... adds 2 each time. It’s an arithmetic sequence.</p>

  <hr>

  <h3>2. Arithmetic Sequences</h3>
  <p>Each term increases (or decreases) by a common difference \(d\).</p>
  <ul>
    <li>First term: \(a\)</li>
    <li>Common difference: \(d\)</li>
    <li>\(n\)th term: \(T_n = a + (n - 1)d\)</li>
  </ul>

  <p><strong>Example:</strong> First term \(a = 5\), difference \(d = 3\). Find the 10th term:</p>
  <div>$$
  T_{10} = 5 + (10 - 1)(3) = 5 + 27 = 32
  $$</div>

  <hr>

  <h3>3. Sum of Arithmetic Series</h3>
  <p>The sum of the first \(n\) terms of an arithmetic sequence is:</p>
  <div>$$
  S_n = \frac{n}{2}(2a + (n - 1)d)
  $$</div>
  <p>Or: \(S_n = \frac{n}{2}(a + l)\), where \(l\) is the last term.</p>

  <p><strong>Example:</strong> Find the sum of the first 20 terms of the sequence: 7, 10, 13, ...</p>
  <div>$$
  a = 7,\ d = 3,\ n = 20
  $$</div>
  <div>$$
  S_{20} = \frac{20}{2}(2 \cdot 7 + (20 - 1) \cdot 3) = 10(14 + 57) = 10(71) = 710
  $$</div>

  <hr>

  <h3>4. Geometric Sequences</h3>
  <p>Each term is multiplied by a common ratio \(r\).</p>
  <ul>
    <li>First term: \(a\)</li>
    <li>Common ratio: \(r\)</li>
    <li>\(n\)th term: \(T_n = ar^{n - 1}\)</li>
  </ul>

  <p><strong>Example:</strong> \(a = 2\), \(r = 3\), find the 5th term:</p>
  <div>$$
  T_5 = 2 \cdot 3^{4} = 2 \cdot 81 = 162
  $$</div>

  <hr>

  <h3>5. Sum of a Geometric Series</h3>
  <p>The sum of the first \(n\) terms of a geometric series is:</p>
  <div>$$
  S_n = \frac{a(1 - r^n)}{1 - r},\quad \text{if } r \neq 1
  $$</div>

  <p><strong>Example:</strong> Find the sum of the first 4 terms of: 3, 6, 12, 24, ...</p>
  <div>$$
  a = 3,\ r = 2,\ n = 4
  $$</div>
  <div>$$
  S_4 = \frac{3(1 - 2^4)}{1 - 2} = \frac{3(1 - 16)}{-1} = \frac{-45}{-1} = 45
  $$</div>

  <hr>

  <h3>6. Infinite Geometric Series</h3>
  <p>If \(|r| < 1\), the geometric series has a limiting sum:</p>
  <div>$$
  S_\infty = \frac{a}{1 - r}
  $$</div>

  <p><strong>Example:</strong> Sum the infinite series: \(5 + 2.5 + 1.25 + \dots\)</p>
  <div>$$
  a = 5,\ r = 0.5,\ S_\infty = \frac{5}{1 - 0.5} = \frac{5}{0.5} = 10
  $$</div>

  <hr>

  <h3>7. Recurrence Relations</h3>
  <p>A recurrence relation gives each term based on the previous one.</p>
  <p><strong>Example:</strong> \(T_1 = 2,\ T_{n+1} = T_n + 3\)</p>
  <ul>
    <li>\(T_2 = 2 + 3 = 5\)</li>
    <li>\(T_3 = 5 + 3 = 8\)</li>
    <li>This is an arithmetic sequence with \(d = 3\)</li>
  </ul>

  <hr>

  <h3>8. Sigma Notation</h3>
  <p>Used to write the sum of a series compactly:</p>
  <div>$$
  \sum_{k=1}^{n} T_k
  $$</div>

  <p><strong>Example:</strong> \(\sum_{k=1}^{4} (2k + 1) = 3 + 5 + 7 + 9 = 24\)</p>

  <hr>

  <h3>9. Applications and Problem Solving</h3>
  <p>Sequences and series are used in finance, population models, and patterns in nature.</p>

  <p><strong>Example:</strong> A machine depreciates 20% per year. Original cost is €10,000. What is its value after 5 years?</p>
  <div>$$
  a = 10000,\ r = 0.8,\ n = 5
  $$</div>
  <div>$$
  T_5 = 10000 \cdot 0.8^{4} = 10000 \cdot 0.4096 = 4096
  $$</div>

</div>
