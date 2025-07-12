---
layout: default
title: Inequalities
---

<div>
  <h2>Inequalities</h2>

  <hr>

  <h3>1. Inequality Notation</h3>
  <ul>
    <li>\(>\): greater than</li>
    <li>\(<\): less than</li>
    <li>\(\geq\): greater than or equal to</li>
    <li>\(\leq\): less than or equal to</li>
    <li>\(\neq\): not equal to</li>
  </ul>

  <p><strong>Example:</strong> \(x > 3\) means \(x\) is any number greater than 3 (not including 3).</p>

  <hr>

  <h3>2. Properties of Inequalities</h3>
  <ul>
    <li>You can add or subtract the same number on both sides.</li>
    <li>You can multiply or divide both sides by a **positive** number.</li>
    <li>But if you multiply or divide by a **negative** number, you must reverse the inequality sign.</li>
  </ul>

  <p><strong>Example:</strong> Solve: \(-2x < 6\)</p>
  <p>Divide both sides by -2 (reverse the sign):</p>
  <div>$$
  x > -3
  $$</div>

  <hr>

  <h3>3. Linear Inequalities</h3>
  <p>These involve linear expressions, just like solving regular equations.</p>
  <p><strong>Example:</strong> Solve \(3x - 4 \leq 11\):</p>
  <div>$$
  3x \leq 15 \Rightarrow x \leq 5
  $$</div>

  <hr>

  <h3>4. Quadratic Inequalities</h3>
  <p>Solve like a quadratic equation, then test values in each region between the roots.</p>

  <p><strong>Example:</strong> Solve \(x^2 - 4x - 5 < 0\)</p>
  <p>Factor: \((x - 5)(x + 1) < 0\)</p>

  <p>Roots are \(x = -1\) and \(x = 5\). Test values in the intervals:</p>
  <ul>
    <li>\(x < -1\): pick \(x = -2\): \((-2 - 5)(-2 + 1) = (-7)(-1) = +7\) → not valid</li>
    <li>\(-1 < x < 5\): pick \(x = 0\): \((0 - 5)(0 + 1) = (-5)(1) = -5\) → valid</li>
    <li>\(x > 5\): pick \(x = 6\): \((6 - 5)(6 + 1) = (1)(7) = 7\) → not valid</li>
  </ul>

  <p><strong>Answer:</strong> \(-1 < x < 5\)</p>

  <hr>

  <h3>5. Rational Inequalities</h3>
  <p>Inequalities involving fractions — multiply across carefully and consider restrictions where the denominator is zero.</p>

  <p><strong>Example:</strong> Solve \(\frac{x + 1}{x - 2} > 0\)</p>
  <p>Critical points: \(x = -1\) (numerator zero), \(x = 2\) (denominator zero, undefined)</p>

  <p>Test values in the regions:</p>
  <ul>
    <li>\(x < -1\): try \(x = -2\): \(\frac{-1}{-4} = \frac{1}{4} > 0\) → valid</li>
    <li>\(-1 < x < 2\): try \(x = 0\): \(\frac{1}{-2} = -\frac{1}{2}\) → not valid</li>
    <li>\(x > 2\): try \(x = 3\): \(\frac{4}{1} = 4\) → valid</li>
  </ul>

  <p><strong>Answer:</strong> \(x < -1\) or \(x > 2\)</p>

  <hr>

  <h3>6. Abstract Inequalities</h3>
  <p>These involve expressions and parameters like \(a\), \(b\), or general reasoning.</p>
  <p><strong>Example:</strong> Prove that for all \(x \in \mathbb{R}\), \(x^2 + 1 > 0\)</p>
  <p>Since \(x^2 \geq 0\) for all real numbers, \(x^2 + 1 \geq 1 > 0\)</p>
  <p><strong>Conclusion:</strong> Always positive — inequality is true for all real \(x\)</p>

  <hr>

  <h3>7. Absolute Value (Modulus)</h3>
  <p>The modulus \(|x|\) means the distance of \(x\) from zero. So \(|x| = x\) if \(x \geq 0\), and \(|x| = -x\) if \(x < 0\).</p>

  <h4>Example (Equation):</h4>
  <p>Solve \(|x - 3| = 5\)</p>
  <p>Split into two cases:</p>
  <ul>
    <li>\(x - 3 = 5 \Rightarrow x = 8\)</li>
    <li>\(x - 3 = -5 \Rightarrow x = -2\)</li>
  </ul>
  <p><strong>Answer:</strong> \(x = -2\) or \(x = 8\)</p>

  <h4>Example (Inequality):</h4>
  <p>Solve \(|x - 4| < 3\)</p>
  <p>This becomes:</p>
  <div>$$
  -3 < x - 4 < 3
  $$</div>
  <div>Add 4 to all parts:</div>
  <div>$$
  1 < x < 7
  $$</div>

</div>
