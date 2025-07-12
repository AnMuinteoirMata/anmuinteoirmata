---
layout: default
title: Quadratic and Cubic Equations
---

<div>
  <h2>Quadratic and Cubic Equations</h2>

  <hr>

  <h3>1. What is a Quadratic Equation?</h3>
  <p>A quadratic equation is a polynomial of degree 2. It has the form:</p>
  <div>$$
  ax^2 + bx + c = 0
  $$</div>
  <p>where \(a\), \(b\), and \(c\) are numbers and \(a \neq 0\).</p>

  <hr>

  <h3>2. Solving by Factorising</h3>
  <p>Find two numbers that multiply to give \(ac\) and add to give \(b\).</p>
  <p><strong>Example:</strong> Solve \(x^2 + 5x + 6 = 0\)</p>
  <div>$$
  (x + 2)(x + 3) = 0 \Rightarrow x = -2, -3
  $$</div>

  <hr>

  <h3>3. Solving by Completing the Square</h3>
  <p>Rewrite the equation in the form \((x + p)^2 = q\) and then solve.</p>
  <p><strong>Example:</strong> Solve \(x^2 + 6x + 2 = 0\)</p>
  <div>$$
  x^2 + 6x + 9 - 9 + 2 = (x + 3)^2 - 7 = 0
  $$</div>
  <div>$$
  (x + 3)^2 = 7 \Rightarrow x + 3 = \pm \sqrt{7} \Rightarrow x = -3 \pm \sqrt{7}
  $$</div>

  <hr>

  <h3>4. Solving by the Quadratic Formula</h3>
  <p>Use the formula:</p>
  <div>$$
  x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
  $$</div>
  <p><strong>Example:</strong> Solve \(2x^2 + 3x - 2 = 0\)</p>
  <p>\(a = 2, b = 3, c = -2\)</p>
  <div>$$
  x = \frac{-3 \pm \sqrt{3^2 - 4(2)(-2)}}{2(2)} = \frac{-3 \pm \sqrt{9 + 16}}{4} = \frac{-3 \pm \sqrt{25}}{4} = \frac{-3 \pm 5}{4}
  $$</div>
  <div>$$
  x = \frac{2}{4} = \frac{1}{2} \quad \text{or} \quad x = \frac{-8}{4} = -2
  $$</div>

  <hr>

  <h3>5. The Factor Theorem</h3>
  <p>The Factor Theorem says that if \(f(a) = 0\), then \((x - a)\) is a factor of the polynomial.</p>
  <p><strong>Example:</strong> If \(f(x) = x^3 - 4x^2 + x + 6\), and \(f(1) = 0\), then \((x - 1)\) is a factor.</p>

  <hr>

  <h3>6. What is a Cubic Equation?</h3>
  <p>A cubic equation is a polynomial of degree 3. It has the form:</p>
  <div>$$
  ax^3 + bx^2 + cx + d = 0
  $$</div>
  <p>It may have one, two, or three real roots.</p>

  <hr>

  <h3>7. Algebraic Division of a Cubic</h3>
  <p>Once a factor is known (e.g. from the Factor Theorem), divide the cubic by that factor to simplify.</p>
  <p>Use long division or synthetic division.</p>

  <p><strong>Example:</strong> Divide \(x^3 - 4x^2 + x + 6\) by \((x - 1)\):</p>

  <div>Set up long division:</div>
  <div>Step 1: \(x^3 ÷ x = x^2\)</div>
  <div>Multiply: \(x^2(x - 1) = x^3 - x^2\)</div>
  <div>Subtract: \((x^3 - 4x^2) - (x^3 - x^2) = -3x^2\)</div>
  <div>Repeat the process:</div>
  <div>Divide \(-3x^2 ÷ x = -3x\), and continue...</div>

  <p>Final result:</p>
  <div>$$
  x^3 - 4x^2 + x + 6 = (x - 1)(x^2 - 3x - 6)
  $$</div>
  <p>Now solve the quadratic using your preferred method.</p>

</div>
