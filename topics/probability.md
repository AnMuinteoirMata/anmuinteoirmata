---
layout: default
title: Probability
---

<div>
  <h2>Probability</h2>

  <hr>

  <h3>1. Basics of Probability</h3>
  <p>Probability measures how likely something is to happen. It ranges from 0 (impossible) to 1 (certain).</p>

  <div>$$
  \text{Probability of an event} = \frac{\text{Number of favourable outcomes}}{\text{Total number of possible outcomes}}
  $$</div>

  <p><strong>Example:</strong> What is the probability of rolling a 4 on a fair 6-sided die?</p>
  <div>$$
  P(4) = \frac{1}{6}
  $$</div>

  <p><strong>Example:</strong> What is the probability of drawing a red card from a deck of 52 cards?</p>
  <div>$$
  P(\text{red}) = \frac{26}{52} = \frac{1}{2}
  $$</div>

  <hr>

  <h3>2. Probability Rules</h3>
  <ul>
    <li><strong>Rule 1:</strong> \(0 \leq P(A) \leq 1\)</li>
    <li><strong>Rule 2 (Complement Rule):</strong> \(P(\text{not A}) = 1 - P(A)\)</li>
    <li><strong>Rule 3 (Addition Rule):</strong> \(P(A \cup B) = P(A) + P(B) - P(A \cap B)\)</li>
    <li><strong>Rule 4 (Mutually Exclusive):</strong> If \(A\) and \(B\) can't both happen, then \(P(A \cup B) = P(A) + P(B)\)</li>
    <li><strong>Rule 5 (Independent Events):</strong> \(P(A \cap B) = P(A) \times P(B)\)</li>
  </ul>

  <p><strong>Example:</strong> A coin is tossed and a die is rolled. What is the probability of getting heads and a 6?</p>
  <div>$$
  P(\text{heads}) = \frac{1}{2},\quad P(6) = \frac{1}{6} \Rightarrow P = \frac{1}{2} \cdot \frac{1}{6} = \frac{1}{12}
  $$</div>

  <hr>

  <h3>3. Tree Diagrams</h3>
  <p>Tree diagrams help list all possible outcomes, especially for multi-stage events.</p>

  <p><strong>Example:</strong> A coin is tossed twice. Draw the tree and find the probability of getting exactly one head.</p>
  <ul>
    <li>Outcomes: HH, HT, TH, TT</li>
    <li>Exactly one head: HT, TH → 2 out of 4 outcomes</li>
  </ul>

  <div>$$
  P(\text{1 head}) = \frac{2}{4} = \frac{1}{2}
  $$</div>

  <hr>

  <h3>4. Expected Value</h3>
  <p>The expected value is the average outcome you'd expect from many trials. Multiply each outcome by its probability and add them.</p>

  <div>$$
  E(X) = \sum x \cdot P(x)
  $$</div>

  <p><strong>Example:</strong> A game has the following payouts:</p>
  <ul>
    <li>Win €5 with probability 0.2</li>
    <li>Win €2 with probability 0.3</li>
    <li>Lose €3 with probability 0.5</li>
  </ul>

  <p>Expected value:</p>
  <div>$$
  E = (5)(0.2) + (2)(0.3) + (-3)(0.5) = 1 + 0.6 - 1.5 = 0.1
  $$</div>
  <p><strong>Conclusion:</strong> On average, you win 10 cents per game.</p>

  <hr>

  <h3>5. Probability Distributions</h3>
  <p>A probability distribution lists all possible outcomes of a random variable and their probabilities.</p>

  <p><strong>Example:</strong> Roll a fair die. Define \(X =\) number rolled.</p>
  <ul>
    <li>\(P(X = 1) = \frac{1}{6}, P(X = 2) = \frac{1}{6},\dots,P(X = 6) = \frac{1}{6}\)</li>
  </ul>

  <p>The sum of all probabilities must be 1.</p>

  <hr>

  <h3>6. Binomial Probability</h3>
  <p>The binomial distribution models the number of successes in a fixed number of independent trials with two possible outcomes (success/failure).</p>

  <ul>
    <li><strong>Formula:</strong> 
      <div>$$
      P(X = r) = \binom{n}{r} p^r (1 - p)^{n - r}
      $$</div>
    </li>
  </ul>

  <p>Where:</p>
  <ul>
    <li>\(n\) = number of trials</li>
    <li>\(r\) = number of successes</li>
    <li>\(p\) = probability of success</li>
  </ul>

  <p><strong>Example:</strong> Toss a coin 4 times. What's the probability of getting exactly 3 heads?</p>
  <p>\(n = 4,\ r = 3,\ p = \frac{1}{2}\)</p>

  <div>$$
  P(X = 3) = \binom{4}{3} \left(\frac{1}{2}\right)^3 \left(\frac{1}{2}\right)^1 = 4 \cdot \frac{1}{8} \cdot \frac{1}{2} = \frac{1}{4}
  $$</div>

  <hr>

  <h3>7. Bernoulli Trials</h3>
  <p>A Bernoulli trial is a random experiment with exactly two possible outcomes: success and failure.</p>
  <ul>
    <li>Each trial is independent</li>
    <li>The probability of success \(p\) stays the same each time</li>
  </ul>

  <p>Bernoulli trials form the basis of the binomial distribution.</p>

  <p><strong>Example:</strong> Tossing a coin once is a Bernoulli trial: success = heads, failure = tails</p>
  <p><strong>Example:</strong> Tossing a coin 5 times = 5 Bernoulli trials → binomial distribution applies</p>

</div>
