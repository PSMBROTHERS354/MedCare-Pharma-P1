# 💊 MedCare Pharma — P1: Demand Sensing & Replenishment Planning

> **An explainable supply-chain decision-support system for demand sensing, forecasting, inventory risk analysis, and intelligent replenishment planning.**

MedCare Pharma P1 is a decision-support platform designed for the **Demand Planning & Replenishment** use case.

The system continuously analyzes demand, forecasts future requirements, evaluates inventory and stockout risk, considers expiry and FEFO constraints, searches the distribution network for transferable inventory, and generates explainable replenishment decisions.

---

## 🚀 Live Demo 

### 🌐 Frontend Application

**Live Application:**  
https://medcare-pharma-p1.onrender.com/

Open the application directly in your browser:

👉 **https://medcare-pharma-p1.onrender.com/**

The frontend is deployed as a **React + Vite Static Site on Render**.

---

### ⚡ Backend API

**Live API:**  
https://medcare-pharma-p1-api.onrender.com

👉 **https://medcare-pharma-p1-api.onrender.com**

The backend is deployed as a **FastAPI Web Service on Render**.

---

### 📚 Interactive API Documentation

Swagger UI:

👉 **https://medcare-pharma-p1-api.onrender.com/docs**

The API documentation provides interactive access to the available backend endpoints.

---

## 🎯 Project Overview

During seasonal demand fluctuations such as a flu-season surge, critical pharmaceutical SKUs can become unavailable in Tier-2 distribution centers while other distribution centers may simultaneously hold excess or near-expiry inventory.

MedCare Pharma addresses this problem by combining:

- Demand sensing
- Demand forecasting
- Inventory monitoring
- Dynamic reorder point calculation
- Safety-stock analysis
- Stockout-risk detection
- Expiry-risk analysis
- FEFO-aware inventory handling
- Distribution-center network analysis
- Inventory transfer feasibility
- Replenishment planning
- Priority management
- Cost-of-inaction analysis
- Explainable decision recommendations

The system produces actionable decisions such as:

```text
TRANSFER
REPLENISH
MONITOR
