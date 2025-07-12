---
layout: default
title: Sets
---

<div>
  <h2>Sets</h2>

  <hr>

  <h3>1. Definitions &amp; Notation</h3>
  <p><strong>Set:</strong> a collection of distinct objects, called <em>elements</em>.</p>
  <p>Notation: If <code>A</code> is a set and <code>x</code> an element, we write <code>x ∈ A</code>; if not, <code>x ∉ A</code>.</p>
  <p><strong>Roster form:</strong> list elements in braces, e.g. <code>A = {1,2,3,5}</code>.</p>
  <p><strong>Set-builder form:</strong> describe a property, e.g. <code>B = {x | x is an even positive integer ≤ 10}</code>.</p>

  <hr>

  <h3>2. Special Sets</h3>
  <ul>
    <li><strong>Empty set:</strong> no elements. <code>∅ = {}</code>.  
      <strong>Example:</strong> {x | x<0 and x>0} = ∅.</li>
    <li><strong>Universal set:</strong> the “domain” of discourse, denoted <code>U</code>.  
      <strong>Example:</strong> If U = {1–10}, then every subset is drawn from these.</li>
    <li><strong>Subset &amp; Proper subset:</strong>  
      <ul>
        <li><code>A ⊆ B</code> if every element of A is in B.  
          <strong>Example:</strong> {1,2} ⊆ {1,2,3}.</li>
        <li><code>A ⊂ B</code> if A ⊆ B but A ≠ B.  
          <strong>Example:</strong> {1,2} ⊂ {1,2,3}.</li>
      </ul>
    </li>
    <li><strong>Power set:</strong> the set of all subsets of A, denoted <code>℘(A)</code> or <code>2ᴬ</code>.  
      <strong>Example:</strong> If A = {a,b}, then ℘(A) = {∅,{a},{b},{a,b}}.</li>
  </ul>

  <hr>

  <h3>3. Set Operations</h3>
  <ul>
    <li>
      <strong>Union:</strong> <code>A ∪ B = {x | x ∈ A or x ∈ B}</code>.  
      <figure>
        <img src="{{ '/assets/images/sets_union.svg' | relative_url }}" alt="Union of sets A and B">
        <figcaption>A ∪ B</figcaption>
      </figure>
      <p><strong>Example:</strong> {1,2,3} ∪ {3,4,5} = {1,2,3,4,5}.</p>
    </li>
    <li>
      <strong>Intersection:</strong> <code>A ∩ B = {x | x ∈ A and x ∈ B}</code>.  
      <figure>
        <img src="{{ '/assets/images/sets_intersection.svg' | relative_url }}" alt="Intersection of sets A and B">
        <figcaption>A ∩ B</figcaption>
      </figure>
      <p><strong>Example:</strong> {1,2,3} ∩ {2,3,4} = {2,3}.</p>
    </li>
    <li>
      <strong>Difference:</strong> <code>A \ B = {x | x ∈ A and x ∉ B}</code>.  
      <figure>
        <img src="{{ '/assets/images/sets_difference.svg' | relative_url }}" alt="Difference of sets A and B">
        <figcaption>A \ B</figcaption>
      </figure>
      <p><strong>Example:</strong> {1,2,3,4} \ {2,4} = {1,3}.</p>
    </li>
    <li>
      <strong>Complement:</strong> <code>Aᶜ = U \ A</code>, relative to the universal set U.  
      <figure>
        <img src="{{ '/assets/images/sets_complement.svg' | relative_url }}" alt="Complement of set A">
        <figcaption>Aᶜ</figcaption>
      </figure>
      <p><strong>Example:</strong> If U = {1–5} and A = {2,4}, then Aᶜ = {1,3,5}.</p>
    </li>
  </ul>

  <hr>

  <h3>4. Cartesian Product</h3>
  <p><strong>Definition:</strong> <code>A × B = {(a,b) | a ∈ A, b ∈ B}</code>.</p>
  <figure>
    <img src="{{ '/assets/images/sets_cartesian.svg' | relative_url }}" alt="Cartesian product A times B">
    <figcaption>A × B</figcaption>
  </figure>
  <p><strong>Example:</strong> {1,2} × {x,y} = {(1,x),(1,y),(2,x),(2,y)}.</p>

  <hr>

  <h3>5. Venn Diagrams</h3>
  <p>Graphical representation of sets and their relationships. Circles represent sets within a rectangle (the universal set).</p>
  <figure>
    <img src="{{ '/assets/images/sets_venn.svg' | relative_url }}" alt="Venn diagram of two sets">
    <figcaption>Typical two-set Venn diagram showing ∪, ∩, and complements.</figcaption>
  </figure>
  <p><strong>Example:</strong> Shade the region for <code>(A ∪ B) \ (A ∩ B)</code> to show the symmetric difference.</p>
</div>
