# snowflake-sales-insights
Beginner-level Snowflake project using sales data with masking and RBAC

# 📊 Snowflake Sales Insights Project

This is a beginner-friendly, end-to-end mini project built on **Snowflake** that demonstrates secure, scalable, and analytics-ready data pipelines for a sales organization. Designed to showcase **real Snowflake features**, it's ideal for portfolio, resumes, and interview prep.

---

## 🎯 Project Objectives

- Load product, sales, customer, and region data
- Build analytical queries to summarize revenue
- Use **RBAC (Role-Based Access Control)** and **Masking Policies**
- Deliver secure views for downstream dashboards

---

## 🧱 Schema Overview

| Table | Description |
|-------|-------------|
| `products` | Product master data |
| `customers` | Customer info with **masked emails** |
| `sales` | Daily sales records |
| `regions` | Region and zone mappings |
| `sales_summary_view` | Aggregated revenue by product and region |

---

## 🛠️ Technologies & Concepts

- ✅ Snowflake SQL
- ✅ Data Masking Policies
- ✅ Views for Dashboards
- ✅ Role-Based Access Control (RBAC)
- ✅ Test Data & Ingestion Scripts

--
