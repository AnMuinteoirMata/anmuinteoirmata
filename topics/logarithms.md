---
layout: default
title: Logarithms
---

<div>
  <h2>Logarithms</h2>

  <hr>

  <h3>1. What is a Logarithm?</h3>
  <p>A logarithm is the inverse of an exponent. If:</p>
  <div>$$
  a^x = b
  $$</div>
  <p>Then:</p>
  <div>$$
  \log_a b = x
  $$</div>
  <p>This means: "To what power must I raise \(a\) to get \(b\)?"</p>

  <p><strong>Examples:</strong></p>
  <ul>
    <li>\(\log_2 8 = 3\) because \(2^3 = 8\)</li>
    <li>\(\log_{10} 1000 = 3\) because \(10^3 = 1000\)</li>
    <li>\(\log_5 25 = 2\) because \(5^2 = 25\)</li>
  </ul>

  <hr>

  <h3>2. Laws of Logarithms</h3>
  <ul>
    <li>\(\log_a (xy) = \log_a x + \log_a y\)</li>
    <li>\(\log_a \left(\frac{x}{y}\right) = \log_a x - \log_a y\)</li>
    <li>\(\log_a (x^n) = n \log_a x\)</li>
    <li>\(\log_a a = 1\), and \(\log_a 1 = 0\)</li>
    <li>\(\log_a b = \frac{\log_c b}{\log_c a}\) (Change of base formula)</li>
  </ul>

  <p><strong>Examples:</strong></p>
  <ul>
    <li>\(\log_2 (8 \times 4) = \log_2 8 + \log_2 4 = 3 + 2 = 5\)</li>
    <li>\(\log_{10} \left(\frac{1000}{10}\right) = \log_{10} 1000 - \log_{10} 10 = 3 - 1 = 2\)</li>
    <li>\(\log_3 (27^2) = 2 \log_3 27 = 2 \times 3 = 6\)</li>
  </ul>

  <hr>

  <h3>3. Solving Logarithmic Equations</h3>

  <p><strong>Example 1:</strong> Solve \(\log_2 x = 5\)</p>
  <div>Rewrite in exponential form: \(x = 2^5 = 32\)</div>

  <p><strong>Example 2:</strong> Solve \(\log_3 (x + 1) = 2\)</p>
  <div>Rewrite: \(x + 1 = 3^2 = 9 \Rightarrow x = 8\)</div>

  <p><strong>Example 3:</strong> Solve \(\log_5 x + \log_5 (x - 4) = 1\)</p>
  <div>Use law: \(\log_5 [x(x - 4)] = 1\)</div>
  <div>Then: \(x(x - 4) = 5^1 = 5\)</div>
  <div>So: \(x^2 - 4x - 5 = 0 \Rightarrow (x - 5)(x + 1) = 0\)</div>
  <div>Possible solutions: \(x = 5\), \(x = -1\) → Reject \(x = -1\) (can't log a negative)</div>
  <div><strong>Final Answer:</strong> \(x = 5\)</div>

  <hr>

  <h3>4. Solving Exponential Equations Using Logs</h3>

  <p><strong>Example:</strong> Solve \(3^x = 20\)</p>
  <p>Take logs of both sides (any base, usually base 10 or base \(e\)):</p>
  <div>$$
  \log(3^x) = \log(20) \Rightarrow x \log 3 = \log 20
  $$</div>
  <div>$$
  x = \frac{\log 20}{\log 3} \approx \frac{1.3010}{0.4771} \approx 2.73
  $$</div>

  <hr>

  <h3>5. Applications of Exponential Functions</h3>

  <ul>
    <li><strong>Population Growth:</strong> \(P = P_0 e^{kt}\)</li>
    <li><strong>Compound Interest:</strong> \(A = P(1 + r)^t\)</li>
    <li><strong>Radioactive Decay:</strong> \(N = N_0 e^{-kt}\)</li>
  </ul>

  <p><strong>Example (Compound Interest):</strong></p>
  <p>\(P = 1000\), \(r = 5\% = 0.05\), \(t = 3\)</p>
  <div>$$
  A = 1000(1.05)^3 = 1000 \times 1.157625 = 1157.63
  $$</div>

  <hr>

  <h3>6. Applications of Logarithmic Functions</h3>

  <ul>
    <li><strong>pH in Chemistry:</strong> \(pH = -\log_{10}[H^+]\)</li>
    <li><strong>Sound Intensity (Decibels):</strong> \(dB = 10 \log_{10} \left(\frac{I}{I_0}\right)\)</li>
    <li><strong>Richter Scale (Earthquake):</strong> \(\text{Magnitude} = \log_{10} \left(\frac{A}{A_0}\right)\)</li>
  </ul>

  <p><strong>Example (pH):</strong> If \([H^+] = 1 \times 10^{-4}\), then:</p>
  <div>$$
  pH = -\log_{10}(1 \times 10^{-4}) = -(-4) = 4
  $$</div>

  <p><strong>Example (Decibels):</strong> \(I = 1000I_0\), then:</p>
  <div>$$
  dB = 10 \log_{10}(1000) = 10 \times 3 = 30\ \text{dB}
  $$</div>

</div>
