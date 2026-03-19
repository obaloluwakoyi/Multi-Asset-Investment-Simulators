

# Financial Analytics & Investment Simulators

A collection of lightweight, client-side financial simulation dashboards designed to evaluate real estate acquisitions, hospitality yields, and equity portfolios. 

These tools leverage raw HTML, CSS, and JavaScript to provide instant pro-forma analysis, dynamic charting, and automated PDF investment memo generation.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Data Visualization:** Chart.js
* **Document Generation:** html2pdf.js

## 📊 Included Tools

### 1. Realty Analytics Pro (`real_estate_proforma.html`)
An investment-grade property evaluator for long-term real estate holdings.
* Assesses Cap Rate, Cash-on-Cash return, and Net Operating Income (NOI).
* Models 10-year equity growth against debt amortization.
* Exports detailed Pro-Forma Investment Memos.

### 2. Short-Let ROI Terminal (`short_let_simulator.html`)
A hospitality yield simulator tailored for short-term rental economics.
* Calculates occupancy-adjusted gross revenue and break-even nights.
* Factors in furnishing capital, maintenance, and cleaning operational expenditures.
* Tracks cumulative wealth and rental revenue growth.

### 3. NGX Super-Agent Terminal (`ngx_portfolio_builder.html`)
A multi-asset portfolio builder pre-configured for NGX (Nigerian Stock Exchange) equities and select US tech stocks.
* Automates volume allocation based on total capital input.
* Projects 5-year capital growth and annual dividend liquidity.
* Features a "Quick-Pick" algorithmic allocation for top-performing assets.

### 4. Executive KPI Dashboard (`executive_kpi_dashboard.html`)
A specialized reporting dashboard built on the portfolio engine.
* Optimized specifically for clean, print-ready PDF generation.
* Formats complex financial projections into confidential, stakeholder-ready executive summaries.

 ### 5 Quantum-Alpha: Risk & Optimization Engine ( Quantum_Investment_Consultant.ipynb)
 An advanced research framework that utilizes Quantum Computing to solve the "Asset Allocation" problem.
 *Quantum Solver: Uses QAOA to identify the efficient frontier and optimal asset weights.
 *Risk Engine: Executes 10,000+ Monte Carlo simulations to forecast Value-at-Risk (VaR) and price trajectories.
 *Automated ETL: Dynamically fetches global equity and crypto data via yfinance.
*Output: Generates a standalone Quantum_Alpha_Dashboard.html with asset correlation heatmaps and optimized weights.

## 🚀 Usage
🚀 Usage & Deployment
For the Quantum Engine (Python):
Prerequisites: Python 3.10+ and an IBM Quantum API Key.

Installation: ```bash
pip install qiskit qiskit-ibm-runtime yfinance riskfolio-lib plotly pandas

Run: Execute the .ipynb notebook to perform optimization and generate the latest performance dashboard.

For the Interactive Dashboards (HTML):
No Server Required: These tools are built with a Zero-Server Architecture.

Execution: Simply open any .html file in a modern web browser (Chrome, Safari, Edge).

Exporting: Use the integrated "Export to PDF" buttons within the UI to generate professional investment memos for offline review.

📂 Project Structure
Plaintext

├── Quantum_Investment_Consultant.ipynb   # Quantum Optimization Logic
├── ngx_portfolio_builder.html            # Equity Allocation Terminal
├── executive_kpi_dashboard.html          # Professional Reporting UI
├── real_estate_proforma.html             # Long-term Property Modeler
└── short_let_simulator.html              # Hospitality Yield Terminal


Quantum Consutant/Dashboard/Quantum_Alpha_Dashboard.html
