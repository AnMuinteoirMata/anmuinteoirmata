---
layout: default
title: Complex Numbers
---

<div>
  <h2>Complex Numbers</h2>

  <p>Complex numbers are numbers that include both real and imaginary parts. They are written in the form:</p>
  <div>$$
  z = a + bi
  $$</div>
  <p>Where:</p>
  <ul>
    <li>\(a\) is the real part</li>
    <li>\(b\) is the imaginary part</li>
    <li>\(i\) is the imaginary unit, where \(i^2 = -1\)</li>
  </ul>

  <hr>

  <h3>1. Adding and Subtracting Complex Numbers</h3>
  <p>Add or subtract the real and imaginary parts separately.</p>

  <p><strong>Example:</strong> \( (3 + 2i) + (1 - 5i) = (3 + 1) + (2i - 5i) = 4 - 3i \)</p>

  <hr>

  <h3>2. Multiplying Complex Numbers</h3>
  <p>Use the distributive (FOIL) method and remember \(i^2 = -1\).</p>

  <p><strong>Example:</strong> \( (2 + i)(3 - 4i) = 6 - 8i + 3i - 4i^2 = 6 - 5i + 4 = 10 - 5i \)</p>

  <hr>

  <h3>3. Complex Conjugate</h3>
  <p>The conjugate of \( z = a + bi \) is \( \bar{z} = a - bi \).</p>
  <p>Multiplying a complex number by its conjugate gives a real number:</p>
  <div>$$
  z \cdot \bar{z} = a^2 + b^2
  $$</div>

  <p><strong>Example:</strong> \( z = 3 + 4i \Rightarrow \bar{z} = 3 - 4i \Rightarrow z\bar{z} = 9 + 16 = 25 \)</p>

  <hr>

  <h3>4. Dividing Complex Numbers</h3>
  <p>To divide complex numbers, multiply top and bottom by the conjugate of the denominator:</p>
  <div>$$
  \frac{a + bi}{c + di} \cdot \frac{c - di}{c - di}
  $$</div>

  <p><strong>Example:</strong> \( \frac{1 + 2i}{3 - i} = \frac{(1 + 2i)(3 + i)}{(3 - i)(3 + i)} = \frac{3 + i + 6i + 2i^2}{9 + 1} = \frac{3 + 7i - 2}{10} = \frac{1 + 7i}{10} \)</p>

  <hr>

  <h3>5. Modulus and Argument</h3>
  <ul>
    <li><strong>Modulus:</strong> \( |z| = \sqrt{a^2 + b^2} \)</li>
    <li><strong>Argument:</strong> angle \( \theta \) the complex number makes with the real axis</li>
  </ul>

  <p><strong>Example:</strong> \( z = 1 + \sqrt{3}i \)</p>
  <ul>
    <li>Modulus: \( |z| = \sqrt{1^2 + (\sqrt{3})^2} = \sqrt{1 + 3} = 2 \)</li>
    <li>Argument: \( \tan^{-1}(\sqrt{3}) = \frac{\pi}{3} \) radians</li>
  </ul>

  <hr>

  <h3>6. Polar Form of Complex Numbers</h3>
  <p>Instead of writing \( z = a + bi \), we can write:</p>
  <div>$$
  z = r(\cos \theta + i \sin \theta)
  $$</div>
  <p>This is useful for multiplying, dividing, and finding powers/roots.</p>

  <p><strong>Example:</strong> \( z = 1 + i \Rightarrow r = \sqrt{2}, \theta = \frac{\pi}{4} \Rightarrow z = \sqrt{2}(\cos \frac{\pi}{4} + i \sin \frac{\pi}{4}) \)</p>

  <hr>

  <h3>7. De Moivre’s Theorem</h3>
  <p>For \( z = r(\cos \theta + i \sin \theta) \), then:</p>
  <div>$$
  z^n = r^n [\cos(n\theta) + i \sin(n\theta)]
  $$</div>

  <p><strong>Example:</strong> Find \( (1 + i)^4 \)</p>
  <ul>
    <li>Write in polar form: \( r = \sqrt{2}, \theta = \frac{\pi}{4} \)</li>
    <li>Use De Moivre: \( z^4 = (\sqrt{2})^4 \cdot [\cos(\pi) + i \sin(\pi)] = 4(-1) = -4 \)</li>
  </ul>

  <hr>

  <h3>8. Roots of Complex Numbers</h3>
  <p>The \(n^\text{th}\) roots of a complex number form a regular polygon on the Argand diagram.</p>
  <p>If \( z = r(\cos \theta + i \sin \theta) \), then:</p>
  <div>$$
  \text{Roots: } \sqrt[n]{z} = r^{1/n} \left[\cos\left(\frac{\theta + 2k\pi}{n}\right) + i\sin\left(\frac{\theta + 2k\pi}{n}\right)\right],\quad k = 0, 1, ..., n-1
  $$</div>

  <p><strong>Example:</strong> Find cube roots of 8:</p>
  <ul>
    <li>Write 8 in polar form: \( z = 8(\cos 0 + i \sin 0) \)</li>
    <li>Roots are \( 2[\cos(0 + \frac{2k\pi}{3}) + i \sin(0 + \frac{2k\pi}{3})] \), for \( k = 0, 1, 2 \)</li>
  </ul>

  <hr>

  <h3>9. Argand Diagram</h3>
  <p>Complex numbers are graphed on the Argand diagram:</p>
  <ul>
    <li>Horizontal axis = real part</li>
    <li>Vertical axis = imaginary part</li>
  </ul>

  <img src="/anmuinteoirmata/images/argand.png" alt="Argand Diagram">


</div>
