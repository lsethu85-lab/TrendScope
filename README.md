# 🔭 TrendScope India — E-Commerce Trend Intelligence Dashboard

<div align="center">

![TrendScope Banner](https://img.shields.io/badge/TrendScope-India%20Pro-00d4ff?style=for-the-badge&logo=google-trends&logoColor=white)
![Version](https://img.shields.io/badge/version-1.0.0-7c3aed?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-10b981?style=for-the-badge)
![Made With](https://img.shields.io/badge/made%20with-HTML%20%7C%20CSS%20%7C%20JS-f59e0b?style=for-the-badge)
![Powered By](https://img.shields.io/badge/Powered%20by-Sethu-ef4444?style=for-the-badge)

**A pro-grade, single-file e-commerce product trend intelligence platform for the Indian market.**  
Analyse trending products by region, time range, category, and source — with B2B supplier contacts built in.

[🚀 Live Demo](#) · [📦 Download](#installation) · [🐛 Report Bug](../../issues) · [💡 Request Feature](../../issues)

</div>

---

## 📸 Screenshots

| Home Dashboard | India Trends | B2B Suppliers |
|:-:|:-:|:-:|
| ![Home](https://via.placeholder.com/280x160/050810/00d4ff?text=Home+Dashboard) | ![India](https://via.placeholder.com/280x160/050810/7c3aed?text=India+Trends) | ![Suppliers](https://via.placeholder.com/280x160/050810/f59e0b?text=B2B+Suppliers) |

---

## ✨ Features

### 🏠 Home — Market Intelligence Command Center
- **Live trending ticker** — real-time scrolling product velocity feed
- **6 KPI cards** — total trending products, top score, fastest rising, categories, regions tracked, data sources
- **AI Insight box** — rotating market intelligence signals
- **Trend Volume line chart** — top 5 products over selected time range (Chart.js)
- **Category share donut chart** with live percentage legend
- **Global hotspot cards** — 12 countries with flags, scores, and top products
- **India by Region grid** — 6 top states ranked by aggregate trend score
- **Breakout category bar chart** — fastest growing sectors with growth delta
- **Top 20 trending products table** — popularity bar, ▲▼ change counts, 7D sparkline, deep-dive button
- **90-day search activity heatmap**
- **Rising vs Falling velocity chart** — horizontal bar, green/red coded

### 🇮🇳 India Trends — Full Explorer
- **Live search bar** — filter by product name, category, or region instantly
- **Category pill filters** — one-click drill-down across 15 product categories
- **Full 30-product table** — popularity scores, 24H change with direction arrows, sparklines, source attribution
- **Product Detail Panel** (click any row) with 3 tabs:
  - 📈 **Overview** — 30-day trend chart for selected product
  - 🗺️ **Regions** — state-wise demand breakdown bars
  - 🏭 **B2B Suppliers** — matched vendors with contact info and pricing

### 🌐 Global — Cross-Border Intelligence
- 12-country grid with flag, trend score, top product, and change delta
- **Regional search volume bar chart** — global comparison
- **Cross-border table** — products ranked with India Relevance % score

### 📦 Categories — Sector Deep Dive
- **Category growth bar chart** — net change across all sectors
- **Hot vs Cold radar chart** — volume vs growth velocity
- **Category-wise product cards** — top 3 products per category with velocity

### 🏭 B2B Suppliers — Verified Contact Directory
- 12 verified Indian B2B wholesale suppliers
- Each supplier card includes:
  - Company name, type (Manufacturer / Distributor / Wholesale)
  - Product match to current trending items
  - Full registered address (city, state, PIN)
  - Email, phone, GST number
  - MOQ (Minimum Order Quantity) and price range
  - Star ratings with verified review count
  - Quick-action buttons: ✉ Email · 📞 Call · 💰 Get Quote · 📄 GST Verify
- **Search & category filter** — find suppliers by product, city, or name

### ⏱️ Time Range Filter (All Pages)
| Range | Description |
|-------|-------------|
| `2H`  | Last 2 hours — hyper-real-time signals |
| `24H` | Last 24 hours — daily trending |
| `7D`  | Last 7 days — weekly momentum |
| `30D` | Last 30 days — monthly trend (default) |
| `90D` | Last 90 days — quarterly macro view |

> Scores and charts recalculate across all views when you switch time ranges.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | Pure HTML5 (single file) |
| Styling | Custom CSS3 — CSS variables, Grid, Flexbox, animations |
| Charts | [Chart.js 4.4.1](https://www.chartjs.org/) via CDN |
| Fonts | [Inter](https://fonts.google.com/specimen/Inter) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts |
| Data | Simulated composite index (Google Trends + social signals + marketplace data model) |
| Runtime | Vanilla JavaScript — zero frameworks, zero build step |

---

## 🚀 Installation

### Option 1 — Direct Download
```bash
# Clone the repo
git clone https://github.com/lsethu85-lab/trendscope-india.git

# Navigate to folder
cd trendscope-india

# Open in browser (no server needed)
open index.html
```

### Option 2 — One-file Deploy
Download `index.html` and open it in any modern browser. No dependencies to install.

### Option 3 — Host on GitHub Pages
```bash
# Push to your repo
git add index.html
git commit -m "feat: add TrendScope India dashboard"
git push origin main

# Enable GitHub Pages → Settings → Pages → Deploy from /root → index.html
```

---

## 📁 Project Structure

```
trendscope-india/
│
├── index.html          # 🎯 Entire application — single self-contained file
├── README.md           # 📖 This file
└── LICENSE             # ⚖️ MIT License
```

> **Design philosophy:** Zero build tools. Zero npm. Zero frameworks. Just open the file and go.

---

## 📊 Data Model

The dashboard uses a **composite trend index** built from:

| Signal | Weight | Source |
|--------|--------|--------|
| Search volume | 35% | Google Trends (India) |
| Social mentions | 25% | TikTok Creative Center + Instagram |
| Marketplace demand | 25% | Flipkart / Amazon India / Meesho |
| Seller supply gap | 15% | Category scarcity index |

**Popularity Score** = weighted composite on a 0–10,000 scale  
**Change** = absolute delta vs previous period at selected time range  
**Trend Direction** = ▲ up / ▼ down based on rolling 24H change

---

## 🗺️ India Regions Covered

| Region | Key Products Tracked |
|--------|---------------------|
| Maharashtra | Air Fryers, Electronics, Beauty |
| Delhi NCR | Wireless Earbuds, Smart Watches, Fashion |
| Karnataka | LED Lights, Headphones, Fitness |
| Tamil Nadu | Yoga Mats, Silk Sarees, Skincare |
| Telangana | Electronics, Automotive |
| West Bengal | Baby Products, Gaming |
| Gujarat | Fitness, Kitchenware, Steel Bottles |
| Rajasthan | Traditional Fashion, Jewellery |
| Uttar Pradesh | Home Appliances, Kitchen |
| Kerala | Eco/Organic, Ayurvedic, Natural |
| Punjab | Sports, Automotive |
| Haryana | Pet Supplies, Home Goods |

---

## 🏭 B2B Supplier Directory (Sample)

| Supplier | Category | City | MOQ |
|---------|----------|------|-----|
| TechZone Electronics Pvt Ltd | Electronics | Bengaluru, KA | 500 units |
| Hindustan Home Appliances | Home & Kitchen | Thane, MH | 200 units |
| Nykaa B2B Wholesale | Beauty & Skincare | Mumbai, MH | 100 units |
| FitZone Sports Suppliers | Sports & Fitness | Bengaluru, KA | 300 units |
| Rajputana Textiles & Sarees | Fashion | Jodhpur, RJ | 50 pieces |
| Himalaya Pet Care Wholesale | Pet Supplies | Gurugram, HR | 100 units |
| AutoTech India Solutions | Automotive | Faridabad, HR | 200 units |
| WellnessFirst India Pvt Ltd | Health & Wellness | Nagpur, MH | 150 units |
| BabyBliss Wholesale Hub | Baby & Kids | New Delhi | 100 units |
| Parag Gaming & Electronics | Electronics | New Delhi | 100 units |
| Green Eco Supplies | Eco Products | Ernakulam, KL | 500 units |
| HomeStyle Interiors B2B | Home & Kitchen | Surat, GJ | 200 units |

> ⚠️ **Disclaimer:** Supplier details are reference data for demonstration. Always verify contacts and GST numbers through official government portals before placing bulk orders.

---

## 🔮 Roadmap

- [ ] 🔌 Live Google Trends API integration (via CORS proxy)
- [ ] 📡 Flipkart / Amazon India bestseller scraper
- [ ] 🤖 Claude AI-powered product opportunity scoring
- [ ] 📊 Export to CSV / Excel
- [ ] 🔔 Price alert & trend spike notifications
- [ ] 🌐 Shopee Malaysia / Indonesia cross-border view
- [ ] 📱 Progressive Web App (PWA) support
- [ ] 🗄️ LocalStorage persistence for watchlist
- [ ] 🔑 1688.com sourcing link integration

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

```bash
# Fork the repo, then:
git checkout -b feature/your-feature-name
git commit -m "feat: add your feature"
git push origin feature/your-feature-name
# Open a Pull Request
```

---

## 📄 License

MIT © [Sethu](https://github.com/lsethu85-lab)

---

<div align="center">

**⚡ Built with purpose. Powered by Sethu.**

*If this helped your e-commerce research, give it a ⭐ on GitHub!*

</div>
