# Logistics & Service Point Optimization – Maastricht 📦

This project aims to optimize the service point network for a package delivery company (Post&L) in Maastricht, NL. Through machine learning, routing algorithms, and cost optimization, the team proposed a solution reducing operational costs by 78%.

---

## 🔍 Problem Statement

The city has 35 existing service points, leading to high operating and routing costs. The goal: reduce the number and optimize their location while maintaining service efficiency.

---

## 🧠 Methodology

- **Exploratory Data Analysis (EDA):**
  - Demographics, deliveries, pickups, heatmaps
- **Routing Optimization:**
  - Dijkstra’s algorithm to map customer to service points
- **Feature Engineering:**
  - Distance to service point, income, age, workday flags
- **Machine Learning Models:**
  - 🔁 Random Forest (R² ≈ 0.78)
  - ⚡ XGBoost (R² ≈ 0.82)
- **Optimization Algorithm:**
  - Simulated Annealing to determine ideal service point configuration

---

## 💼 My Role

> While not the main Python coder, I took ownership of:
> - Leading the **analytical interpretation** of ML model results
> - **Debugging and fixing critical Python logic** in the simulated annealing algorithm
> - **Validating feature engineering logic**
> - Acting as **bridge between coders and domain logic**, ensuring the methodology made business sense
> - Drafting **data-driven recommendations** and helping steer the final narrative

---

## 📊 Key Results

- Reduced projected cost from **€3.2M → €672K**
- Proposed 7 optimized service point locations
- Identified major cost centers and overburdened locations

---

## ⚙️ Technologies Used

- Python, XGBoost
- Simulated Annealing (custom)
- Dijkstra’s Algorithm
- Data cleaning & preprocessing

--
