# AI-Powered GTM Funnel Intelligence System

## 📊 Dashboard Preview

<img width="1000" height="900" alt="Screenshot 2026-04-25 232859" src="https://github.com/user-attachments/assets/e2e5cb44-0955-4e0c-870f-da888340fd04" />

*Executive view of pipeline performance, conversion funnel, and revenue drivers.*

This project simulates a Revenue Operations / GTM analytics system for a SaaS-style business.

## Goal
Analyze the full GTM funnel from lead → MQL → SQL → opportunity → revenue, and identify performance gaps, pipeline risk, and revenue drivers.

## Project Stack
- Python: synthetic data generation and AI/risk scoring
- SQL: CRM-style relational tables and RevOps metrics
- Power BI: dashboards and executive reporting
- Optional: automation using Python, Make, or Zapier

## Key Insights
- High-risk pipeline dominates total value (~70%+), indicating potential revenue volatility
- Organic Search generates the highest revenue with strong win rate
- Several deals remain idle >120 days, signaling pipeline stagnation
- Conversion drop-off is most significant between MQL → SQL
- 
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
