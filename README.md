# Victorian-LGA-Clustering
Clustering LGAs in Victoria based on their rental profiles and socio-economic variables

## Project Overview
Melbourne’s rental market is one of the fastest-changing in Australia. For international students, families, and policymakers, rent affordability is a constant challenge.  
This project applies **K-Means clustering** to group Melbourne LGAs (Local Government Areas) based on rental profiles and socio-economic variables.

The goal: uncover patterns across LGAs to support better housing policy and planning.

---

## Data & Features
The clustering was based on variables such as:
- Rent dynamics: Rent growth, absolute rent change, average annual growth rate  
- Socio-economic factors: Median household income, unemployment, household size, age distribution  
- Demographics: Proportion born in Australia, income distribution  
- Geography: Distance to CBD  

---

## Methodology
- Algorithm: K-Means Clustering  
- Preprocessing: Standardization of features  
- Evaluation: Cluster interpretability and domain relevance  

---

## Key Findings

### Cross-Cluster Insights
- Rent vs. Income mismatch → Some LGAs see rents rising faster than incomes, even in higher-income regions.  
- Far ≠ Cheap → Outer LGAs are not always more affordable; some regional areas face higher rent growth than closer suburbs.  
- Demographics & affordability → Younger, diverse LGAs show higher unemployment and larger households, suggesting shared living as a coping strategy.  

---

### Cluster-Level Profiles

| Cluster | Rent Growth | Median Income | Age | CBD Distance | Key Traits |
|---------|-------------|---------------|-----|--------------|------------|
| 0 | 0.74 | $1,600 | 40 yrs | 120 km | Moderate incomes, balanced rent rise, larger household sizes |
| 1 | 0.64 | $1,800 | 36 yrs | 27 km | Younger, diverse, higher unemployment, largest household sizes |
| 2 | 0.64 | $1,200 | 51 yrs | 150 km | Older, lower incomes, high proportion born in Australia |
| 3 | 0.52 | $2,100 | 38 yrs | 17 km | Inner-city, highest incomes, rising rents, younger populations |
| 4 | 0.99 | $1,240 | 48 yrs | 242 km | Regional, lower incomes but highest rent growth |

---

## Why This Matters
By clustering LGAs, we highlight that Melbourne’s rental challenges are not uniform.  
Policymakers and planners can design targeted housing strategies — supporting inner-city affordability differently from outer regional areas.



