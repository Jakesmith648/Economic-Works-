### Here is an overview of the some econometrical and benchmarking studies and consultations. 

### The Impact of Minimum Wage Increases on Youth Employment: A Difference-in-Differences Econometric Analysis (U.S. States, 2010–2022)

Overview

This capstone research investigates whether increases in state-level minimum wages significantly affect youth employment rates (ages 16–24) across the United States. The study leverages real-world data and econometric modeling to assess if minimum wage policy changes lead to job displacement, job growth, or neutral outcomes for young workers—an issue central to contemporary labor market policy debates.

### Data and Sources

Youth Employment & Unemployment: Bureau of Labor Statistics (Local Area Unemployment Statistics)

Minimum Wage Levels: U.S. Department of Labor & Economic Policy Institute (EPI Minimum Wage Tracker)

State GDP, Education, and Industry Composition: Bureau of Economic Analysis (BEA) & American Community Survey (Census Bureau)

Panel Period: Approximately 10 years (pre- and post-policy implementation), covering multiple U.S. states

Econometric Framework

The analysis employs a Difference-in-Differences (DiD) approach combined with state and year fixed effects to estimate the causal effect of minimum wage increases on youth employment.

The core model specification:
YouthEmpRate_it = β₀ + β₁Treatment_i + β₂Post_t + β₃(Treatment_i × Post_t) + β₄X_it + μ_i + γ_t + ε_it  

**Where:**  
- **Treatment_i** = 1 if the state increased its minimum wage  
- **Post_t** = 1 for years after the policy was enacted  
- **Treatment_i × Post_t** = causal Difference-in-Differences (DiD) estimate  
- **X_it** = control variables (GDP per capita, education level, unemployment rate, industry mix)  
- **μ_i** = state fixed effects  
- **γ_t** = year fixed effects  

### Methodological Techniques

Difference-in-Differences (DiD): Estimates the causal impact of wage policy by comparing treated vs. control states before and after policy changes.

Fixed Effects (FE): Controls for unobserved, time-invariant state characteristics and macroeconomic shocks common to all states.

Robust Standard Errors (Clustered): Adjusts for within-state correlation across time.

Outlier & Influence Diagnostics: Cook’s Distance and heteroskedasticity tests applied; non-normal residuals addressed to improve robustness.

Model Validation: Parallel trends checked visually and statistically; placebo and subgroup tests proposed for internal validity.

### Key Findings

Baseline DiD (without fixed effects): No statistically significant difference between treatment and control groups initially; R² ≈ 0.18.

With Fixed Effects: Model fit improved to R² = 0.57, confirming strong explanatory power from state and time variation.

Post-Outlier Adjustment (Final Model):

A $1 increase in the minimum wage was associated with a +0.95 percentage point increase in youth employment (p = 0.001, statistically significant).

The DiD policy effect (the direct causal estimate) indicated a –1.0 percentage point change, not statistically significant (p = 0.176).

This suggests that while the specific policy change may not have caused a significant shift, higher wage levels correlate positively with youth employment overall.

Economic Controls: Unemployment rate remained the strongest negative predictor of youth employment (p < 0.001), aligning with standard labor theory.

Interpretation

These results challenge traditional neoclassical labor theory, which predicts that higher minimum wages reduce employment. Instead, they align more closely with modern monopsony and behavioral models, suggesting that modest wage increases may improve labor market participation via higher productivity, lower turnover, and stronger labor supply incentives.

The findings mirror those of Card & Krueger (1994, 1995) and contribute to ongoing debates in empirical labor economics by using quasi-experimental design and panel econometric methods grounded in Kennedy (2008) and Wooldridge (2013) frameworks.

Statistical and Econometric Tools

Python (statsmodels, pandas) | R | EViews | Excel | Jupyter Notebook
Techniques: OLS, Difference-in-Differences, Fixed Effects, Heteroskedasticity Correction, Outlier Diagnostics

### Policy Implications Found 

Policymakers: Evidence suggests moderate minimum wage increases do not harm youth employment and may improve participation rates in low-wage sectors.

