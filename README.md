# E-Commerce Revenue and Funnel Optimization Analysis

## Project Objective
Analyze an e-commerce dataset to understand revenue drivers, order funnel drop-offs, and customer retention, and to provide data-driven business recommendations.

## Dataset Source
This project uses the Brazilian E-Commerce Public Dataset (Olist) available on Kaggle.
The dataset contains real-world e-commerce orders, customers, payments, products, sellers, and delivery information.

## Tables Used
- orders: order-level information and order status
- order_items: product-level details for each order
- payments: payment type and payment value
- products: product metadata and category
- customers: customer identifiers and location

## Business Assumptions
- Revenue is calculated as product price plus freight value.
- Funnel analysis is order-based, not user-based.
- Orders with status 'canceled' or 'unavailable' are treated as revenue leakage.
- All monetary values are assumed to be in Brazilian Real (BRL).

## Project Structure
- Phase 0: Dataset Understanding & Assumptions
- Phase 1: Database Foundation & Data Audit
- Phase 2: Revenue Performance & Product Insights
- Phase 3: Funnel Optimization Analysis
- Phase 4: Customer Behavior & Retention
- Phase 5: Business Impact & Recommendations

## Tools Used
- SQL (MySQL)
- GitHub

## Status
Project in progress
