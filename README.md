## 🛍️ RetailMart SQL Analytics Dashboard

### 🎯 Project Summary

RetailMart SQL Analytics Dashboard is an **end-to-end, enterprise-grade analytics platform** designed to transform raw retail transactional data into **actionable business intelligence**. Built as a capstone project for the **AccioJob SQL Bootcamp**, the solution mirrors real-world analytics systems used by large-scale organizations like **Amazon, Flipkart, and Swiggy**.

The platform follows **production-ready data engineering principles**, including schema isolation, configuration-driven logic, data quality governance, performance tuning, automated refresh pipelines, and a fully decoupled dashboard consumption layer.

---

## 🚀 Core Capabilities

* **25+ Business Analytics Views** covering Sales, Customers, Products, Stores, Operations, and Marketing
* **10 Materialized Views** to deliver high-performance, low-latency KPI access
* **32 JSON Export Functions** for API-ready and frontend-friendly data delivery
* **Multi-Tab Interactive Dashboard** built on pre-exported analytics datasets
* **Automated Business Alerts** to proactively detect risks and anomalies
* **Scheduled Refresh & Export Pipeline** with detailed logging and auditability

---

## 🏗️ Architecture Overview

The project is structured as a **layered analytics platform**, closely resembling enterprise data architectures:

### 1️⃣ Analytics Foundation

* Dedicated analytics schema to isolate reporting workloads
* Centralized configuration tables for thresholds, segmentation rules, and KPIs
* Metadata, refresh history, execution logs, and data quality tracking
* Performance-optimized indexing strategy aligned with real query patterns

### 2️⃣ Data Quality & Governance

* Automated validation across **completeness, accuracy, consistency, timeliness, and uniqueness**
* Centralized reporting view for overall data health
* Logged quality issues to prevent unreliable data from reaching dashboards

### 3️⃣ KPI & Business Intelligence Layer

* Domain-specific SQL modules for:

  * **Sales** (growth trends, payment behavior, executive KPIs)
  * **Customers** (CLV, RFM segmentation, churn risk, cohort retention)
  * **Products** (ABC analysis, inventory health, category & brand performance)
  * **Stores** (profitability, efficiency, regional benchmarks)
  * **Operations** (delivery SLA, returns, courier performance)
  * **Marketing** (campaign ROI, channel efficiency, promotions, email engagement)
* Heavy use of **CTEs, window functions, and time-series analysis**
* JSON-based output functions for downstream consumption

### 4️⃣ Alerting & Monitoring

Rule-based alerts to proactively flag:

* Low inventory for high-impact products
* Churn risk among high-value customers
* Revenue anomalies and sudden drops
* Shipment delays and SLA breaches
* Elevated return rates
* Over-dependence on a single payment method

### 5️⃣ Automation & Refresh Engine

* Centralized orchestration for refreshing materialized views
* Support for concurrent refreshes to avoid read blocking
* Execution metrics, failure tracking, and refresh history logging
* Automated JSON exports for dashboards and APIs

### 6️⃣ Dashboard & Visualization

* Lightweight frontend consuming **pre-generated JSON files**
* Fully decoupled from the database layer
* Multi-tab, responsive UI optimized for desktop and mobile
* Client-side caching and graceful error handling
* Built using **HTML, CSS, JavaScript, and Chart.js**

---

## ⚙️ End-to-End Workflow

1. Source data is validated through automated data quality checks
2. Analytics views and materialized views are refreshed in dependency order
3. KPIs are exported as structured JSON datasets
4. Dashboard consumes JSON data and renders interactive insights
5. Alerts surface critical business risks in near real time

---

## 📈 Performance & Optimization

* 50+ targeted indexes on high-frequency columns
* Pre-aggregated materialized views for heavy computations
* Composite indexing for common join and filter paths
* Planner-optimized execution using `ANALYZE` statistics

---

## 🎓 Key Skills Demonstrated

* Advanced SQL (CTEs, window functions, analytical queries)
* Query performance optimization at scale
* Enterprise-style schema and metadata design
* Data quality enforcement and governance
* Automated analytics pipelines and refresh orchestration
* JSON-based data serving for dashboards and APIs
* Frontend visualization integration

---


