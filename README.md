**Running title:** Hot starts make heat-tolerant but stress-prone frogs

This repository contains the code used to analyse data for the manuscript:

**Miguel, I.R., Burraco, P., Hakemann, C., Keunecke, L., Martin, C., Kruger, N., & Ruthsatz, K.**  
*Ontogenetic consequences of developmental temperature in amphibians: simultaneous gains in heat tolerance and cumulative costs to stress physiology*  

---

## Overview

This study examines the effects of developmental temperature on physiological performance, stress responses, and thermal tolerance across ontogeny in amphibians. Statistical analyses were conducted in **R** using mixed-effects models and generalized linear models.

---

## Repository contents

├── data/
│ ├── raw/ # Raw data (see Data availability)
│ └── processed/ # Cleaned datasets used for analyses
├── scripts/
│ ├── Larvae-life-history-traits-RMR-Q10.R
│ ├── Metamorphs.R
│ ├── Juveniles.R
│ ├── All-CTmax-fat-reserves.R
│ ├── Heatwave-control.R
│ ├── Heatwave-no-control.R
│ ├── Heatwave17.R
│ ├── Heatwave20.R
│ ├── Heatwave23.R
│ └── Heatwave26.R
├── session_info.txt # R environment and package versions
├── LICENSE # MIT License
└── README.md


---

## Scripts description

1. `Larvae-life-history-traits-RMR-Q10.R` – Larval growth, development, resting metabolic rate, and Q10 analyses  
2. `Metamorphs.R` – Metamorph stage 
3. `Juveniles.R` – Juvenile 
4. `All-CTmax-fat-reserves.R` – Thermal tolerance (CTmax) and fat reserve analyses across stages  
5. `Heatwave-control.R` – Heatwave experiment, baseline CORT
6. `Heatwave-no-control.R` – Heatwave experiment, post-heatwave CORT
7. `Heatwave17.R` – Heatwave experiment, 17°C treatment baseline vs post-heatwave CORT
8. `Heatwave20.R` – Heatwave experiment, 20°C treatment  baseline vs post-heatwave CORT
9. `Heatwave23.R` – Heatwave experiment, 23°C treatment  baseline vs post-heatwave CORT
10. `Heatwave26.R` – Heatwave experiment, 26°C treatment  baseline vs post-heatwave CORT

**Execution order:**  
Scripts should be run in the order above to reproduce the full analysis workflow. 

---

## Setup

1. Set the working directory to the root of this repository.  
2. Ensure required R packages are installed (listed in code).  
3. Run the analysis scripts in order

Package versions are recorded in session_info.txt.

If data files are missing, the scripts will stop and provide informative error messages.
Raw data are not publicly available due to ethical and permitting restrictions, but can be requested from the corresponding author.

Reproducibility
All analyses reported in the manuscript are implemented in the scripts provided. Model specifications correspond directly to those described in the Methods and Results sections.

Session information is provided in session_info.txt to document the R environment and package versions.

License
This repository is released under the MIT License.

Code repository DOI to be added upon publication.

Authorship and correspondence
Shared last authorship: Natasha Kruger and Katharina Ruthsatz contributed equally.

Corresponding author:
Katharina Ruthsatz
ORCID: 0000-0002-3273-2826
Email: katharinaruthsatz@gmail.com

---








