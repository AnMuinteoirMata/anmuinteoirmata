---
layout: default
title: Trigonometry
---

<div>
  <h2>Trigonometry</h2>

  <hr>

  <h3>1. Degrees and Radians</h3>
  <p>Angles can be measured in degrees (°) or in radians. One full circle is:</p>
  <ul>
    <li>\(360^\circ = 2\pi\) radians</li>
    <li>\(180^\circ = \pi\) radians</li>
  </ul>
  <p>To convert from degrees to radians, multiply by \(\frac{\pi}{180}\). To convert from radians to degrees, multiply by \(\frac{180}{\pi}\).</p>

  <p><strong>Example:</strong> Convert \(135^\circ\) to radians.</p>
  <div>$$
  135^\circ = \frac{135\pi}{180} = \frac{3\pi}{4} \text{ radians}
  $$</div>

  <!-- Insert Degrees-Radians Diagram -->

  <hr>

  <h3>2. Sine, Cosine, and Tangent Ratios</h3>
  <p>In a right-angled triangle, the trigonometric ratios are defined as follows for angle \(\theta\):</p>
  <ul>
    <li>\(\sin \theta = \frac{\text{opposite}}{\text{hypotenuse}}\)</li>
    <li>\(\cos \theta = \frac{\text{adjacent}}{\text{hypotenuse}}\)</li>
    <li>\(\tan \theta = \frac{\text{opposite}}{\text{adjacent}}\)</li>
  </ul>
  <p>These ratios are used to find unknown sides or angles in right-angled triangles.</p>

  <p><strong>Example:</strong> In a triangle with hypotenuse 10 cm and opposite side 6 cm:</p>
  <div>$$
  \sin \theta = \frac{6}{10} = 0.6 \Rightarrow \theta = \sin^{-1}(0.6) \approx 36.87^\circ
  $$</div>

  <!-- Insert Right-Angled Triangle Diagram -->

  <hr>

  <h3>3. Special Angles and Triangles</h3>
  <p>Certain angles have known exact trigonometric values. These include \(30^\circ\), \(45^\circ\), and \(60^\circ\).</p>
  <ul>
    <li>\(\sin 30^\circ = \frac{1}{2},\ \cos 30^\circ = \frac{\sqrt{3}}{2},\ \tan 30^\circ = \frac{1}{\sqrt{3}}\)</li>
    <li>\(\sin 45^\circ = \cos 45^\circ = \frac{1}{\sqrt{2}},\ \tan 45^\circ = 1\)</li>
    <li>\(\sin 60^\circ = \frac{\sqrt{3}}{2},\ \cos 60^\circ = \frac{1}{2},\ \tan 60^\circ = \sqrt{3}\)</li>
  </ul>
  <p>These values come from two special triangles: the 45°-45°-90° and 30°-60°-90° triangles.</p>

  <p><strong>Example:</strong> Use a 30°-60°-90° triangle where the hypotenuse is 1:</p>
  <div>$$
  \sin 30^\circ = \frac{1}{2},\quad \cos 30^\circ = \frac{\sqrt{3}}{2}
  $$</div>

  <!-- Insert Special Triangle Diagram -->

  <hr>

  <h3>4. Sine Rule and Cosine Rule</h3>

  <p><strong>The Sine Rule</strong> is used in non-right-angled triangles:</p>
  <div>$$
  \frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C}
  $$</div>

  <p><strong>The Cosine Rule</strong> is used when you know two sides and the included angle or all three sides:</p>
  <div>$$
  c^2 = a^2 + b^2 - 2ab\cos C
  $$</div>

  <p><strong>Example (Sine Rule):</strong> In triangle ABC, \(a = 7\), \(A = 40^\circ\), \(B = 60^\circ\). Find \(b\).</p>
  <div>$$
  \frac{7}{\sin 40^\circ} = \frac{b}{\sin 60^\circ} \Rightarrow b = \frac{7 \cdot \sin 60^\circ}{\sin 40^\circ} \approx 10.2
  $$</div>

  <p><strong>Example (Cosine Rule):</strong> \(a = 5\), \(b = 6\), \(C = 60^\circ\)</p>
  <div>$$
  c^2 = 5^2 + 6^2 - 2(5)(6)\cos 60^\circ = 25 + 36 - 60(0.5) = 31 \Rightarrow c \approx 5.57
  $$</div>

  <!-- Insert Diagram of Non-Right Triangle -->

