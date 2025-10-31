# Analysis of 'Immigration Services Scams Complaints' 2022-2025 — DCWP

## Overview
This repository contains data, analysis code, and findings related to complaints against immigration service providers in New York City. The analysis focuses on complaints submitted to the NYC Department of Consumer and Worker Protection (DCWP) between 2022 and 2025. Please refer to the NYC Open Data website for additional context.

---

## Data
This analysis uses a spreadsheet (`DCWP_Consumer_Complaints_20251010.csv`) containing information about consumer complaints filed against businesses.  

### Key columns used in the analysis:
- **Intake date** — The date the complaint was received by DCWP.  
- **Complaint code** — Indicates the type of business practice involved in the complaint.  
- **Business category** — The business activity or category subject to the complaint.  
- **Result** — The type of resolution for the complaint.  
- **Borough** — The NYC borough where the business is located.  
- **Business name** — The legal business name filed with the New York State Secretary of State or County Clerk, or if an individual, the person’s first and last name.

### How the data is used
- Show patterns of problems with immigration service providers in NYC.  
- Highlight that **Queens has the highest number of complaints**.  
- Identify the most common issues, such as:
  - Non-delivery of paid services  
  - False promises  
  - Mishandled paperwork  
- Examine which businesses are repeatedly cited.  
- Analyze complaint outcomes, showing that most are:
  - Closed without compensation  
  - Resolved through mediation only  

### Re-use opportunities
- Create **charts** or **maps** highlighting “hot spots” of problematic businesses.  
- Investigate the **owners, locations, and operations** of providers.  
- Help journalists and researchers uncover recurring issues and inform the public about unreliable or risky businesses.

---

## Methodology
The analysis is performed using Python and pandas, and involves:  
- Loading and cleaning the CSV data.  
- Grouping complaints by `Complaint Code` and `Result`.  
- Sorting to identify the **top complaints**.  
- Generating tables and visualizations for exploration.

---

## Who I am

I'm a bilingual journalist and data reporter currently pursuing a Master’s in Journalism at the Craig Newmark Graduate School of Journalism in New York and interning at Gothamist. My recent work focuses on immigration and Latino communities in the U.S., where I’ve reported on the struggles of undocumented street vendors and asylum seekers in New York, and Phoenix, for outlets like El País US and The Arizona Republic.
