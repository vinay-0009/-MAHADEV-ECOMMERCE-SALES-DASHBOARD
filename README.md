<!-- Save this as README.html or paste the inner HTML into your GitHub project page -->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Mahadev Ecommerce Sales Dashboard</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: #0f1724;
      color: #e6eef8;
      line-height: 1.5;
      padding: 28px;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius: 10px;
      padding: 28px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.6);
      border: 1px solid rgba(255,255,255,0.04);
    }
    h1 {
      font-size: 24px;
      letter-spacing: 0.6px;
      margin: 0 0 12px 0;
    }
    .subtitle {
      color: #bcd2ff;
      margin-bottom: 18px;
      font-size: 14px;
    }
    .cover {
      width: 100%;
      border-radius: 8px;
      overflow: hidden;
      margin-bottom: 18px;
      border: 1px solid rgba(255,255,255,0.04);
    }
    .section-title {
      color: #d9e6ff;
      margin: 14px 0 8px;
      font-weight: 600;
    }
    ul {
      margin: 8px 0 12px 20px;
    }
    li {
      margin: 6px 0;
    }
    .kpi {
      background: rgba(255,255,255,0.02);
      border-radius: 8px;
      padding: 10px;
      display: inline-block;
      margin-right: 8px;
      margin-bottom: 10px;
      font-weight: 600;
    }
    .tech-list {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
    }
    .tech-item {
      background: rgba(255,255,255,0.02);
      padding: 6px 10px;
      border-radius: 6px;
      font-size: 13px;
    }
    .impact {
      background: rgba(255,255,255,0.01);
      padding: 12px;
      border-radius: 8px;
      margin-top: 12px;
    }
    footer { font-size: 13px; color: #98a8d8; margin-top: 18px; }
    @media (max-width:600px) {
      .container { padding: 18px; }
      h1 { font-size: 20px; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>📊 Mahadev Ecommerce Sales Dashboard</h1>
    <div class="subtitle">
      End-to-end BI project to track and analyze sales, profit, and customer insights for an ecommerce business. Interactive visualizations help uncover trends and enable data-driven decisions.
    </div>

    <!-- Replace the src with the exact path of the image in your repo (e.g., ./images/mahadev_ecommerce_dashboard.jpg) -->
    <div class="cover">
      <img src="./mahadev_ecommerce_dashboard.jpg" alt="Mahadev Ecommerce Sales Dashboard" style="width:100%; display:block;">
    </div>

    <div>
      <div class="section-title">🔹 Highlights</div>
      <div class="kpi">Total Sales: <strong>438K</strong></div>
      <div class="kpi">Profit: <strong>37K</strong></div>
      <div class="kpi">Quantity: <strong>5615</strong></div>
      <div class="kpi">Average Order Value: <strong>121K</strong></div>

      <ul>
        <li><strong>Geographical Insights</strong> — Sales performance by states (Maharashtra, Madhya Pradesh, Uttar Pradesh, Delhi).</li>
        <li><strong>Category & Sub-Category Breakdown</strong> — Contribution and profitability across Furniture, Electronics, Clothing, Printers, Sarees, etc.</li>
        <li><strong>Customer Analysis</strong> — Identify top customers driving revenue.</li>
        <li><strong>Payment Mode Insights</strong> — UPI, COD, EMI, Cards distribution.</li>
        <li><strong>Profit Trends</strong> — Month-wise profit analysis for seasonality detection.</li>
      </ul>

      <div class="section-title">🔹 Tools & Technologies</div>
      <div class="tech-list">
        <div class="tech-item">Power BI</div>
        <div class="tech-item">SQL</div>
        <div class="tech-item">Excel</div>
        <div class="tech-item">Python (optional)</div>
      </div>

      <div class="section-title">🔹 Impact</div>
      <div class="impact">
        <ul>
          <li>✔ Clean, transform, and model large datasets for analytics.</li>
          <li>✔ Build interactive dashboards for stakeholders to monitor KPIs.</li>
          <li>✔ Extract actionable insights to optimize product mix, pricing, and marketing strategies.</li>
        </ul>
      </div>
    </div>

    <footer>
      Tip: place <code>mahadev_ecommerce_dashboard.jpg</code> in your repo root or an <code>images/</code> folder and update the <code>img src</code> path accordingly.
    </footer>
  </div>
</body>
</html>
