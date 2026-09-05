\# Procurement \& Supply Chain Performance Intelligence



AI-powered performance improvement system built with n8n to identify procurement, inventory and supplier opportunities, quantify financial exposure, and translate operational findings into actionable management decisions.



\## Business Problem



Procurement and supply chain teams often have operational data but lack a continuous way to identify improvement opportunities, quantify their financial impact, and prioritize actions.



This project demonstrates a data-driven approach to connecting operational performance with financial impact.



\## What It Does



\- Analyzes procurement price variance and annualized cost exposure

\- Identifies excess inventory and working-capital tied up in inventory

\- Evaluates supplier performance and operational risk

\- Quantifies improvement opportunities using deterministic analytics

\- Prioritizes opportunities based on financial exposure and operational significance

\- Uses Claude AI to interpret validated analytical findings and generate management recommendations

\- Delivers management alerts and supports action tracking through Telegram



\## Solution Flow



Operational Data → Data Validation → Analytics → Opportunity Engine → AI Interpretation → Management Action



\## Key Analytics



\### Procurement

\- Price variance by supplier and SKU

\- Annualized cost exposure

\- Identification of procurement cost-reduction opportunities



\### Inventory

\- Inventory days vs. target inventory days

\- Excess inventory quantity

\- Excess inventory value

\- Working-capital exposure



\### Supplier Performance

\- On-time delivery

\- Defect rate

\- Lead-time variability

\- Supplier risk scoring

\- Spend exposure



\## Key Output



The system converts operational data into a prioritized opportunity list containing quantified financial exposure, supporting evidence, and recommended next steps.



Example opportunities include excess inventory, procurement price variance, and supplier performance risks.



Financial exposure represents identified improvement opportunity or risk exposure, not realized savings.



\## AI Role



AI is used as an interpretation layer rather than the calculation engine.



Deterministic analytics calculate the underlying metrics and financial exposure. Claude AI receives the structured analytical results and converts them into concise management recommendations.



This helps keep the financial calculations traceable and prevents the AI layer from inventing analytical results.



\## Technology



\- n8n

\- JavaScript

\- Claude API

\- Telegram Bot API



\## Data



The demonstration uses a simulated automotive-component manufacturer with synthetic procurement, inventory and supplier data.



No real company, supplier, customer, or financial data is used.



\## Architecture



```text

Synthetic Operational Data

&#x20;         ↓

&#x20;   Data Validation

&#x20;         ↓

&#x20;      Analytics

&#x20;         ↓

&#x20; Opportunity Engine

&#x20;         ↓

&#x20;   Claude AI Layer

&#x20;         ↓

&#x20;Management Recommendations

&#x20;         ↓

&#x20;Telegram Alerts \& Actions



