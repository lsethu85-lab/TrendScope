# TrendScope India — E-Commerce Trend Intelligence & Seller Tools

TrendScope India is a front-end e-commerce intelligence dashboard built for Indian online sellers, marketplace operators, resellers, and D2C brands. It provides trend analytics, keyword research, marketplace listing tools, seller calculators, compliance checks, image utilities, and video-generation-style tools in a single static HTML application.

The project is designed to run fully in the browser using free client-side resources such as HTML, CSS, JavaScript, Canvas, file uploads, and browser-based media recording.

---

## Author

**Sethuraman Lakshminarayanan**

---

## Project Overview

TrendScope India helps sellers explore product trends, analyze categories, generate marketplace-ready listing content, calculate selling costs, and create basic seller assets without requiring a backend or paid API.

The dashboard is especially focused on Indian marketplaces such as:

- Amazon India
- Flipkart
- Meesho
- Myntra
- Shopify-based D2C stores

---

## Key Features

### Market Intelligence Dashboard

- Trending product dashboard
- India trend explorer
- Global trend map
- Category deep dive
- B2B supplier directory
- Trend score indicators
- Regional demand insights
- Category share charts
- Rising and falling trend analysis

---

## All Tools Hub

The **All Tools** section includes multiple seller-focused tools built directly into the website.

### Listing & SEO Tools

- Marketplace-ready content generator
- Marketplace keyword research
- Product description generator
- Competitor listing analyzer
- Listing quality scorer
- Marketplace compliance checker

### Marketplace Calculators

- GST calculator
- Shipping cost calculator
- Amazon fee calculator
- Flipkart fee calculator
- Meesho fee calculator

### Seller Utility Tools

- Barcode generator
- Invoice generator
- Return policy generator
- Bulk image upload analyzer

### Creative Tools

- AI-style product image generator using browser Canvas
- AI-style product video generator using browser Canvas and MediaRecorder
- Bulk product image preview and analysis

---

## Tools Included

### 1. Marketplace Keyword Research

Generate keyword ideas for:

- Amazon India
- Flipkart
- Meesho
- All marketplaces

Keyword groups include:

- Primary keywords
- Long-tail keywords
- Buyer-intent keywords
- Question-based keywords
- Competitor-style keywords

---

### 2. Marketplace-ready Content Generator

Generate listing content including:

- SEO-friendly title
- Bullet points
- Product description
- Search keywords
- Marketplace-specific formatting

Supported marketplaces:

- Amazon India
- Flipkart
- Meesho
- Shopify
- Myntra

---

### 3. Competitor Listing Analyzer

Analyze competitor listing text and get:

- Listing quality score
- Keyword signal detection
- Content gaps
- Improvement recommendations
- Title and description feedback

---

### 4. Product Description Generator

Generate product descriptions in different tones:

- Professional
- Premium
- Budget Friendly
- Hinglish Simple

---

### 5. Barcode Generator

Generate downloadable barcode images.

Supported formats:

- EAN-13 style barcode
- Code 128 style barcode

Output:

- PNG download using HTML Canvas

---

### 6. Shipping Cost Calculator

Estimate shipping cost using:

- Product weight
- Package dimensions
- Volumetric weight
- Local, zonal, and national delivery zones
- Prepaid or COD payment mode

Courier-style comparisons include:

- Delhivery
- Blue Dart
- DTDC
- Ecom Express
- XpressBees
- India Post
- Shadowfax

---

### 7. Return Policy Generator

Create seller-friendly return policies based on:

- Brand or store name
- Return window
- Refund/replacement type
- Product condition rules

---

### 8. Listing Quality Scorer

Score marketplace listings based on:

- Title length
- Bullet count
- Keyword count
- Keyword relevance
- Feature coverage
- Content quality

---

### 9. GST Calculator

Calculate GST using:

- 0%
- 5%
- 12%
- 18%
- 28%

Supports:

- GST inclusive calculation
- GST exclusive calculation
- CGST + SGST split
- IGST calculation

