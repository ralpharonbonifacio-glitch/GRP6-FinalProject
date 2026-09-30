# GRP6-FinalProject

### Members

- Ralph Aron Bonifacio
- Andrei Karl Dela Cruz
- Eivrard Seraphim Franco
- Matthew Zachary Medallon
- Josef Jayden Nepomuceno

## Project Title

Analyzing Palay and Corn Production and Harvested Area Across Philippine Regions, 2016–2026

## Project Overview

This project analyzes palay and corn production and harvested area across Philippine regions from 2016 to 2026. The group will use two related datasets from Philippine Statistics Authority (PSA) OpenSTAT: Volume of Production and Area Harvested.

The original datasets cover 1987 to 2026. For this project, the group will focus the analysis on 2016 to 2026 to maintain a more focused and manageable scope.

## Analytical Questions

1. How has the production of palay and corn changed across Philippine regions from 2016 to 2026?

2. How has the area harvested for palay and corn changed across Philippine regions from 2016 to 2026?

3. How does harvested area relate to the production of palay and corn across regions and crop types from 2016 to 2026?

## Proposed Datasets

### 1. Volume of Production

- **Provider:** Philippine Statistics Authority (PSA) - OpenSTAT
- **Dataset:** Palay and Corn: Volume of Production in Metric Tons by Ecosystem/Croptype, Quarter, Semester, Region and Province, 1987-2026
- **Coverage:** 1987-2026
- **Unit:** Metric tons

### 2. Area Harvested

- **Provider:** Philippine Statistics Authority (PSA) - OpenSTAT
- **Dataset:** Palay and Corn: Area Harvested in Hectares by Ecosystem/Croptype, Quarter, Semester, Region and Province, 1987-2026
- **Coverage:** 1987-2026
- **Unit:** Hectares

## Dataset Relationship

The Production and Area Harvested datasets contain the same `Ecosystem/Croptype` and `Geolocation` fields, which will be used as the proposed integration keys.

Initial validation found 654 unique key combinations in each dataset. All 654 combinations matched between the two datasets, with no unmatched key combinations found during the initial inspection.

## Group Responsibilities

| Member | Main Responsibility | Peer Reviewer |
|---|---|---|
| Ralph | Data acquisition, initial data inspection, and validation | Josef |
| Andrei | Production dataset cleaning and preprocessing | Ralph |
| Eivrard | Area harvested dataset cleaning and NumPy task | Andrei |
| Matthew | Dataset integration and data analysis | Eivrard |
| Josef | Data visualization, testing, and reliability checks | Matthew |

### Collaboration

Each member will contribute substantive Python code and review another member's work. Responsibilities may be adjusted as the project progresses based on the group's needs and instructor feedback.

## Project Structure

```text
data/
├── raw/
└── sample/

notebooks/
├── week8_initial_inspection.ipynb

src/
docs/
proposal/
```

## Initial Inspection

The group conducted an initial Python inspection of the datasets to examine their shape, columns, data types, and basic data quality issues. The inspection also identified the proposed integration keys and checked whether the key combinations matched between the two datasets.

## Project Status

**Week 8 - Initial Proposal and Programming Plan**

The group has completed the initial inspection and validation of the two PSA OpenSTAT datasets. The proposed analysis scope is 2016–2026, and the group has defined three analytical questions for the project proposal.