Employers (Retail, Food Service): Wage adjustments can coincide with stable employment levels, countering automation fears.

Researchers: Demonstrates replicable design for labor policy evaluation using state panel data and robust econometric testing.

Econometric Competencies Demonstrated

Causal inference through Difference-in-Differences

Handling panel data with fixed and time effects

Testing for model robustness and validity

Interpreting conflicting empirical outcomes through theory

Translating econometric findings into policy-relevant insights

Outcome

This capstone project showcases the ability to conduct applied causal econometric analysis on real U.S. labor market data, providing evidence-based insights for both academic and policy audiences. It demonstrates technical proficiency in program evaluation econometrics, labor market modeling, and data-driven policy design.

### Starbucks Financial Performance Analysis 

Purpose:
This analysis evaluates Starbucks Corporation’s financial performance and adherence to GAAP reporting standards through detailed horizontal, vertical, and trend analyses.

Key Focus Areas:

Horizontal & Vertical Analysis: Compared Starbucks’ receivables, fixed assets, and debt financing between 2021–2022, identifying key asset growth trends and debt structure shifts.

Ratio Analysis: Computed liquidity (current, acid-test), solvency (debt-to-asset, debt-to-equity), and profitability (net margin, ROA) ratios. Benchmarked against Tim Hortons, McDonald’s, and the Consumer Discretionary sector.

Findings:

Liquidity ratios showed tightening cash flexibility (current ratio ↓ 0.43 pts).

Solvency revealed high debt leverage (95th percentile in industry).

Profitability remained resilient (ROA ≈ 13.3%, outperforming 94% of peers).

Regulatory Insight: Summarized Starbucks’ compliance with SEC rules and Sarbanes-Oxley Act internal control requirements, confirming robust financial governance.

Tools & Methods Used:
Excel | EViews | Python (for ratio automation) | GAAP & SEC standards

Outcome:
Delivered a comprehensive econometric-style financial evaluation integrating accounting, ratio benchmarking, and internal control analysis — a model replicable for firm-level forecasting and credit evaluation.

### U.S. Economic Impact and Policy Evaluation (Applied Economics Paper)


Purpose:
Assessed macroeconomic policy outcomes on employment, inflation, and GDP trends using econometric reasoning and real data from Federal Reserve and BEA sources.

Key Contributions:

Built regression-based analysis linking fiscal stimulus and labor market performance post-pandemic.

Conducted elasticity and multiplier effect calculations to interpret federal spending efficiency.

Evaluated policy lag effects on inflation control using time-series data visualization (Jupyter Notebook).

Skills Highlighted:
Econometric modeling, data cleaning (Pandas), and macroeconomic interpretation.

Outcome:
Produced a policy-facing analysis illustrating how data-driven econometric evaluation can inform fiscal decisions — relevant to forecasting and policy research positions.

### Business Analytics & Predictive Modeling Project (Quantitative Methods)


Purpose:
Applied statistical inference and predictive analytics to corporate operational datasets to forecast performance metrics and evaluate decision alternatives.

Key Components:

Built regression and correlation models to identify determinants of firm profitability.

Utilized Minitab, Python, and Jupyter to generate descriptive statistics, confidence intervals, and predictive trends.

Created Power BI dashboards to visualize KPI fluctuations and optimize managerial insight.

Outcome:
Demonstrated proficiency in statistical modeling and visualization for decision support — connecting analytics to economic interpretation.

### Portfolio Summary 

Jacob L. Smith – Applied Economics Graduate | Data Analytics & Econometrics

This portfolio showcases my applied economic and analytical work, ranging from firm-level financial analysis performed to macroeconomic forecasting and predictive modeling. Each project integrates data analysis, statistical rigor, and economic interpretation to inform business and policy decisions.

My technical toolkit includes Python, SQL, Tableau, Power BI, Minitab, Jupyter Notebooks, and Snowflake, applied across forecasting, econometric modeling, and visualization contexts.

Collectively, these projects demonstrate my ability to translate quantitative data into actionable economic insight — skills directly relevant to economic forecasting, data analytics, and consulting roles.
