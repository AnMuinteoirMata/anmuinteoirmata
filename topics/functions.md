---
layout: default
title: Functions
---

<div>
  <h2>Functions</h2>

  <p>Functions are rules that assign exactly one output to each input. In this chapter, we will cover the definition of a function, domain and range, function notation, composition of functions, inverses, and graphical interpretation.</p>

  <hr>

  <h3>1. What Is a Function?</h3>
  <p>A function is a rule that maps each input to one and only one output.</p>
  <p>We usually write: \( f(x) = \text{some expression in } x \)</p>

  <p><strong>Example:</strong> \( f(x) = x^2 + 3 \)</p>
  <p>Then \( f(2) = 2^2 + 3 = 7 \)</p>

  <hr>

  <h3>2. Domain and Range</h3>
  <p>The <strong>domain</strong> is the set of all possible inputs.</p>
  <p>The <strong>range</strong> is the set of all possible outputs.</p>

  <p><strong>Example:</strong> For \( f(x) = \frac{1}{x - 4} \)</p>
  <ul>
    <li>Domain: all real numbers except 4 (since division by 0 is undefined)</li>
    <li>Range: all real numbers except 0 (the function never equals 0)</li>
  </ul>

  <hr>

  <h3>3. Function Notation</h3>
  <p>Instead of writing \( y = 2x + 1 \), we often write \( f(x) = 2x + 1 \).</p>
  <p>This means "the function f takes input x and gives output \(2x + 1\)".</p>

  <p><strong>Example:</strong> If \( f(x) = 2x + 1 \), find \( f(4) \):</p>
  <div>$$
  f(4) = 2(4) + 1 = 9
  $$</div>

  <hr>

  <h3>4. Composition of Functions</h3>
  <p>Combining two functions: if \( f(x) \) and \( g(x) \) are functions, then:</p>
  <div>$$
  (f \circ g)(x) = f(g(x))
  $$</div>

  <p><strong>Example:</strong> Let \( f(x) = 2x \), \( g(x) = x + 3 \). Find \( f(g(x)) \):</p>
  <div>$$
  f(g(x)) = f(x + 3) = 2(x + 3) = 2x + 6
  $$</div>

  <hr>

  <h3>5. Inverse Functions</h3>
  <p>An inverse function undoes the original function.</p>
  <p>Notation: \( f^{-1}(x) \)</p>
  <p>To find the inverse:</p>
  <ul>
    <li>Step 1: Replace \( f(x) \) with \( y \)</li>
    <li>Step 2: Swap \( x \) and \( y \)</li>
    <li>Step 3: Solve for \( y \)</li>
    <li>Step 4: Rewrite as \( f^{-1}(x) \)</li>
  </ul>

  <p><strong>Example:</strong> \( f(x) = 3x + 1 \)</p>
  <div>$$
  y = 3x + 1 \Rightarrow x = 3y + 1 \Rightarrow y = \frac{x - 1}{3} \Rightarrow f^{-1}(x) = \frac{x - 1}{3}
  $$</div>

  <hr>

  <h3>6. Graphs of Functions</h3>
  <p>The graph of a function shows the relationship between \(x\) and \(f(x)\).</p>
  <ul>
    <li>Vertical Line Test: If any vertical line touches a graph more than once, it is not a function.</li>
    <li>To graph inverse functions, reflect the graph of \(f(x)\) in the line \(y = x\).</li>
  </ul>

  <p><strong>Example:</strong> Sketch \(f(x) = x^2\) and its inverse.</p>
  <p>Note: The inverse of \(f(x) = x^2\) is not a function unless restricted to \(x \geq 0\).</p>

  <!-- Insert graph: y = x^2 and y = sqrt(x) -->

  <hr>

  <h3>7. Even and Odd Functions</h3>
  <ul>
    <li><strong>Even:</strong> \( f(-x) = f(x) \) (symmetric about y-axis)</li>
    <li><strong>Odd:</strong> \( f(-x) = -f(x) \) (symmetric about origin)</li>
  </ul>

  <p><strong>Example:</strong> \( f(x) = x^2 \) is even because \( f(-x) = (-x)^2 = x^2 \)</p>
  <p><strong>Example:</strong> \( f(x) = x^3 \) is odd because \( f(-x) = (-x)^3 = -x^3 = -f(x) \)</p>

  <hr>

  <h3>8. Piecewise Functions</h3>
  <p>These are functions defined by different expressions depending on the value of \(x\).</p>

  <p><strong>Example:</strong></p>
  <div>$$
  f(x) = \begin{cases}
    x^2 & \text{if } x < 0 \\
    2x + 1 & \text{if } x \geq 0
  \end{cases}
  $$</div>

  <p>To graph this function, draw each piece in its respective domain.</p>

</div>
