---
layout: default
title: Financial Mathematics
---

<div>
  <h2>Financial Mathematics</h2>

  <p>This chapter deals with compound interest, present and future values, regular payments, loans, and real-life applications using geometric series.</p>

  <hr>

  <h3>1. Compound Interest</h3>
  <p>Compound interest is earned each period on the initial amount and the interest that has already been added.</p>
  <p>The formula is:</p>
  <div>$$
  A = P(1 + r)^n
  $$</div>
  <ul>
    <li><em>A</em>: final amount</li>
    <li><em>P</em>: principal (starting amount)</li>
    <li><em>r</em>: interest rate per period (as a decimal)</li>
    <li><em>n</em>: number of periods</li>
  </ul>

  <p><strong>Example:</strong> 1000 euro invested for 3 years at 5% annual interest:</p>
  <div>$$
  A = 1000(1.05)^3 = 1000 \times 1.157625 = 1157.63
  $$</div>

  <hr>

  <h3>2. Present Value</h3>
  <p>This is the amount you'd need to invest today to get a known future amount:</p>
  <div>$$
  P = \frac{A}{(1 + r)^n}
  $$</div>

  <p><strong>Example:</strong> What is 2000 euro due in 4 years worth today at 3%?</p>
  <div>$$
  P = \frac{2000}{(1.03)^4} = \frac{2000}{1.1255} \approx 1777.99
  $$</div>

  <hr>

  <h3>3. Future Value of Regular Payments</h3>
  <p>When you save the same amount each period into an account that earns interest, the total grows as a geometric series.</p>
  <div>$$
  FV = R \cdot \frac{(1 + r)^n - 1}{r}
  $$</div>

  <p><strong>Example:</strong> Save 100 euro per month for 12 months at 1% monthly interest:</p>
  <div>$$
  FV = 100 \cdot \frac{(1.01)^{12} - 1}{0.01} = 100 \cdot 12.6825 = 1268.25
  $$</div>

  <hr>

  <h3>4. Present Value of Regular Payments</h3>
  <p>This is the value now of receiving or paying a fixed amount each period:</p>
  <div>$$
  PV = R \cdot \frac{1 - (1 + r)^{-n}}{r}
  $$</div>

  <p><strong>Example:</strong> What is the present value of receiving 500 euro per year for 5 years at 4%?</p>
  <div>$$
  PV = 500 \cdot \frac{1 - (1.04)^{-5}}{0.04} = 500 \cdot 4.4518 = 2225.88
  $$</div>

  <hr>

  <h3>5. Loans and Annuities</h3>
  <p>Loan repayments are based on the present value formula. The present value of repayments must equal the amount borrowed.</p>

  <p><strong>Example:</strong> Borrow 10,000 euro for 5 years at 6% annual interest. Find yearly repayments.</p>
  <div>$$
  10000 = R \cdot \frac{1 - (1.06)^{-5}}{0.06}
  $$</div>
  <div>$$
  R = \frac{10000}{4.21236} \approx 2373.91
  $$</div>

  <hr>

  <h3>6. Effective Interest Rate</h3>
  <p>If interest is compounded more than once a year, the actual annual rate is called the effective rate:</p>
  <div>$$
  r_{\text{eff}} = \left(1 + \frac{r}{m}\right)^m - 1
  $$</div>
  <ul>
    <li><em>r</em>: nominal annual rate</li>
    <li><em>m</em>: number of compounding periods per year</li>
  </ul>

  <p><strong>Example:</strong> A rate of 6% compounded monthly gives:</p>
  <div>$$
  r_{\text{eff}} = (1.005)^{12} - 1 = 0.06168 = 6.17\%
  $$</div>

  <hr>

  <h3>7. Geometric Series Applications</h3>
  <p>All the formulas above for compound interest, savings, and repayments are derived from geometric series.</p>
  <p>Each regular payment earns interest and forms a term in the series.</p>

  <p><strong>Example:</strong> Save 500 euro yearly for 5 years at 4% interest:</p>
  <div>$$
  FV = 500 + 500(1.04) + 500(1.04)^2 + 500(1.04)^3 + 500(1.04)^4
  $$</div>
  <p>This is a geometric series with first term 500 and ratio 1.04:</p>
  <div>$$
  FV = 500 \cdot \frac{(1.04)^5 - 1}{0.04} = 500 \cdot 5.4163 = 2708.15
  $$</div>

  <hr>

  <h3>8. Real-Life Example: Car Loan</h3>
  <p>You borrow 12,000 euro to buy a car. Interest is 5% annually, repaid monthly for 4 years.</p>
  <ul>
    <li>Monthly rate: \(r = \frac{0.05}{12} = 0.004167\)</li>
    <li>Number of payments: \(n = 48\)</li>
  </ul>

  <div>$$
  12000 = R \cdot \frac{1 - (1 + 0.004167)^{-48}}{0.004167}
  $$</div>
  <div>$$
  R \approx 276.25
  $$</div>
  <p>So you repay about 276.25 euro each month.</p>

</div>
