# AI-Powered GTM Funnel Intelligence System

This project simulates a Revenue Operations / GTM analytics system for a SaaS-style business.

## Goal
Track the full lead lifecycle from marketing lead → MQL → SQL → opportunity → closed revenue, then surface funnel performance, pipeline risk, and recommended sales actions.

## Project Stack
- Python: synthetic data generation and AI/risk scoring
- SQL: CRM-style relational tables and RevOps metrics
- Power BI: dashboards and executive reporting
- Optional: automation using Python, Make, or Zapier

## Folder Structure
- data/: generated CSV files
- sql/: database schema and metric queries
- python/: data generation and scoring scripts
- powerbi/: Power BI dashboard file
- docs/: notes, dashboard screenshots, and project documentation

## Build Order
1. Generate synthetic GTM/CRM data
2. Load CSVs into PostgreSQL, MySQL, SQLite, or Power BI directly
3. Write SQL metrics for funnel, pipeline, CAC, and risk
4. Build Power BI dashboard
5. Add lead scoring and deal risk scoring
6. Document project and add resume bullets
