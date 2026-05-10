Netflix (NFLX) Three-Statement Financial Model

Technical Lead: Vincent Ta

Project Overview
This project involved the construction of a dynamic three-year historical financial model for Netflix, Inc. (NASDAQ: NFLX). The model integrates data extracted from SEC 10-K filings to build a cohesive link between the Income Statement, Balance Sheet, and Statement of Cash Flows, ensuring 100% data integrity across all schedules.

Model Architecture
The model is built with a structured "detective" approach to reconcile GAAP financial statements:
Three-Year Historical Income Statement (2023-2025): Tracks revenue growth from $33.7B to $45.1B and net income expansion from $5.4B to $10.9B.
Two-Year Consolidated Balance Sheet (2024-2025): Monitors asset and liability management, specifically focusing on content asset capitalization and debt obligations.
Three-Year Cash Flow Reconciliation (2023-2025): Bridges the gap between Net Income and Free Cash Flow, specifically reconciling content asset amortization ($16.4B in 2025) and additions ($17.1B in 2025).

Key Findings
Operational Leverage: While revenues grew by approximately 34% over the three-year period. Net Income more than doubled, illustrating high operating leverage.
Content Asset Management: Identified that Netflix successfully scaled its content investment from $12.5B in 2023 to $17.1B in 2025 while maintaining a positive net cash position.
Asset Efficiency: Total assets grew from $53.6B in 2024 to $55.6B in 2025, driven primarily by non-current asset increases and reinvested capital.

Technical Documentation & Files
The core of this project is contained within a single, multi-tabbed Excel workbook. The CSV files included in this repository serve as static previews for web-based viewing.
Three-Statement Model.xlsx: This is the master file. It contains the fully dynamic model with cross-linked formulas between the three primary financial schedules:
  Tab 1 - Income Statement Tab: 3-year historical performance analysis.
  Tab 2 - Balance Sheet Tab: Consolidated assets, liabilities, and equity.
  Tab 3 - Cash Flow Tab: Reconciliation of Net Income to Free Cash Flow (FCF).

Technical Skills Demonstrated
Financial Modeling: Linking three-statement models and FCF reconciliation.
Data Extraction: Mining SEC filings for historical hardcodes and financial disclosures.
Integrity Testing: Implementing balance checks and error-handling logic for accounting precision.
