# 🔥 SmartStock Manager (Firebase Edition)

<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Firebase-Realtime_DB-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Architecture-BaaS_/_Modular-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Stable_v1.0-success?style=for-the-badge" />
</p>

## 📝 Overview
This is a **Full-Stack Inventory Management System** built to handle high-velocity warehouse operations. Moving beyond static prototyping, this version leverages **Firebase Realtime Database** to provide instantaneous data synchronization across all connected clients.

The system was engineered to solve high-volume stock tracking challenges, providing a robust interface for managing thousands of motorcycle spare parts with sub-second latency and precise inventory accuracy.

---

## 🛠️ Technical Stack
*   **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3.
*   **Database (BaaS):** Firebase Realtime Database for live persistence.
*   **Architecture:** Modular ES6 Scripting for maintainable and scalable code logic.
*   **Deployment:** Optimized for rapid cloud integration.

---

## 🚀 Key Features

*   **⚡ Live CRUD Operations:** Fully reactive Create, Read, Update, and Delete modules for Items, Categories, and Stock levels.
*   **📍 Precision Location Tracking:** Detailed inventory mapping down to specific **Racks (Rak)**, **Rows (Baris)**, and **Box Numbers (Nomor Kotak)**.
*   **🔄 Operational Workflows:** Integrated business logic for **"Pindah"** (Relocation) and **"Ambil"** (Picking), mirroring real-world warehouse movements.
*   **🔍 Dynamic Data Filtering:** Real-time search indexing and category filtering to minimize cognitive load during peak operational hours.

---

## 📈 Engineering Roadmap
This repository represents the **"Live Data Synchronization"** milestone in the system's evolution:
1.  **Inventory Concept:** UI/UX research and static prototyping.
2.  **SmartStock Manager (Current):** Cloud integration and full-stack logic implementation.
3.  **Desk ERP Ecosystem:** Migration to React/Next.js and Supabase for enterprise-scale requirements.

---

## 📸 System Preview

<div align="center">
  <table border="0">
    <tr>
      <td align="center"><img src="assets/main_menu.png" width="380" alt="Main Menu"/><br/><sub><b>Real-time Management Dashboard</b></sub></td>
      <td align="center"><img src="assets/categories.png" width="380" alt="Categories"/><br/><sub><b>Dynamic Category Management</b></sub></td>
    </tr>
    <tr>
      <td align="center"><img src="assets/products.png" width="380" alt="Products"/><br/><sub><b>Comprehensive Product List</b></sub></td>
      <td align="center"><img src="assets/stocks.png" width="380" alt="Stocks"/><br/><sub><b>Live Stock Monitoring</b></sub></td>
    </tr>
  </table>
</div>

---

## ⚠️ Security & Local Setup
> [!IMPORTANT]
> **Industrial Best Practices:** To maintain security, sensitive API configurations have been excluded from this repository.
> 
> **To run this project locally:**
> 1. Rename `firebase-config.example.js` to `firebase-config.js`.
> 2. Insert your own Firebase project credentials.
> 3. Serve the directory using a local server (e.g., VS Code Live Server).
