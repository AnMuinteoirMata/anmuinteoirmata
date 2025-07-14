---
layout: default
title: Lines & Analytical Geometry
---

<div>
  <h2>Lines &amp; Analytical Geometry</h2>

  <hr>

  <h3>1. Distance Between Two Points</h3>
  <p>For points \(P(x_1,y_1)\) and \(Q(x_2,y_2)\):</p>
  <div>$$
    d(P,Q) = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}
  $$</div>
  <figure>
    <img src="/anmuinteoirmata/images/geometry1.png" alt="geometry1">
    <figcaption>Distance \(PQ\).</figcaption>
  </figure>
  <p><strong>Example:</strong> \(P(1,2)\), \(Q(4,6)\) ⇒  
     \(d = \sqrt{3^2 + 4^2} = 5\).</p>

  <hr>

  <h3>2. Midpoint of a Segment</h3>
  <p>The midpoint \(M\) of segment \(PQ\) is:</p>
  <div>$$
    M\!\bigl(\tfrac{x_1 + x_2}{2},\,\tfrac{y_1 + y_2}{2}\bigr)
  $$</div>
  <figure>
    <img src="{{ '/assets/images/line02.svg' | relative_url }}" alt="Midpoint of a segment">
    <figcaption>Midpoint \(M\).</figcaption>
  </figure>
  <p><strong>Example:</strong> \(P(1,2)\), \(Q(5,4)\) ⇒  
     \(M(3,3)\).</p>

  <hr>

  <h3>3. Slope of a Line</h3>
  <p>If \(P\) and \(Q\) lie on a non-vertical line, the slope \(m\) is:</p>
  <div>$$
    m = \frac{y_2 - y_1}{x_2 - x_1}
  $$</div>
  <figure>
    <img src="{{ '/assets/images/line03.svg' | relative_url }}" alt="Slope of a line">
    <figcaption>Slope \(m\).</figcaption>
  </figure>
  <p><strong>Example:</strong> \(P(0,1)\), \(Q(3,5)\) ⇒  
     \(m = \tfrac{5-1}{3-0} = \tfrac{4}{3}\).</p>

  <hr>

  <h3>4. Division of a Segment (Ratio)</h3>
  <p>A point dividing \(PQ\) in the ratio \(k:1\) (from \(P\) toward \(Q\)) has coordinates:</p>
  <div>$$
    \Bigl(\tfrac{k\,x_2 + x_1}{k+1},\,\tfrac{k\,y_2 + y_1}{k+1}\Bigr)
  $$</div>
  <figure>
    <img src="{{ '/assets/images/line04.svg' | relative_url }}" alt="Division of a segment">
    <figcaption>Internal division in ratio \(k:1\).</figcaption>
  </figure>
  <p><strong>Example:</strong> \(P(2,0)\), \(Q(8,6)\), ratio \(2:1\) ⇒  
     \(\bigl(\tfrac{2·8+2}{3},\tfrac{2·6+0}{3}\bigr)=(6,4)\).</p>

  <hr>

  <h3>5. Equation of a Line</h3>
  <p>Common forms:</p>
  <ul>
    <li><strong>Point–slope:</strong> \(y - y_1 = m(x - x_1)\)</li>
    <li><strong>Slope–intercept:</strong> \(y = m x + c\)</li>
    <li><strong>General:</strong> \(A x + B y + C = 0\)</li>
  </ul>
  <figure>
    <img src="{{ '/assets/images/line05.svg' | relative_url }}" alt="Equation of a line">
    <figcaption>Different line equations.</figcaption>
  </figure>
  <p><strong>Example:</strong> Slope \(2\) through \((1,3)\):  
     \(y - 3 = 2(x - 1)\) ⇒ \(y = 2x + 1\).</p>

  <hr>

  <h3>6. Distance from a Point to a Line</h3>
  <p>For line \(A x + B y + C = 0\) and point \((x_0,y_0)\):</p>
  <div>$$
    d = \frac{\lvert A x_0 + B y_0 + C\rvert}{\sqrt{A^2 + B^2}}
  $$</div>
  <figure>
    <img src="{{ '/assets/images/line06.svg' | relative_url }}" alt="Distance from a point to a line">
    <figcaption>Perpendicular distance to the line.</figcaption>
  </figure>
  <p><strong>Example:</strong> Line \(3x - 4y + 5=0\), point \((2,1)\):  
     \(d = \tfrac{|6 - 4 + 5|}{5} = \tfrac{7}{5} = 1.4\).</p>

  <hr>

  <h3>7. Angle Between Two Lines</h3>
  <p>If lines have slopes \(m_1\) and \(m_2\), the acute angle \(\theta\) between them satisfies:</p>
  <div>$$
    \tan\theta = \Bigl|\tfrac{m_2 - m_1}{1 + m_1 m_2}\Bigr|
  $$</div>
  <figure>
    <img src="{{ '/assets/images/line07.svg' | relative_url }}" alt="Angle between two lines">
    <figcaption>Angle \(\theta\) between the lines.</figcaption>
  </figure>
  <p><strong>Example:</strong> \(m_1=1\), \(m_2=-\tfrac13\) ⇒  
     \(\tan\theta = 2\), so \(\theta \approx 63.4°\).</p>

  <hr>

  <h3>8. Area of a Triangle (Coordinate Formula)</h3>
  <p>For vertices \(P(x_1,y_1)\), \(Q(x_2,y_2)\), \(R(x_3,y_3)\):</p>
  <div>$$
    \text{Area} = \tfrac12\bigl|x_1(y_2-y_3) + x_2(y_3-y_1) + x_3(y_1-y_2)\bigr|
  $$</div>
  <figure>
    <img src="{{ '/assets/images/line08.svg' | relative_url }}" alt="Area of triangle">
    <figcaption>Triangle \(PQR\).</figcaption>
  </figure>
  <p><strong>Example:</strong> \((0,0),(4,0),(0,3)\) ⇒  
     \(\tfrac12|0 + 12 + 0| = 6\).</p>

  <hr>

  <h3>9. Collinear Points</h3>
  <p>Points \(P, Q, R\) are collinear if the triangle area formula gives zero (or if slopes \(PQ\) and \(PR\) are equal).</p>
  <figure>
    <img src="{{ '/assets/images/line09.svg' | relative_url }}" alt="Collinear points">
    <figcaption>Three collinear points.</figcaption>
  </figure>
  <p><strong>Example:</strong> \((1,2),(3,6),(5,10)\) all have slope 2 ⇒ collinear.</p>

  <hr>

  <h3>10. Concurrency in a Triangle</h3>
  <p>Certain lines in a triangle meet at a single point:</p>
  <ul>
    <li><strong>Centroid:</strong> intersection of medians at  
      \(\bigl(\tfrac{x_1+x_2+x_3}{3},\,\tfrac{y_1+y_2+y_3}{3}\bigr)\).</li>
    <li><strong>Orthocenter:</strong> intersection of altitudes.</li>
    <li><strong>Incenter:</strong> intersection of angle bisectors.</li>
  </ul>
  <figure>
    <img src="{{ '/assets/images/line10.svg' | relative_url }}" alt="Concurrency in a triangle">
    <figcaption>Medians concurrent at the centroid G.</figcaption>
  </figure>
  <p><strong>Example:</strong> For \((0,0),(6,0),(0,6)\), centroid = \((2,2)\).</p>
</div>
