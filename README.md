# Automotive Vehicle Service & Warranty Analytics

## 📌 Project Overview

The **Automotive Vehicle Service & Warranty Analytics** project is a data engineering and analytics solution designed to analyze vehicle service and warranty data.

The project uses the **Medallion Architecture** to transform raw automotive data into clean, reliable, and analytics-ready datasets. The final data is used to build an interactive dashboard for monitoring service and warranty performance.

---

## 🎯 Objectives

- Analyze vehicle service and warranty data
- Clean and transform raw data
- Build a structured data pipeline using Medallion Architecture
- Generate meaningful business insights
- Analyze service costs and warranty claims
- Identify service and warranty trends
- Create an interactive analytics dashboard

---

## 🏗️ Architecture

The project follows the **Medallion Architecture**:

```text
Raw Data
   │
   ▼
┌─────────────────┐
│  Bronze Layer   │
│  Raw Data       │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Silver Layer   │
│ Cleaned Data    │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Golden Layer   │
│ Analytics Data  │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│   Dashboard     │
│ Service &       │
│ Warranty        │
│ Analytics       │
└─────────────────┘
