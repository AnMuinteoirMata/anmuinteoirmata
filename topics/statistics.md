---
layout: default
title: Statistics
---

<div>
  <h2>Statistics</h2>

  <p>Statistics involves collecting, analysing, interpreting, and presenting data. This section covers types of data, measures of central tendency, measures of spread, and interpreting statistical diagrams.</p>

  <hr>

  <h3>1. Types of Data</h3>
  <ul>
    <li><strong>Qualitative (categorical):</strong> e.g. eye colour, brand names</li>
    <li><strong>Quantitative (numerical):</strong> e.g. height, income</li>
    <ul>
      <li><em>Discrete:</em> countable values (e.g. number of students)</li>
      <li><em>Continuous:</em> measured values (e.g. weight, time)</li>
    </ul>
  </ul>

  <p><strong>Example:</strong> Shoe size is quantitative and discrete. Temperature is quantitative and continuous.</p>

  <hr>

  <h3>2. Mean, Median and Mode</h3>

  <ul>
    <li><strong>Mean:</strong> Average value: \( \bar{x} = \frac{\sum x}{n} \)</li>
    <li><strong>Median:</strong> Middle value when data is ordered</li>
    <li><strong>Mode:</strong> Most frequent value</li>
  </ul>

  <p><strong>Example:</strong> Data: 4, 5, 6, 7, 7, 8, 9</p>
  <ul>
    <li>Mean = \( \frac{4 + 5 + 6 + 7 + 7 + 8 + 9}{7} = \frac{46}{7} \approx 6.57 \)</li>
    <li>Median = 7</li>
    <li>Mode = 7</li>
  </ul>

  <hr>

  <h3>3. Measures of Spread</h3>

  <ul>
    <li><strong>Range:</strong> Largest - smallest value</li>
    <li><strong>Interquartile Range (IQR):</strong> \( Q_3 - Q_1 \)</li>
    <li><strong>Variance:</strong> \( \frac{1}{n} \sum (x_i - \bar{x})^2 \)</li>
    <li><strong>Standard Deviation:</strong> \( \sqrt{\text{variance}} \)</li>
  </ul>

  <p><strong>Example:</strong> Data: 2, 4, 6, 8</p>
  <ul>
    <li>Mean = 5</li>
    <li>Variance = \( \frac{1}{4}[(2-5)^2 + (4-5)^2 + (6-5)^2 + (8-5)^2] = \frac{1}{4}(9 + 1 + 1 + 9) = 5 \)</li>
    <li>Standard Deviation = \( \sqrt{5} \approx 2.24 \)</li>
  </ul>

  <hr>

  <h3>4. Grouped Data</h3>

  <p>To estimate the mean of grouped data:</p>
  <div>$$
  \bar{x} = \frac{\sum fx}{\sum f}
  $$</div>
  <p>\(f\): frequency, \(x\): midpoint of class</p>

  <p><strong>Example:</strong></p>
  <table>
    <thead>
      <tr><th>Class</th><th>Midpoint \(x\)</th><th>Frequency \(f\)</th><th>\(fx\)</th></tr>
    </thead>
    <tbody>
      <tr><td>0–10</td><td>5</td><td>3</td><td>15</td></tr>
      <tr><td>10–20</td><td>15</td><td>5</td><td>75</td></tr>
      <tr><td>20–30</td><td>25</td><td>2</td><td>50</td></tr>
    </tbody>
  </table>
  <p>Total frequency = 10, Total fx = 140 → Mean = \( \frac{140}{10} = 14 \)</p>

  <hr>

  <h3>5. Cumulative Frequency</h3>
  <p>Used to estimate the median, quartiles, and percentiles from grouped data.</p>

  <p><strong>Steps:</strong></p>
  <ol>
    <li>Find cumulative frequency</li>
    <li>Draw cumulative frequency graph</li>
    <li>Estimate median at \( \frac{n}{2} \), quartiles at \( \frac{n}{4} \), \( \frac{3n}{4} \)</li>
  </ol>

  <hr>

  <h3>6. Box Plots</h3>
  <p>Box plots show median, quartiles, and outliers.</p>
  <ul>
    <li>Minimum</li>
    <li>Lower quartile \(Q_1\)</li>
    <li>Median</li>
    <li>Upper quartile \(Q_3\)</li>
    <li>Maximum</li>
  </ul>

  <p><strong>Example:</strong> Data: 3, 5, 7, 9, 11</p>
  <ul>
    <li>Min = 3, \( Q_1 = 5 \), Median = 7, \( Q_3 = 9 \), Max = 11</li>
  </ul>

  <hr>

  <h3>7. Outliers</h3>
  <p>An outlier is a value that is much smaller or larger than the rest.</p>
  <p>Outliers are often defined as values outside the range:</p>
  <div>$$
  [Q_1 - 1.5 \cdot IQR,\ Q_3 + 1.5 \cdot IQR]
  $$</div>

  <p><strong>Example:</strong> If \( Q_1 = 10 \), \( Q_3 = 30 \), then:</p>
  <div>$$
  IQR = 20 \Rightarrow [10 - 30,\ 30 + 30] = [-20,\ 60]
  $$</div>
  <p>Any value outside this range is an outlier.</p>

  <hr>

  <h3>8. Comparing Distributions</h3>
  <p>Compare two sets of data using:</p>
  <ul>
    <li>Mean or Median (central tendency)</li>
    <li>Standard deviation or IQR (spread)</li>
    <li>Box plots (shape and outliers)</li>
  </ul>

  <p><strong>Example:</strong> Set A has mean 50 and SD 5, Set B has mean 50 and SD 12. They have the same average, but Set B has more variability.</p>

  <hr>

  <h3>9. Interpret Graphs and Data</h3>
  <p>Students should be able to interpret:</p>
  <ul>
    <li>Histograms</li>
    <li>Box plots</li>
    <li>Cumulative frequency graphs</li>
    <li>Bar charts and pie charts</li>
  </ul>

  <p><strong>Example:</strong> A box plot with a large IQR suggests data is spread out. A very short box suggests consistency.</p>

</div>
