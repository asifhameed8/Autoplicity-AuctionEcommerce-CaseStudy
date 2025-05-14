# 🚗 Autoplicity – Scalable Automotive Auction & eCommerce Platform (Case Study)

🔧 **Role:** Lead Developer – Architecture, Integration & Customization  
📅 **Date:** January 2024  
🧱 **Tech Stack:** ASP.NET Core · NopCommerce · Angular · ASP.NET MVC · Web API  

---

## 🔍 Project Overview

I engineered a high-performance, enterprise-grade automotive platform for **Autoplicity**, tailored for B2C sales at scale. The solution leverages:

- ⚙️ **ASP.NET Core + NopCommerce** for a modular, plugin-driven architecture  
- 🔍 **VIN-based search & YMM filtering** for personalized product discovery  
- 🚗 **Live inventory sync** for 500,000+ SKUs  
- 💳 **Optimized checkout** with custom admin workflows  
- 📦 **Scalable backend** supporting auctions, product management, and real-time pricing

> This platform was purpose-built for **high-volume eCommerce and custom automotive auctions**, with a focus on performance, extensibility, and conversions.

---

## ✅ Key Features

- 🛒 Custom **Car Auction System** with bidding & real-time updates  
- 🔍 **Year/Make/Model (YMM)** filtering and VIN compatibility lookup  
- 🧠 Inventory sync for **500K+ SKUs**  
- 🔧 Tailored admin panel with **role-based access control**  
- 💬 NopCommerce-based checkout, reviews & loyalty features  
- 📱 Responsive UI for mobile-first shoppers

---

## 🖼️ Screenshots

### 🎬 Platform Banner

![Autoplicity Banner](screenshots/autoplicity-banner.png)

### 🛞 Product Grid – Dynamic Listings

![Autoplicity Grid](screenshots/autoplicity-grid.png)

### 📄 Product Detail Page – Tire Match

![Autoplicity Product](screenshots/autoplicity-detail.png)

---

## ⚙️ Tech Stack Overview

| Layer        | Technology                      |
|--------------|----------------------------------|
| Backend      | NopCommerce 4.60+ (.NET 7)       |
| API Bridge   | Custom NopCommerce REST Plugin   |
| Frontend     | Angular 16+                      |
| Data Source  | Mocked Tire SKUs (JSON)          |

---

## 🚀 Getting Started (Demo Instructions)

### 🖥️ Backend – NopCommerce Plugin

1. Clone the latest [NopCommerce](https://github.com/nopSolutions/nopCommerce)
2. Install locally with SQL Server
3. Add `TireCatalog.API` plugin:
   - Route: `/api/tireproducts`
   - Returns a list of tire SKUs with pricing, fitment & stock

4. Enable plugin via Nop Admin Panel

---

### 🌐 Frontend – Angular UI

```bash
cd Frontend/tire-ui
npm install
ng serve
```

Runs at: `http://localhost:4200`

---

## 📦 Sample API Response

```json
{
  "name": "Pirelli Scorpion Verde A/S",
  "price": "$650.81",
  "fits": "2024 Acura RDX Base",
  "inStock": true,
  "image": "pirelli.jpg"
}
```

---

## 📁 Suggested Folder Structure

```
TireCatalog-Demo-NopCommerce-Angular/
├── README.md
├── LICENSE
├── Frontend/
│   └── tire-ui/
│       └── src/app/tire-list/
│           ├── tire-list.component.ts
│           ├── tire-list.component.html
├── Backend/
│   └── TireCatalog.API.Plugin/
│       ├── Controllers/
│       └── Models/
├── screenshots/
│   ├── autoplicity-banner.png
│   ├── autoplicity-grid.png
│   └── autoplicity-detail.png
```

---

## 🧪 Related Demo Repo (Coming Soon)

[→ Tire Catalog Angular + .NET API Demo](https://github.com/asifhameed8/TireCatalog-Demo)

---

## 💬 Work With Me

Looking to build a **custom eCommerce platform**, **automotive auction system**, or **high-performance NopCommerce marketplace**?

I help businesses scale with clean architecture, modern UI, and full-stack systems built to convert.

📬 [Let’s talk on Upwork](https://www.upwork.com/freelancers/asifhameed)  
🌐 [Visit my portfolio](https://asifhameed.com)

