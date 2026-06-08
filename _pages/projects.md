---
title: "Projects"
layout: single
permalink: /projects/
author_profile: true
projects:
  - title: "Food-Cost Calculator"
    category: "Cost Control · Food Cost & Yield"
    description: "Cost a recipe line-by-line with trim-yield adjustment, then test it against a target food-cost % and concept benchmark."
    url: "/tools/food-cost-calculator.html"
  - title: "Supplier Scorecard"
    category: "Supplier Management"
    description: "Six weighted KPIs generate a 1–5 performance rating, radar profile, and a recommended retain / develop / replace action."
    url: "/tools/supplier-scorecard.html"
  - title: "Menu Engineering Matrix"
    category: "Menu Profitability"
    description: "Plot dishes by popularity and contribution margin into Stars, Plowhorses, Puzzles, and Dogs using the Kasavana–Smith model."
    url: "/tools/menu-engineering.html"
  - title: "TCO Comparison Tool"
    category: "Sourcing Strategy · Total Cost of Ownership"
    description: "Compare suppliers on true landed cost across acquisition, ownership, and end-of-life — proving the cheapest unit price is rarely the cheapest supplier."
    url: "/tools/tco-comparison.html"
  - title: "Kraljic Matrix"
    category: "Sourcing Strategy · Category Positioning"
    description: "Position purchase categories on supply risk vs. profit impact into Strategic, Leverage, Bottleneck, and Non-critical — with the right sourcing strategy for each."
    url: "/tools/kraljic-matrix.html"
  - title: "Seasonal Break-Even Map"
    category: "Revenue Management · Seasonal Break-Even"
    description: "Track annual hotel break-even as a cumulative recovery line — net of per-channel cost and seasonal step costs — pinpointing the date peak and event weeks clear the year-round fixed nut."
    url: "/tools/seasonal-breakeven-map.html"
  - title: "F&B P&L & Prime-Cost Dashboard"
    category: "Operations & Budgeting · F&B P&L"
    description: "A live departmental P&L — revenue in, cost of sales and labour out, prime cost and GOP computed, with flow-through modelling on incremental revenue."
    url: "/tools/fb-pnl-dashboard.html"    
---

F&B procurement and cost-control tools I'm building as I train toward RNCP certification. Each one turns a standard industry framework into something I can run on real numbers — the way a hotel-group buyer or cost controller would.

<style>
.proj-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
  gap:1.25em;
  margin:1.75em 0;
}
.proj-card{
  display:flex;
  flex-direction:column;
  border:1px solid #e8e8e8;
  border-radius:8px;
  padding:1.4em 1.4em 1.5em;
  transition:box-shadow .25s ease, transform .25s ease;
}
.proj-card:hover{
  box-shadow:0 10px 30px -12px rgba(0,0,0,.22);
  transform:translateY(-4px);
}
.proj-card .eyebrow{
  font-size:.68em;
  letter-spacing:.1em;
  text-transform:uppercase;
  color:#8a8a8a;
  font-weight:700;
  margin-bottom:.55em;
}
.proj-card h3{
  margin:0 0 .45em;
  font-size:1.2em;
  line-height:1.2;
}
.proj-card p{
  font-size:.86em;
  line-height:1.5;
  color:#5e5e5e;
  flex:1;
  margin:0 0 1.2em;
}
.proj-card .btn{align-self:flex-start;margin:0;}
</style>

<div class="proj-grid">
{% for p in page.projects %}
  <div class="proj-card">
    <div class="eyebrow">{{ p.category }}</div>
    <h3>{{ p.title }}</h3>
    <p>{{ p.description }}</p>
    <a class="btn btn--primary" href="{{ p.url }}">Open tool →</a>
  </div>
{% endfor %}
</div>

## About this toolkit

I'm building formal procurement and supply-chain credentials on top of hands-on F&B operations experience — supplier relationships, food-cost management, and full P&L responsibility in an upscale Riviera market.

These tools are how I study: each turns a textbook framework into something I can run on real numbers, the way a hotel-group procurement manager or cost controller would. The code is mine; the methods are industry-standard.
