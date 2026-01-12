# Corporate Profitability Analysis and Projection

## Project Overview
This project analyzes financial data from publicly listed companies on the New York Stock Exchange (NYSE) to identify highly profitable firms and generate three-year profit projections. Using historical profit levels and growth trends, the analysis produces optimistic, pessimistic, and average scenarios to support high-level investment insights.

Unlike machine learning–based projects, this analysis focuses on **financial reasoning, trend analysis, and scenario modeling**, reflecting real-world corporate finance decision-making.

---

## Problem Statement
The objective of this project is to:
- Identify the most profitable companies based on historical average profit
- Evaluate profit growth trends over time
- Generate three-year forward projections under optimistic, pessimistic, and average assumptions
- Compare companies based on both expected returns and downside risk

The goal is to determine which firms may be most attractive to investors under different risk preferences.

---

## Dataset
- **Source:** Kaggle  
- **Coverage:** Publicly listed NYSE companies  
- **Key Variables:**  
  - Company identifier  
  - Historical profit figures  
  - Growth rates and trend indicators  

The dataset provides firm-level financial metrics suitable for exploratory and projection-based analysis rather than predictive modeling.

---

## Methodology
1. **Exploratory Data Analysis (EDA)**  
   - Inspected profit distributions and trends across firms  
   - Identified top performers based on average profitability  

2. **Growth Trend Analysis**  
   - Calculated historical growth rates for each company  
   - Used these trends as the basis for forward projections  

3. **Profit Projections**  
   - Generated three-year projections under:
     - **Optimistic (maximum growth)**
     - **Average (mean growth)**
     - **Pessimistic (minimum growth)** scenarios  

4. **Comparative Evaluation**  
   - Ranked companies based on projected returns  
   - Assessed tradeoffs between upside potential and downside risk  

---

## Key Findings
- Companies such as **Verizon (VZ)**, **Bank of America (BAC)**, and **AT&T (T)** show strong upside potential under optimistic and average growth assumptions.
- Verizon exhibits the highest potential returns under optimistic scenarios.
- **Wells Fargo (WFC)** demonstrates relatively lower downside risk, making it a more conservative investment option.
- Firms with the highest upside are not always those with the lowest risk, highlighting the importance of scenario-based analysis.

---

## Limitations
- Projections are based solely on historical profit trends and do not incorporate:
  - Macroeconomic conditions
  - Interest rates
  - Industry-specific shocks
  - Firm-level strategic changes
- This analysis should be interpreted as **illustrative**, not as financial advice.
- Results are sensitive to historical volatility and limited data scope.

---

## Conclusion
This project demonstrates how historical financial data can be used to generate meaningful profit projections and comparative investment insights without relying on machine learning models. By combining profitability levels with growth trends, the analysis highlights tradeoffs between risk and return and provides a structured framework for evaluating investment opportunities.

---

## Tools Used
- Python  
- pandas  
- NumPy  
- Jupyter Notebook  

---

## How to Run
pip install -r requirements.txt

