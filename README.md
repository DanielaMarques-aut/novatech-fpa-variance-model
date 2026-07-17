NovaTech Consulting — FP&A Financial Model (2022–2025)
A complete FP&A portfolio project demonstrating variance analysis, YoY revenue bridge, business drivers, forecasting engine, scenario modeling, and executive‑level storytelling.

📊 Overview
Este repositório contém um modelo FP&A completo para uma consultora fictícia (NovaTech Consulting Lda.), cobrindo:

Dados históricos mensais (2022–2024)

Budget 2025

YoY Revenue Bridge (2022→2023 e 2023→2024)

Drivers de negócio (HC, Billing Rate, MS, Cost per Head)

Variance Analysis (Actual 2024 vs Budget 2025)

Forecast Engine (Flat, Trend, Manual)

Forecast vs Budget 2025

Scenario Analysis (Base, Upside, Downside)

Sensitivity Tables (HC, Rate, Utilização)

Narrativa FP&A e CFO Summary

Este projeto funciona como um case study FP&A completo, ideal para portfolio profissional.

🧩 Repository Structure
Código
novatech-fpa-variance-model/
│
├── RawData/
│   └── RawData.xlsx
│
├── Analysis/
│   ├── YoY_Bridge.xlsx
│   ├── Drivers.xlsx
│   ├── Variance_Model.xlsx
│   └── Forecast_2025.xlsx
    └── Powerbi analysis


│
├── Docs/
│   ├── CFO_Summary.pdf
│   └── Full_FP&A_Narrative.pdf
│
└── README.md
📈 Key Analytical Components
1. RawData (2022–2024 + Budget 2025)
Inclui:

Revenue (Consulting + MS)

Costs (Personnel, Operations, Other)

Budget 2025 por linha

Sazonalidade realista

Ajustes de rounding em Dezembro

2. YoY Revenue Bridge (Atualizado)
2022 → 2023
Volume: +€240,000

Rate: +€169,200

Mix: €0

Actual: €2,509,200

Bridge: €2,400,000

Gap: €−109,200

2023 → 2024
Volume: +€258,000

Rate: +€187,200

Mix: €0

Actual: €2,650,000

Bridge: €2,845,200

Gap: €−195,800

Conclusão:  
Crescimento explicado por mais FTEs + maior rate, MS estável.

3. Business Drivers (Atualizado)
Headcount: 42 → 47 → 52 → 55 (2025)

Billing Rate: €4,000 → €4,300 → €4,600 → €4,900 (2025)

Managed Services: €420k → €480k → €530k → €580k (budget 2025, +9.4%)

Cost Structure:

Personnel: 65%

Operations: 8%

Other: 4%

Drivers alimentam todo o modelo (P&L, Forecast, Cenários).

4. Variance Analysis — Actual 2024 vs Budget 2025
Revenue: -8.6%

Costs: -8.6%

EBITDA: abaixo do budget

Margem: comprimida por falta de volume

Insight:  
A empresa foi eficiente, mas operou com volume insuficiente.

5. Forecast Engine (Flat, Trend, Manual)
Flat: média de Oct–Dec 2024

Trend: regressão linear

Manual: HC × Rate × Utilização

Todos alimentam automaticamente o P&L 2025.

6. Forecast 2025 vs Budget 2025 (Atualizado)
Revenue
Forecast acima do budget por €383K

Driver: utilização mais realista (82% vs 71.7% no budget)

Personnel
Forecast abaixo do budget por €63K

Driver: custo/head real (€2,760) < custo/head budget (€2,856)

Operations & Other
Forecast acima do budget por €46K

Driver: revenue mais alto → custos variáveis mais altos

Total Costs
Forecast abaixo do budget por €87K

Driver: poupança em Personnel > aumento em Ops+Other

EBITDA
Forecast acima do budget por €400K

Driver: operating leverage + utilização mais alta

EBITDA Margin
Forecast margin > budget margin

Driver: Personnel semi-fixo → cada ponto de utilização cai quase todo em EBITDA

7. Scenario Analysis (Base, Upside, Downside)
Scenario	HC	Rate	Utilização	Insight
Base	55	€4,900	82%	Continuação da tendência
Upside	60	€5,000	86%	Crescimento agressivo
Downside	50	€4,700	78%	Pressão comercial


8. Sensitivity Tables
Três tabelas:

EBITDA vs Headcount

EBITDA vs Billing Rate

EBITDA vs Utilização

Confirma que EBITDA é mais sensível a HC e Utilização do que ao Rate.

🧠 Key Insights
Crescimento histórico explicado por HC + Rate

MS é estável, mas Budget 2025 assume +9.4%

Custos proporcionais ao revenue

Variância negativa do Budget 2025 é volume-driven

Forecast 2025 depende fortemente da utilização

Cenários e sensitivities suportam decisões estratégicas

📄 Included Documents
CFO Summary (PDF)
Resumo executivo com principais drivers e implicações.
Full FP&A Narrative (PDF)
Análise completa: RawData, YoY Bridge, Drivers, Variance, P&L, Forecast, Cenários.
Powerbi dashboard: KPI cards, Budget vs Actual, Revenue trend

# NovaTech FP&A Model

Financial planning & analysis practice model built on a fictional 
IT consultancy (NovaTech Consulting Lda., Lisboa).

## What's included
- Excel model: P&L, Variance Analysis, Drivers, Forecast (3 methods, 
  3 scenarios, sensitivity tables), YoY Bridge
- Power BI dashboard: KPI cards, Budget vs Actual, Revenue trend

## Tools
Excel | Power BI | DAX | Python (data generation)

## Dataset
Fictional — NovaTech Consulting Lda., ~52 FTEs, €2.65M revenue (2024)

👩‍💼 About the Author
Daniela Marques  
FP&A Analyst | Financial Modelling | Business Performance | Data‑Driven Storytelling