---
layout: default
title: Circles
---

<div>
  <h2>Circles</h2>

  <hr>

  <h3>1. Types of Circles</h3>
  <ul>
    <li><strong>Unit Circle:</strong> radius \(r=1\), center usually at \((0,0)\).  
      <figure>
        <img src="{{ '/assets/images/circle01.svg' | relative_url }}" alt="Unit circle">
        <figcaption>Unit circle centered at the origin.</figcaption>
      </figure>
      <p><strong>Example:</strong> Equation \(x^2 + y^2 = 1\).</p>
    </li>
    <li><strong>Concentric Circles:</strong> share the same center, different radii.  
      <figure>
        <img src="{{ '/assets/images/circle02.svg' | relative_url }}" alt="Concentric circles">
        <figcaption>Circles with center O and radii 3 and 5.</figcaption>
      </figure>
      <p><strong>Example:</strong> \(x^2 + y^2 = 9\) and \(x^2 + y^2 = 25\).</p>
    </li>
    <li><strong>Eccentric (Non-concentric) Circles:</strong> different centers.  
      <figure>
        <img src="{{ '/assets/images/circle03.svg' | relative_url }}" alt="Eccentric circles">
        <figcaption>Circles with centers O and P.</figcaption>
      </figure>
      <p><strong>Example:</strong> \((x-2)^2 + (y-1)^2 = 4\) and \((x+1)^2 + (y+2)^2 = 9\).</p>
    </li>
    <li><strong>Coincident Circles:</strong> same center and same radius (identical).  
      <p><strong>Example:</strong> \(x^2 + y^2 = 4\) and \(x^2 + y^2 = 4\).</p>
    </li>
  </ul>

  <hr>

  <h3>2. Circles Touching the Axes</h3>
  <p>A circle that touches both the \(x\)- and \(y\)-axes has center \((r,r)\) and radius \(r\):</p>
  <div>
    \[
      (x - r)^2 + (y - r)^2 = r^2
    \]
  </div>
  <figure>
    <img src="{{ '/assets/images/circle04.svg' | relative_url }}" alt="Circle touching axes">
    <figcaption>Circle of radius r touching both axes.</figcaption>
  </figure>
  <p><strong>Example:</strong> For \(r=3\): \((x-3)^2 + (y-3)^2 = 9\).</p>

  <hr>

  <h3>3. Points Inside, On &amp; Outside</h3>
  <p>Given circle \((x-h)^2+(y-k)^2=r^2\) and a point \(P(x_0,y_0)\), let \(d=\sqrt{(x_0-h)^2+(y_0-k)^2}\):</p>
  <ul>
    <li>\(d < r\): \(P\) is <em>inside</em>.</li>
    <li>\(d = r\): \(P\) is <em>on</em> the circle.</li>
    <li>\(d > r\): \(P\) is <em>outside</em>.</li>
  </ul>
  <figure>
    <img src="{{ '/assets/images/circle05.svg' | relative_url }}" alt="Points inside on outside circle">
    <figcaption>Points A, B, C inside, on, and outside respectively.</figcaption>
  </figure>
  <p><strong>Example:</strong> Circle \(x^2+y^2=4\); \(P(1,1)\) has \(d≈1.41<2\) ⇒ inside.</p>

  <hr>

  <h3>4. Touching (Tangent) Circles</h3>
  <p>Two circles with centers \(O_1,O_2\) and radii \(r_1,r_2\):</p>
  <ul>
    <li><strong>Externally tangent</strong> if \(O_1O_2 = r_1 + r_2\).</li>
    <li><strong>Internally tangent</strong> if \(O_1O_2 = |r_1 - r_2|\).</li>
  </ul>
  <figure>
    <img src="{{ '/assets/images/circle06.svg' | relative_url }}" alt="Touching circles">
    <figcaption>Externally and internally tangent circles.</figcaption>
  </figure>
  <p><strong>Example:</strong> Circles radius 2 and 3, centers 5 apart ⇒ external tangent.</p>

  <hr>

  <h3>5. Circle Theorems</h3>
  <ul>
    <li>
      <strong>Inscribed Angle Theorem:</strong> The angle at the centre is twice the angle at the circumference on the same arc.  
      <figure>
        <img src="{{ '/assets/images/circle07.svg' | relative_url }}" alt="Inscribed angle theorem">
        <figcaption>\(\angle AOB = 2\angle ACB\).</figcaption>
      </figure>
      <p><strong>Example:</strong> If \(\angle ACB=30°\), then \(\angle AOB=60°\).</p>
    </li>
    <li>
      <strong>Angle in a Semicircle:</strong> An angle in a semicircle is a right angle.  
      <figure>
        <img src="{{ '/assets/images/circle08.svg' | relative_url }}" alt="Angle in a semicircle">
        <figcaption>\(\angle ACB = 90°\) if AB is a diameter.</figcaption>
      </figure>
      <p><strong>Example:</strong> For diameter AB, any C on the circle yields \(\angle ACB=90°\).</p>
    </li>
    <li>
      <strong>Equal Chords &amp; Equal Arcs:</strong> Equal chords subtend equal angles at the centre.  
      <figure>
        <img src="{{ '/assets/images/circle09.svg' | relative_url }}" alt="Equal chords theorem">
        <figcaption>Chords AB and CD equal ⇒ \(\angle AOB = \angle COD\).</figcaption>
      </figure>
      <p><strong>Example:</strong> If AB=CD, then central angles are equal.</p>
    </li>
    <li>
      <strong>Cyclic Quadrilateral:</strong> Opposite angles of a cyclic quadrilateral sum to 180°.  
      <figure>
        <img src="{{ '/assets/images/circle10.svg' | relative_url }}" alt="Cyclic quadrilateral theorem">
        <figcaption>In ABCD on a circle, \(\angle A + \angle C = 180°\).</figcaption>
      </figure>
      <p><strong>Example:</strong> If \(\angle A=110°\), then \(\angle C=70°\).</p>
    </li>
  </ul>

  <hr>

  <h3>6. Tangents to a Circle</h3>
  <ul>
    <li><strong>Radius ⟂ Tangent:</strong> The radius at the point of contact is perpendicular to the tangent line.  
      <figure>
        <img src="{{ '/assets/images/circle11.svg' | relative_url }}" alt="Radius perpendicular to tangent">
        <figcaption>At P, \(OP \perp\) tangent PT.</figcaption>
      </figure>
      <p><strong>Example:</strong> \(OP=5\), PT ⟂ OP ⇒ PT is a tangent.</p>
    </li>
    <li><strong>Equal Tangents:</strong> Tangents from an external point are equal in length.  
      <figure>
        <img src="{{ '/assets/images/circle12.svg' | relative_url }}" alt="Equal tangents theorem">
        <figcaption>From P, PA = PB.</figcaption>
      </figure>
      <p><strong>Example:</strong> If PA=8, then PB=8.</p>
    </li>
  </ul>

  <hr>

  <h3>7. Common Tangent &amp; Common Chord</h3>
  <p><strong>Common Tangent:</strong> A line tangent to two circles. Can be direct (both on same side) or transverse (between them).</p>
  <figure>
    <img src="{{ '/assets/images/circle13.svg' | relative_url }}" alt="Common tangents">
    <figcaption>Direct and transverse common tangents to two circles.</figcaption>
  </figure>
  <p><strong>Example:</strong> Two circles radius 2 and 3, centers 8 apart have four common tangents.</p>

  <p><strong>Common Chord:</strong> If two circles intersect, the line through their intersection points is the common chord.</p>
  <figure>
    <img src="{{ '/assets/images/circle14.svg' | relative_url }}" alt="Common chord">
    <figcaption>Circles intersecting at A and B; AB is the common chord.</figcaption>
  </figure>
  <p><strong>Example:</strong> Intersection of \((x-2)^2+y^2=5\) and \(x^2+(y-1)^2=5\) gives chord AB.</p>
</div>
