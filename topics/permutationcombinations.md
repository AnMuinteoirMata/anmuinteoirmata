---
layout: default
title: Permutations and Combinations
---

<div>
  <h2>Permutations and Combinations</h2>

  <hr>

  <h3>1. Fundamental Principle of Counting</h3>
  <p>If one task can be done in \(m\) ways and another in \(n\) ways, then both can be done in \(m \times n\) ways.</p>

  <p><strong>Example:</strong> You have 3 shirts and 2 pairs of trousers. The number of outfits is:</p>
  <div>$$
  3 \times 2 = 6
  $$</div>

  <hr>

  <h3>2. Permutations (Arrangements)</h3>
  <p>Permutations count the number of ways to arrange items where <strong>order matters</strong>.</p>
  <ul>
    <li><strong>Formula:</strong> \(P(n, r) = \frac{n!}{(n - r)!}\)</li>
    <li>\(n!\) means \(n \times (n-1) \times \dots \times 1\)</li>
  </ul>

  <p><strong>Example 1:</strong> How many ways can 3 students be seated in 5 chairs?</p>
  <div>$$
  P(5, 3) = \frac{5!}{(5 - 3)!} = \frac{120}{2} = 60
  $$</div>

  <p><strong>Example 2:</strong> How many ways can 4 letters be arranged?</p>
  <p>If all letters are different: \(4! = 24\)</p>

  <hr>

  <h3>3. Combinations (Selections)</h3>
  <p>Combinations count the number of ways to select items where <strong>order does not matter</strong>.</p>
  <ul>
    <li><strong>Formula:</strong> \(C(n, r) = \binom{n}{r} = \frac{n!}{r!(n - r)!}\)</li>
  </ul>

  <p><strong>Example:</strong> How many ways can 3 students be chosen from a group of 5?</p>
  <div>$$
  \binom{5}{3} = \frac{5!}{3! \cdot 2!} = \frac{120}{6 \cdot 2} = \frac{120}{12} = 10
  $$</div>

  <p><strong>Example:</strong> How many different lotto tickets can be made by choosing 6 numbers from 45?</p>
  <div>$$
  \binom{45}{6} = \frac{45!}{6! \cdot 39!} \approx 8,145,060
  $$</div>

  <hr>

  <h3>4. Relationship Between Permutations and Combinations</h3>
  <p>Every combination of \(r\) items can be arranged in \(r!\) ways, so:</p>
  <div>$$
  P(n, r) = C(n, r) \cdot r!
  $$</div>

  <p><strong>Example:</strong> Choose 3 students from 5 and arrange them in a line:</p>
  <p>First find combinations:</p>
  <div>$$
  \binom{5}{3} = 10
  $$</div>
  <p>Then multiply by the number of arrangements for 3 people:</p>
  <div>$$
  10 \cdot 3! = 10 \cdot 6 = 60 \text{ permutations}
  $$</div>

</div>
