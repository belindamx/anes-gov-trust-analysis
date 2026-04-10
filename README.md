## Trust in Government by Party Affiliation (ANES 2024)

This analysis examines whether Democrats and Republicans differ in their trust in the U.S. federal government using 2024 ANES survey data. Since trust is an ordinal, non-normal variable, I use a Wilcoxon rank-sum test along with a nonparametric effect size (rank-biserial correlation).

**Key Findings**
- Democrats show **higher trust in government** than Republicans  
- Difference is **statistically significant** (Wilcoxon rank-sum, p < 0.05)  
- Effect size indicates a **moderate practical difference**, not just statistical noise  
- Results align with broader trends of **political polarization in trust**

**Methodology**
- Dataset: ANES 2024 survey (~5.5k respondents → ~1.8k after filtering)  
- Target: trust in government (ordinal scale 1–5)  
- Comparison: Democrat vs Republican  
- Test: Wilcoxon rank-sum (nonparametric)  
- Effect size: rank-biserial correlation  

**Data source:** American National Election Studies (ANES), 2024 Time Series  

**Files**
- `anes2024_govtrust.rmd`
- `anes2024_govtrust.pdf`
