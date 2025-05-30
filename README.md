# Headless Multi-Brand Storefront – SAP Commerce Edition

## 🧾 Project Overview
This project showcases a headless multi-brand storefront built using **SAP Commerce Cloud** and **Spartacus**. It features two lifestyle brands:
- **UrbanEdge** – Streetwear fashion
- **ZenNest** – Home & wellness products

The storefront demonstrates MACH principles: **Microservices**, **API-first**, **Cloud-native**, and **Headless**.

---

## ✨ Features
- 🛍️ Multi-brand catalog with brand-specific theming
- 🛒 Shared cart and checkout across brands
- 🧠 CMS-driven content using Contentful or SAP CMS
- 🌐 Responsive design for mobile and desktop
- 🔐 Optional JWT-based authentication

---

## 🧰 Tech Stack

| Layer       | Technology              |
|-------------|--------------------------|
| Frontend    | Spartacus (Angular)      |
| Backend     | SAP Commerce Cloud       |
| CMS         | Contentful / SAP CMS     |
| DevOps      | Docker, GitHub Actions   |
| Infra       | Kubernetes (optional)    |

---

## 🏗️ Architecture
[Frontend (Spartacus)] <--> [SAP Commerce APIs] <--> [CMS (Contentful/SAP CMS)]
---

## 🚀 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/MACHsmith/multibrand-storefront-sap.git
   cd multibrand-storefront-sap
   
2. **Install dependencies**
   npm install

3. **Run the frontend**
   npm start

4. **Connect to SAP Commerce backend**
   - Configure API endpoints in environment.ts
   - Ensure CORS is enabled on the backend
     
6. **CMS Integration**
   - Add Contentful API keys or SAP CMS credentials
   - Sync content models and content types

## 📄 License
MIT License
   