</div>


  <hr>

  <h3>5. Area of a Triangle (Using Trigonometry)</h3>
  <p>In any triangle (not necessarily right-angled), you can find the area using two sides and the angle between them:</p>
  <div>$$
  \text{Area} = \frac{1}{2}ab\sin C
  $$</div>

  <p><strong>Example:</strong> In a triangle, \(a = 8\), \(b = 10\), and the angle between them is \(60^\circ\):</p>
  <div>$$
  \text{Area} = \frac{1}{2} \cdot 8 \cdot 10 \cdot \sin 60^\circ = 40 \cdot \frac{\sqrt{3}}{2} = 20\sqrt{3} \approx 34.64\ \text{units}^2
  $$</div>

  <!-- Insert Triangle with Included Angle -->

  <hr>

  <h3>6. The Unit Circle</h3>
  <p>The unit circle is a circle with radius 1 centred at the origin. Any point on the circle corresponds to an angle \(\theta\) and has coordinates \((\cos \theta, \sin \theta)\).</p>
  <p>This allows us to define sine and cosine for any angle, not just in triangles.</p>

  <p><strong>Example:</strong> At \(\theta = 90^\circ = \frac{\pi}{2}\), the point on the unit circle is:</p>
  <div>$$
  (\cos \theta, \sin \theta) = (0, 1)
  $$</div>

  <!-- Insert Unit Circle with Coordinates -->

  <hr>

  <h3>7. Solving Trigonometric Equations</h3>
  <p>To solve equations like \(\sin x = a\), find the general solutions and restrict to the given interval (usually \(0^\circ\) to \(360^\circ\)).</p>

  <p><strong>Example:</strong> Solve \(\sin x = \frac{1}{2}\) for \(x \in [0^\circ, 360^\circ]\)</p>
  <ul>
    <li>\(\sin x = \frac{1}{2} \Rightarrow x = 30^\circ\) or \(150^\circ\)</li>
  </ul>

  <p>Always check the sign of the value and use the ASTC rule (All Students Take Calculus) to find all solutions in the interval.</p>

  <!-- Insert Sine Graph or ASTC Circle -->

  <hr>

  <h3>8. Inverse Trigonometric Functions</h3>
  <p>To find an angle when you know the ratio, use inverse trigonometric functions:</p>
  <ul>
    <li>\(\sin^{-1}(\text{value})\)</li>
    <li>\(\cos^{-1}(\text{value})\)</li>
    <li>\(\tan^{-1}(\text{value})\)</li>
  </ul>

  <p><strong>Example:</strong> A triangle has opposite side 5 cm and hypotenuse 13 cm. Find the angle \(\theta\).</p>
  <div>$$
  \sin \theta = \frac{5}{13} \Rightarrow \theta = \sin^{-1}\left(\frac{5}{13}\right) \approx 22.6^\circ
  $$</div>

  <!-- Insert Right Triangle with Labelled Sides -->

  <hr>

  <h3>9. Half-Angle Identities</h3>
  <p>These identities help find values of trigonometric functions for half an angle, useful in proofs and calculus.</p>
  <ul>
    <li>\(\sin\frac{\theta}{2} = \pm \sqrt{\frac{1 - \cos \theta}{2}}\)</li>
    <li>\(\cos\frac{\theta}{2} = \pm \sqrt{\frac{1 + \cos \theta}{2}}\)</li>
    <li>\(\tan\frac{\theta}{2} = \pm \sqrt{\frac{1 - \cos \theta}{1 + \cos \theta}}\)</li>
  </ul>
  <p>The sign depends on the quadrant of the angle \(\frac{\theta}{2}\).</p>

  <p><strong>Example:</strong> Find \(\sin 15^\circ\) using a half-angle identity.</p>
  <div>$$
  \sin 15^\circ = \sin\left(\frac{30^\circ}{2}\right) = \sqrt{\frac{1 - \cos 30^\circ}{2}} = \sqrt{\frac{1 - \frac{\sqrt{3}}{2}}{2}} \approx 0.2588
  $$</div>

  <!-- Insert Half-Angle Visual Aid -->

  <hr>

  <h3>10. Compound Angle Formulae</h3>
  <p>These are used to expand expressions like \(\sin(A \pm B)\) and \(\cos(A \pm B)\):</p>
  <ul>
    <li>\(\sin(A \pm B) = \sin A \cos B \pm \cos A \sin B\)</li>
    <li>\(\cos(A \pm B) = \cos A \cos B \mp \sin A \sin B\)</li>
    <li>\(\tan(A \pm B) = \frac{\tan A \pm \tan B}{1 \mp \tan A \tan B}\)</li>
  </ul>

  <p><strong>Example:</strong> Find \(\sin(75^\circ)\) using the compound formula.</p>
  <div>$$
  \sin(75^\circ) = \sin(45^\circ + 30^\circ) = \sin 45^\circ \cos 30^\circ + \cos 45^\circ \sin 30^\circ
  $$</div>
  <div>$$
  = \frac{1}{\sqrt{2}} \cdot \frac{\sqrt{3}}{2} + \frac{1}{\sqrt{2}} \cdot \frac{1}{2} = \frac{1}{\sqrt{2}} \cdot \left(\frac{\sqrt{3} + 1}{2}\right)
  $$</div>

  <!-- Insert Visual Showing A + B on Triangle or Circle -->

  <hr>

  <h3>11. Special Trigonometric Identities</h3>
  <p>These come from the Pythagorean identity and are useful in algebra and calculus.</p>
  <ul>
    <li>\(\sin^2 \theta + \cos^2 \theta = 1\)</li>
    <li>\(1 + \tan^2 \theta = \sec^2 \theta\)</li>
    <li>\(1 + \cot^2 \theta = \csc^2 \theta\)</li>
  </ul>

  <p><strong>Example:</strong> If \(\cos \theta = \frac{3}{5}\), find \(\sin \theta\).</p>
  <div>$$
  \sin^2 \theta = 1 - \cos^2 \theta = 1 - \left(\frac{9}{25}\right) = \frac{16}{25} \Rightarrow \sin \theta = \pm \frac{4}{5}
  $$</div>
  <p>The sign depends on the quadrant.</p>

  <!-- Insert Right Triangle or Circle Showing Identity -->

  <hr>

  <h3>12. Sums to Products</h3>
  <p>These identities rewrite sums as products, often used in integration or simplifying trig expressions.</p>
  <ul>
    <li>\(\sin A + \sin B = 2 \sin\left(\frac{A + B}{2}\right)\cos\left(\frac{A - B}{2}\right)\)</li>
    <li>\(\cos A + \cos B = 2 \cos\left(\frac{A + B}{2}\right)\cos\left(\frac{A - B}{2}\right)\)</li>
    <li>\(\cos A - \cos B = -2 \sin\left(\frac{A + B}{2}\right)\sin\left(\frac{A - B}{2}\right)\)</li>
  </ul>

  <p><strong>Example:</strong> Simplify \(\sin 70^\circ + \sin 10^\circ\)</p>
  <div>$$
  = 2 \sin\left(\frac{70 + 10}{2}\right)\cos\left(\frac{70 - 10}{2}\right) = 2 \sin 40^\circ \cos 30^\circ
  $$</div>

  <!-- Insert Diagram Linking A and B -->

  <hr>

  <h3>13. Products to Sums</h3>
  <p>These identities convert products of trig functions into sums, useful in simplifying integrals and verifying identities:</p>
  <ul>
    <li>\(\sin A \sin B = \frac{1}{2}[\cos(A - B) - \cos(A + B)]\)</li>
    <li>\(\cos A \cos B = \frac{1}{2}[\cos(A - B) + \cos(A + B)]\)</li>
    <li>\(\sin A \cos B = \frac{1}{2}[\sin(A + B) + \sin(A - B)]\)</li>
  </ul>

  <p><strong>Example:</strong> Simplify \(\cos 60^\circ \cos 30^\circ\):</p>
  <div>$$
  = \frac{1}{2}[\cos(60^\circ - 30^\circ) + \cos(60^\circ + 30^\circ)]
  = \frac{1}{2}[\cos 30^\circ + \cos 90^\circ] = \frac{1}{2}\left(\frac{\sqrt{3}}{2} + 0\right) = \frac{\sqrt{3}}{4}
  $$</div>

  <!-- Insert angle diagram showing A ± B -->

  <hr>

  <h3>14. Double Angle Formulae</h3>
  <p>These are identities for functions of \(2A\), used often in calculus and algebra:</p>
  <ul>
    <li>\(\sin 2A = 2 \sin A \cos A\)</li>
    <li>\(\cos 2A = \cos^2 A - \sin^2 A = 2\cos^2 A - 1 = 1 - 2\sin^2 A\)</li>
    <li>\(\tan 2A = \frac{2\tan A}{1 - \tan^2 A}\)</li>
  </ul>

  <p><strong>Example:</strong> Find \(\sin 2A\) if \(\sin A = \frac{3}{5}, \cos A = \frac{4}{5}\):</p>
  <div>$$
  \sin 2A = 2 \cdot \frac{3}{5} \cdot \frac{4}{5} = \frac{24}{25}
  $$</div>

  <!-- Insert diagram with right triangle for sine and cosine -->

  <hr>

  <h3>15. Length of Arc and Area of Sector</h3>
  <p>These formulas use angle \(\theta\) in radians with radius \(r\):</p>
  <ul>
    <li>Arc length: \(s = r\theta\)</li>
    <li>Sector area: \(A = \frac{1}{2}r^2\theta\)</li>
  </ul>

  <p><strong>Example:</strong> A circle has radius 6 cm and angle \(\theta = \frac{\pi}{3}\):</p>
  <ul>
    <li>Arc length: \(s = 6 \cdot \frac{\pi}{3} = 2\pi \text{ cm}\)</li>
    <li>Area: \(A = \frac{1}{2} \cdot 6^2 \cdot \frac{\pi}{3} = \frac{18\pi}{1} = 18\pi \approx 56.55\ \text{cm}^2\)</li>
  </ul>

  <!-- Insert labelled circle sector diagram -->

  <hr>

  <h3>16. Segment of a Circle</h3>
  <p>A segment is the area between a chord and the arc above it.</p>
  <p>To find the segment area:</p>
  <div>$$
  \text{Segment area} = \text{Sector area} - \text{Triangle area}
  $$</div>
  <p>In radians, a shortcut is:</p>
  <div>$$
  \text{Segment area} = \frac{1}{2}r^2(\theta - \sin\theta)
  $$</div>

  <p><strong>Example:</strong> Find the segment area if \(r = 5\), \(\theta = \frac{\pi}{3}\):</p>
  <div>$$
  \text{Segment} = \frac{1}{2}(25)\left(\frac{\pi}{3} - \sin\left(\frac{\pi}{3}\right)\right)
  = \frac{25}{2} \left(\frac{\pi}{3} - \frac{\sqrt{3}}{2}\right)
  $$</div>

  <!-- Insert segment diagram with chord and arc -->

</div>