---

### 10. Invoice Generator

Generate simple seller invoices with:

- Seller name
- Buyer name
- Invoice number
- Product name
- Quantity
- Price
- GST rate
- Total invoice amount

Output:

- HTML invoice preview
- Downloadable invoice HTML file

---

### 11. Amazon Fee Calculator

Estimate Amazon selling profit using:

- Selling price
- Product cost
- Referral fee
- Closing fee
- Shipping fee
- GST on fees
- Profit and margin calculation

---

### 12. Flipkart Fee Calculator

Estimate Flipkart selling profit using:

- Selling price
- Product cost
- Commission percentage
- Fixed fee
- Shipping fee
- GST on fees
- Profit and margin calculation

---

### 13. Meesho Fee Calculator

Estimate Meesho selling profit using:

- Selling price
- Product cost
- Shipping zone
- Product weight
- Shipping GST
- Profit and margin calculation

---

### 14. AI-style Product Image Generator

Generate product creatives using browser Canvas.

Features:

- Product name input
- Theme selection
- Product image upload
- Product image preview
- Canvas-generated marketplace creative
- PNG download

Themes include:

- Marketplace White
- Neon Tech
- Luxury Gold
- Eco Green

---

### 15. AI-style Product Video Generator

Generate a short product promotional video using browser Canvas and MediaRecorder.

Features:

- Product name input
- Feature input
- Marketplace promo style
- Canvas animation
- WebM video generation
- Downloadable video output

---

### 16. Bulk Image Uploads

Upload and preview multiple product images.

Features:

- Multi-image upload
- Image preview grid
- Bulk image analysis
- Listing and image-QC suggestions

---

## Technology Stack

This project uses:

- HTML5
- CSS3
- JavaScript
- Chart.js
- HTML Canvas
- Browser FileReader API
- Browser Blob API
- Browser MediaRecorder API
- Local browser execution

No backend is required for the current version.

---

## Project Structure

```text
/
├── index.html
├── README.md
└── assets/
    └── optional images or supporting files
```

If you are using the latest generated version, rename the HTML file to:

```text
index.html
```

Recommended file:

```text
index_all_tools_full.html
```

Rename it before publishing:

```text
index.html
```

---

## How to Run Locally

### Option 1: Open directly

Open the HTML file in your browser:

```text
index.html
```

### Option 2: Run with a local server

Using Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## How to Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload the project files.
3. Rename the main HTML file to:

```text
index.html
```

4. Go to:

```text
Settings → Pages
```

5. Select:

```text
Deploy from branch
```

6. Choose:

```text
main branch / root
```

7. Save and wait for GitHub Pages to publish the site.

---

## Notes

- All calculators are estimate-based and should be verified with official marketplace dashboards, courier contracts, GST rules, and professional tax advice.
- The product image and video generators are browser-based creative tools and do not use paid AI APIs.
- The project is designed as a static front-end prototype and can be extended with backend APIs, databases, authentication, and real marketplace integrations.

---

## Future Enhancements

Planned improvements may include:

- Real marketplace API integration
- Live keyword volume data
- Seller account dashboard
- Product SKU database
- CSV import/export
- PDF invoice export
- Real barcode standard validation
- QR code generation
- Advanced AI listing generation
- Image background removal
- Product feed export for Amazon, Flipkart, and Meesho
- Cloud storage for uploaded product images

---

## Disclaimer

This tool is provided for informational and productivity purposes only. Marketplace fees, GST rules, shipping rates, and compliance policies may change over time. Always verify financial, tax, and marketplace information with official sources before making business decisions.

---

## License

This project can be released under the MIT License.

```text
MIT License

Copyright (c) 2026 Sethuraman Lakshminarayanan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files, to deal in the Software
without restriction, including without limitation the rights to use, copy,
modify, merge, publish, distribute, sublicense, and/or sell copies of the
Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## Author

Built by **Sethuraman Lakshminarayanan**.
