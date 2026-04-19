# SAP PP – Production Order Management

**Student:** Isha Roy
**Roll No:** 23051109
**Module:** SAP Production Planning (SAP PP)
**Document Type:** Academic Project Report

---

## 📌 Project Overview

This project is a practical field study on the **SAP Production Planning (SAP PP)** module, focusing on the end-to-end lifecycle of Production Order management. It covers everything from order creation and release to confirmation and technical closure.

---



## 🔄 Production Order Lifecycle Covered

| Phase | Transaction | Description |
|-------|------------|-------------|
| Create Order | CO01 | Manually create a Production Order with BOM & Routing |
| Convert Planned Order | MD16 | Batch-convert MRP Planned Orders to Production Orders |
| Modify Order | CO02 | Update quantity, dates, or master data |
| Confirm Order | CO15 | Trigger Goods Issue (261) & Goods Receipt (101) |
| Close Order | TECO | Apply Technical Completion to freeze the order |

---

## 🖥️ Frontend

The `frontend/` folder contains an interactive HTML dashboard simulating the SAP PP Production Order Management interface. It includes:

- Production Order lifecycle process flow
- Dashboard with order status overview
- Navigation for CO01, MD16, CO02, CO15, and TECO transactions
- Troubleshooting section and audit trail

To view it, simply open `sap_pp_frontend.html` in any web browser.

---

## 📄 Report

The `report/` folder contains the full 24-page academic project report covering:

- Introduction to SAP PP and Production Orders
- Core concepts: BOM, Routing, Backflushing, Movement Types
- Step-by-step transaction guides with SAP GUI screenshots
- Integration with SAP MM and SAP CO modules
- Common issues and troubleshooting guide

---

## 🔑 Key Concepts

- **BOM (Bill of Materials)** – Component list auto-populated into every Production Order
- **Routing** – Manufacturing operations sequence driving scheduling and costs
- **Movement Type 101** – Goods Receipt (finished goods into stock)
- **Movement Type 261** – Goods Issue (raw materials consumed from stock)
- **TECO** – Technical Completion; freezes orders and removes them from MRP

---

## 🛠️ Technologies & Tools

- SAP ERP – Production Planning (PP) Module
- SAP GUI Transactions: CO01, MD16, CO02, CO15, CO03
- HTML / CSS / JavaScript (Frontend Dashboard)

---

*Submitted as part of SAP PP Module – Academic Project*
