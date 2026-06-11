# 🛠️ Procurement & Logistics Toolkit

> A free, browser-based toolkit for supply chain and procurement professionals — no login, no install, no cost.

**[▶ Live Demo →](https://ofrank-design.github.io/procurement-logistics-toolkit)**

---

## What's Inside

Four practical tools in one clean web app:

| Tool | What it does |
|------|-------------|
| 📦 **EOQ & Safety Stock Calculator** | Calculates Economic Order Quantity, reorder point, safety stock, and annual inventory cost |
| ⚠️ **Supplier Risk Dashboard** | Scores suppliers across delivery, quality, financial stability, and compliance — weighted automatically |
| 🚚 **Logistics Cost Estimator** | Estimates freight costs by route, weight, distance, and transport mode with fuel surcharge and insurance |
| 📋 **Ghana e-GP Tender Tracker** | Tracks tender stages, deadlines, and portfolio value aligned to Ghana PPA Acts 663 & 914 |

---

## Who This Is For

- Procurement officers and supply chain analysts
- Students studying SCM, logistics, or public procurement
- NGOs and public sector teams working with Ghana e-GP
- Anyone who needs a quick, no-frills procurement calculator

---

## Features

- ✅ Fully browser-based — works offline, no backend needed
- ✅ Ghana context — GHS currency, Acts 663 & 914, e-GP tender stages
- ✅ Multi-currency support — GHS, USD, NGN, KES
- ✅ Pre-loaded with demo data so you can see it working immediately
- ✅ Mobile friendly
- ✅ Zero dependencies — pure HTML, CSS, and JavaScript

---

## How to Use

**Option 1 — Use the live version:**
Go to [ofrank-design.github.io/procurement-logistics-toolkit](https://ofrank-design.github.io/procurement-logistics-toolkit) — nothing to install.

**Option 2 — Run it locally:**
```bash
git clone https://github.com/Ofrank-design/procurement-logistics-toolkit.git
cd procurement-logistics-toolkit
# Open index.html in any browser
```

**Option 3 — Fork and customize:**
Click the **Fork** button at the top of this page, then edit `index.html` to match your organization's needs — rates, currency, tender stages, risk weights.

---

## EOQ Formula Reference

```
EOQ = √(2DS / H)

D = Annual demand (units)
S = Ordering cost per order
H = Holding cost per unit per year
```

Reorder Point = (Daily demand × Lead time) + Safety stock

---

## Supplier Risk Scoring

Scores are weighted across four dimensions:

| Dimension | Weight |
|-----------|--------|
| On-time delivery | 30% |
| Quality rejection rate | 30% |
| Financial stability | 20% |
| Regulatory compliance | 20% |

Scores of **7–10** = Low risk · **4–6** = Medium risk · **1–3** = High risk

---

## Logistics Rate Reference

Rates used in the estimator (per kg per km):

| Mode | Base Rate |
|------|-----------|
| 🚚 Road | 0.08 |
| 🚃 Rail | 0.05 |
| ✈️ Air | 0.95 |
| 🚢 Sea | 0.03 |

Fuel surcharge and insurance are applied on top.

---

## Contributing

Contributions are welcome. If you work in procurement or logistics and want to improve the tool — better rate tables, additional currencies, new features — open a pull request or raise an issue.

---

## About the Author

Built by **Frank Oduro** — BSc Procurement & Supply Chain Management student at Kumasi Technical University (KSTU), Ghana. 

Building real, usable tools from Day 1 of study.

- 🌐 [Portfolio](https://ofrank-design.github.io)
- 💼 [LinkedIn](https://linkedin.com/in/ofrank-design)
- 🐙 [GitHub](https://github.com/Ofrank-design)

---

## License

MIT — free to use, fork, and adapt. A ⭐ star is appreciated if this saves you time.

---

*Made in Kumasi, Ghana 🇬🇭*
