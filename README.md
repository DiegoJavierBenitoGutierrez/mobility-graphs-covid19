# COVID-19 Mobility Graphs

This repository contains mobility graphs for Brazil, Japan, Turkey, and South Africa, generated using data from the University of Maryland COVID-19 Trends and Impact Survey (UMD-CTIS). These graphs are the result of the study:

**"Mobility Analysis during COVID-19 using Explainable Machine Learning Techniques"**  
Diego Benito, Jose Aguilar, Juan Marcos Ramírez, Antonio Fernández Anta (January 2025)

**Authors and Affiliations:**

- Diego Benito, Jose Aguilar — IMDEA Networks Institute, Madrid, Spain  
- Jose Aguilar — CEMISID, Universidad de Los Andes, Mérida, Venezuela
- Juan Marcos Ramírez  —  IMDEA Networks Institute, Madrid, Spain 
- Antonio Fernández Anta — IMDEA Software Institute, Madrid, Spain  
- Contact emails: diego.benito@imdea.org.

The repository is organized to allow easy exploration of mobility patterns and reproduction of the analyses.

---

## Repository Structure

The repository is organized by country and type of analysis:

```text
mobility-graphs-covid19/
├── Brazil/
│   ├── General Analysis of Dominant Patterns/
│   │   ├── General Case/
│   │   ├── Gender/
│   │   └── Age Groups/
│   └── Dominant Patterns of Positive Cases/
│       ├── General Case/
│       ├── Gender/
│       └── Age Groups/
├── Japan/
│   ├── General Analysis of Dominant Patterns/
│   │   ├── General Case/
│   │   ├── Gender/
│   │   └── Age Groups/
│   └── Dominant Patterns of Positive Cases/
│       ├── General Case/
│       ├── Gender/
│       └── Age Groups/
├── Turkey/
│   ├── General Analysis of Dominant Patterns/
│   │   ├── General Case/
│   │   ├── Gender/
│   │   └── Age Groups/
│   └── Dominant Patterns of Positive Cases/
│       ├── General Case/
│       ├── Gender/
│       └── Age Groups/
└── SouthAfrica/
    ├── General Analysis of Dominant Patterns/
    │   ├── General Case/
    │   ├── Gender/
    │   └── Age Groups/
    └── Dominant Patterns of Positive Cases/
        ├── General Case/
        ├── Gender/
        └── Age Groups/
```

- **Country folders**: Contain the mobility graphs for each country.  
- **General Analysis of Dominant Patterns**: Graphs showing overall mobility trends, separated by general case, gender, and age groups.  
- **Dominant Patterns of Positive Cases**: Graphs focusing on positive COVID-19 cases, also separated by general case, gender, and age groups. 

## Usage Instructions

1. Clone the repository:

```bash
git clone https://github.com/usuario/mobility-graphs-covid19.git
