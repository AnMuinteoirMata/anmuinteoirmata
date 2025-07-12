---
layout: default
title: Inferential Statistics
---

<div>
  <h2>Inferential Statistics</h2>

  <hr>

  <h3>1. The Normal Distribution, Empirical Rule &amp; Z-Scores</h3>
  <p><strong>Normal Distribution:</strong> a continuous, bell-shaped curve defined by mean μ and standard deviation σ.</p>
  <p><strong>Empirical Rule:</strong>  
    <ul>
      <li>≈ 68 % of data within μ ± 1σ</li>
      <li>≈ 95 % within μ ± 2σ</li>
      <li>≈ 99.7 % within μ ± 3σ</li>
    </ul>
  </p>
  <p><strong>Z-Score:</strong> number of standard deviations a value x is from the mean:  
    $$z = \frac{x - \mu}{\sigma}$$  
    <strong>Example:</strong> If heights are N(μ=170 cm, σ=10 cm), what is the z-score of 185 cm?  
    $$z = \frac{185 - 170}{10} = 1.5$$  
    → 185 cm is 1.5σ above the mean.
  </p>

  <hr>

  <h3>2. Sampling &amp; Inferential Statistics</h3>
  <p><strong>Population vs. Sample:</strong> population is the full set; a sample is a subset used to estimate population parameters.</p>
  <p>By analyzing sample statistics (like \(\bar{x}\), s), we draw conclusions (“infer”) about μ and σ of the population.</p>
  <p><strong>Example:</strong> Survey 200 students’ GPAs to estimate the average GPA of all 5,000 students at a university.</p>

  <hr>

  <h3>3. The Central Limit Theorem</h3>
  <p>Regardless of the population’s distribution, the distribution of sample means \(\bar{x}\) approaches normal as sample size n grows.</p>
  <p>Key facts:  
    <ul>
      <li>Mean of \(\bar{x}\) = μ</li>
      <li>Standard error SE = σ / √n</li>
    </ul>
  </p>
  <p><strong>Example:</strong> If individual test scores have μ=75, σ=12, then the mean of 36-student samples is approx. N(75, 12/√36=2).</p>

  <hr>

  <h3>4. Confidence Intervals</h3>
  <p>A confidence interval (CI) gives a range of plausible values for a population parameter.</p>
  <p>For a mean (σ known):  
    $$\bar{x} \pm z^* \frac{\sigma}{\sqrt{n}}$$  
    where z* is the critical value (e.g. 1.96 for 95 % CI).</p>
  <p><strong>Example:</strong> Sample of n=49 yields \(\bar{x}=100\), σ=14.  
    95 % CI = \(100 \pm 1.96·(14/7) = 100 \pm 3.92 = [96.08,\;103.92]\).</p>

  <hr>

  <h3>5. Hypothesis Testing</h3>
  <p>Procedure for testing claims about a population:</p>
  <ol>
    <li>State H₀ (null) and H₁ (alternative).</li>
    <li>Choose significance level α (e.g. 0.05).</li>
    <li>Compute test statistic (z, t, χ², etc.).</li>
    <li>Find p-value or critical region.</li>
    <li>Reject H₀ if p ≤ α; otherwise fail to reject.</li>
  </ol>
  <p><strong>Example:</strong> Test if a coin is fair. Flip 100 times, get 60 heads.  
    Under H₀: p=0.5, z = (0.60–0.50)/√(0.5·0.5/100) = 2 → p≈0.045. Since p<0.05, reject fairness.
  </p>

  <hr>

  <h3>6. Three Methods of Hypothesis Testing</h3>
  <ul>
    <li><strong>Z-Test</strong> (σ known, large n):  
      Test statistic \(z = (\bar{x}-\mu_0)/(σ/√n)\).  
      <strong>Example:</strong> Verify avg. battery life vs. 10 hrs with known σ=2 hrs, sample n=64, \(\bar{x}=10.5\).</li>
    <li><strong>t-Test</strong> (σ unknown, small n):  
      \(t = (\bar{x}-\mu_0)/(s/√n)\) with df=n–1.  
      <strong>Example:</strong> Compare mean weight loss vs. 5 kg in n=16 participants, sample mean=6 kg, s=1.5 kg.</li>
    <li><strong>Chi-Square Test</strong> (categorical or variance):  
      \(\chi^2 = \sum\frac{(O-E)^2}{E}\).  
      <strong>Example:</strong> Goodness-of-fit: roll a die 120 times, observe counts vs. expected 20 each; test fairness.</li>
  </ul>
</div>
