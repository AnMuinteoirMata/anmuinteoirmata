---
layout: default
title: Differentiation
---

<div>
  <h2>Differentiation</h2>

  <p>Differentiation is a way of finding the rate of change of a function. It helps us calculate gradients, tangents, maxima/minima, and solve real-world problems involving change.</p>

  <hr>

  <h3>1. Basic Derivative Rules</h3>
  <p>For a function \( f(x) = x^n \), the derivative is:</p>
  <div>$$
  \frac{d}{dx}x^n = nx^{n - 1}
  $$</div>

  <p><strong>Other common derivatives:</strong></p>
  <ul>
    <li>\( \frac{d}{dx}[\sin x] = \cos x \)</li>
    <li>\( \frac{d}{dx}[\cos x] = -\sin x \)</li>
    <li>\( \frac{d}{dx}[e^x] = e^x \)</li>
    <li>\( \frac{d}{dx}[\ln x] = \frac{1}{x} \)</li>
  </ul>

  <p><strong>Example:</strong> Differentiate \( f(x) = x^3 + 2x - 7 \)</p>
  <div>$$
  f'(x) = 3x^2 + 2
  $$</div>

  <hr>

  <h3>2. The Constant Rule</h3>
  <p>The derivative of a constant is 0:</p>
  <div>$$
  \frac{d}{dx}[c] = 0
  $$</div>
  <p><strong>Example:</strong> \( f(x) = 8 \Rightarrow f'(x) = 0 \)</p>

  <hr>

  <h3>3. The Sum and Difference Rule</h3>
  <p>The derivative of a sum/difference is the sum/difference of the derivatives:</p>
  <div>$$
  \frac{d}{dx}[f(x) \pm g(x)] = f'(x) \pm g'(x)
  $$</div>

  <p><strong>Example:</strong> \( f(x) = x^2 + 5x - 3 \)</p>
  <div>$$
  f'(x) = 2x + 5
  $$</div>

  <hr>

  <h3>4. The Product Rule</h3>
  <p>Used when two functions are multiplied:</p>
  <div>$$
  \frac{d}{dx}[f(x)g(x)] = f'(x)g(x) + f(x)g'(x)
  $$</div>

  <p><strong>Example:</strong> \( f(x) = x \cdot \sin x \)</p>
  <div>$$
  f'(x) = 1 \cdot \sin x + x \cdot \cos x = \sin x + x \cos x
  $$</div>

  <hr>

  <h3>5. The Quotient Rule</h3>
  <p>Used when dividing two functions:</p>
  <div>$$
  \frac{d}{dx} \left[ \frac{f(x)}{g(x)} \right] = \frac{f'(x)g(x) - f(x)g'(x)}{[g(x)]^2}
  $$</div>

  <p><strong>Example:</strong> \( f(x) = \frac{x^2}{x + 1} \)</p>
  <div>$$
  f'(x) = \frac{2x(x + 1) - x^2(1)}{(x + 1)^2} = \frac{2x^2 + 2x - x^2}{(x + 1)^2} = \frac{x^2 + 2x}{(x + 1)^2}
  $$</div>

  <hr>

  <h3>6. The Chain Rule</h3>
  <p>Used for functions inside other functions (composite functions):</p>
  <div>$$
  \frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x)
  $$</div>

  <p><strong>Example:</strong> \( f(x) = (3x + 2)^5 \)</p>
  <div>$$
  f'(x) = 5(3x + 2)^4 \cdot 3 = 15(3x + 2)^4
  $$</div>

  <hr>

  <h3>7. Finding the Gradient</h3>
  <p>The derivative of a function gives the gradient (slope) at any point.</p>

  <p><strong>Example:</strong> \( f(x) = x^2 - 4x \). Find the gradient at \( x = 3 \):</p>
  <div>$$
  f'(x) = 2x - 4,\quad f'(3) = 2(3) - 4 = 2
  $$</div>

  <hr>

  <h3>8. Tangents and Normals</h3>
  <p>The gradient of the tangent at a point is \( f'(x) \). The gradient of the normal is the negative reciprocal.</p>

  <p><strong>Example:</strong> Find the equation of the tangent to \( f(x) = x^2 \) at \( x = 2 \)</p>
  <ul>
    <li>Point: \( (2, f(2)) = (2, 4) \)</li>
    <li>Gradient: \( f'(x) = 2x \Rightarrow f'(2) = 4 \)</li>
    <li>Use point-slope: \( y - 4 = 4(x - 2) \Rightarrow y = 4x - 4 \)</li>
  </ul>

  <hr>

  <h3>9. Stationary Points</h3>
  <p>These occur where \( f'(x) = 0 \).</p>
  <ul>
    <li>If \( f''(x) > 0 \): local minimum</li>
    <li>If \( f''(x) < 0 \): local maximum</li>
    <li>If \( f''(x) = 0 \): test further (could be point of inflection)</li>
  </ul>

  <p><strong>Example:</strong> \( f(x) = x^3 - 6x^2 + 9x \)</p>
  <ul>
    <li>\( f'(x) = 3x^2 - 12x + 9 \)</li>
    <li>Set to 0: \( 3x^2 - 12x + 9 = 0 \Rightarrow x = 1 \text{ or } 3 \)</li>
    <li>Second derivative: \( f''(x) = 6x - 12 \)</li>
    <li>\( f''(1) = -6 \) → max, \( f''(3) = 6 \) → min</li>
  </ul>

  <hr>

  <h3>10. Applications</h3>
  <ul>
    <li>Maximise profit or area</li>
    <li>Minimise cost or time</li>
    <li>Model speed, acceleration, or rates of change in real-world problems</li>
  </ul>

  <p><strong>Example:</strong> A box with square base and no lid is to be made from 48 cm² of material. Maximise volume.</p>
  <p>(This is a classic Leaving Cert question — full solution would follow using a function for volume in terms of one variable, then find maximum using derivative)</p>

</div>
