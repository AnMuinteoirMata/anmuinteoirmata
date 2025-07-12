---
layout: default
title: Integration
---

<div>
  <h2>Integration</h2>

  <p>Integration is the reverse of differentiation. It allows us to find areas, volumes, and original functions from rates of change. It is a key concept in calculus.</p>

  <hr>

  <h3>1. Basic Integration Rule</h3>
  <p>If \( \frac{d}{dx} [x^n] = nx^{n - 1} \), then the reverse is:</p>
  <div>$$
  \int x^n \, dx = \frac{x^{n+1}}{n + 1} + C,\quad \text{(for } n \ne -1\text{)}
  $$</div>
  <p>\( C \) is the constant of integration.</p>

  <p><strong>Example:</strong> \( \int x^3 \, dx = \frac{x^4}{4} + C \)</p>

  <hr>

  <h3>2. Integrating Basic Functions</h3>
  <ul>
    <li>\( \int k \, dx = kx + C \)</li>
    <li>\( \int \sin x \, dx = -\cos x + C \)</li>
    <li>\( \int \cos x \, dx = \sin x + C \)</li>
    <li>\( \int e^x \, dx = e^x + C \)</li>
    <li>\( \int \frac{1}{x} \, dx = \ln|x| + C \)</li>
  </ul>

  <p><strong>Example:</strong> \( \int (2x^2 + 3) \, dx = \frac{2x^3}{3} + 3x + C \)</p>

  <hr>

  <h3>3. Definite Integrals</h3>
  <p>To evaluate an integral between two limits \(a\) and \(b\):</p>
  <div>$$
  \int_a^b f(x) \, dx = F(b) - F(a)
  $$</div>
  <p>Where \(F(x)\) is the antiderivative of \(f(x)\).</p>

  <p><strong>Example:</strong> \( \int_1^3 x^2 \, dx = \left[\frac{x^3}{3}\right]_1^3 = \frac{27}{3} - \frac{1}{3} = \frac{26}{3} \)</p>

  <hr>

  <h3>4. Area Under a Curve</h3>
  <p>The definite integral gives the area between the curve and the x-axis from \(a\) to \(b\).</p>

  <p><strong>Example:</strong> Find the area under \( f(x) = x + 1 \) from \( x = 0 \) to \( x = 2 \):</p>
  <div>$$
  \int_0^2 (x + 1) \, dx = \left[\frac{x^2}{2} + x\right]_0^2 = \left(2 + 2\right) - 0 = 4
  $$</div>

  <p><strong>Note:</strong> If part of the curve is below the x-axis, the integral will be negative — so you may need to break it up and add absolute values to get the total area.</p>

  <hr>

  <h3>5. Area Between Two Curves</h3>
  <p>If \(f(x)\) is above \(g(x)\) on the interval \([a, b]\), then:</p>
  <div>$$
  \text{Area} = \int_a^b [f(x) - g(x)] \, dx
  $$</div>

  <p><strong>Example:</strong> Find the area between \(f(x) = x^2 + 1\) and \(g(x) = x\) from \(x = 0\) to \(x = 1\):</p>
  <div>$$
  \int_0^1 [(x^2 + 1) - x] \, dx = \int_0^1 (x^2 - x + 1) \, dx = \left[\frac{x^3}{3} - \frac{x^2}{2} + x\right]_0^1
  $$</div>
  <div>$$
  = \left(\frac{1}{3} - \frac{1}{2} + 1\right) = \frac{5}{6}
  $$</div>

  <hr>

  <h3>6. Applications of Integration</h3>
  <ul>
    <li>Find distance from velocity: \( \int v(t)\, dt \)</li>
    <li>Find displacement: \( \int a(t)\, dt \) (if acceleration is given)</li>
    <li>Find original function: if rate of change is known, integrate to get original</li>
  </ul>

  <p><strong>Example:</strong> A particle has velocity \( v(t) = 3t^2 \). Find distance travelled in first 2 seconds.</p>
  <div>$$
  \int_0^2 3t^2 \, dt = 3 \cdot \left[\frac{t^3}{3}\right]_0^2 = 8 \text{ units}
  $$</div>

  <hr>

  <h3>7. Average Value of a Function</h3>
  <p>The average value of \( f(x) \) on \([a, b]\) is:</p>
  <div>$$
  \text{Average} = \frac{1}{b - a} \int_a^b f(x) \, dx
  $$</div>

  <p><strong>Example:</strong> Find the average value of \( f(x) = x^2 \) from 1 to 3:</p>
  <div>$$
  \text{Average} = \frac{1}{2} \int_1^3 x^2 \, dx = \frac{1}{2} \cdot \frac{26}{3} = \frac{13}{3}
  $$</div>

</div>
