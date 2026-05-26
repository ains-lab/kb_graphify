# Graph Report - data/hoseo/job_rate  (2026-05-26)

## Corpus Check
- Corpus is ~43,967 words - fits in a single context window. You may not need a graph.

## Summary
- 33 nodes · 66 edges · 4 communities
- Extraction: 76% EXTRACTED · 24% INFERRED · 0% AMBIGUOUS · INFERRED: 16 edges (avg confidence: 0.84)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Hoseo Admissions|Hoseo Admissions]]
- [[_COMMUNITY_Economic Labor Context|Economic Labor Context]]
- [[_COMMUNITY_Education Indicators|Education Indicators]]
- [[_COMMUNITY_Graduate Employment|Graduate Employment]]

## God Nodes (most connected - your core abstractions)
1. `Korea Education and Employment Indicators` - 9 edges
2. `Hoseo University` - 9 edges
3. `Hoseo University 2023 Rolling Admission Results` - 7 edges
4. `Hoseo University 2024 Graduate Employment Status` - 7 edges
5. `Hoseo University 2025 Rolling Admission Results` - 6 edges
6. `Hoseo University 2025 Regular Admission Results` - 6 edges
7. `Hoseo University 2023 Regular Admission Results` - 6 edges
8. `Hoseo University 2023 Graduate Employment Status` - 6 edges
9. `Hoseo University 2025 Graduate Employment Status` - 6 edges
10. `Hoseo University Employment Rate Summary` - 6 edges

## Surprising Connections (you probably didn't know these)
- `Graduate Employment Rate` --semantically_similar_to--> `Employment Rate`  [INFERRED] [semantically similar]
  data/hoseo/job_rate/korea_education_employment_indicators.md → data/hoseo/job_rate/취업률.md
- `Korea Economic Indicators` --semantically_similar_to--> `Korea Education and Employment Indicators`  [INFERRED] [semantically similar]
  data/hoseo/job_rate/korea_economic_indicators.md → data/hoseo/job_rate/korea_education_employment_indicators.md
- `Hoseo University 2025 Rolling Admission Results` --semantically_similar_to--> `Hoseo University 2025 Regular Admission Results`  [INFERRED] [semantically similar]
  data/hoseo/job_rate/2025수시입시결과.md → data/hoseo/job_rate/2025정시입시결과.md
- `Hoseo University 2023 Rolling Admission Results` --semantically_similar_to--> `Hoseo University 2023 Regular Admission Results`  [INFERRED] [semantically similar]
  data/hoseo/job_rate/2023수시입시결과.md → data/hoseo/job_rate/2023정시입시결과.md
- `Hoseo University Employment Rate Summary` --references--> `Hoseo University`  [INFERRED]
  data/hoseo/job_rate/취업률.md → data/hoseo/job_rate/2025수시입시결과.md

## Hyperedges (group relationships)
- **Hoseo Admission Results Time Series** — 2022수시입시결과_hoseo_2022_rolling_admission_results, 2023수시입시결과_hoseo_2023_rolling_admission_results, 2025수시입시결과_hoseo_2025_rolling_admission_results, 2023정시입시결과_hoseo_2023_regular_admission_results, 2025정시입시결과_hoseo_2025_regular_admission_results, admission_competition_rate, final_registrant_grade [INFERRED 0.82]
- **Hoseo Graduate Employment Time Series** — 2023취업현황_hoseo_2023_graduate_employment_status, 2024취업현황_hoseo_2024_graduate_employment_status, 2025취업현황_hoseo_2025_graduate_employment_status, 취업률_hoseo_employment_rate_summary, employment_rate, employment_retention_rate [INFERRED 0.87]
- **Simulation Labor Market Context** — korea_education_employment_indicators_korea_education_employment_indicators, korea_economic_indicators_korea_economic_indicators, agent_simulation_reference_data, youth_unemployment_rate, unemployment_rate, gdp_growth, inflation, economic_anxiety, job_market_competition [EXTRACTED 1.00]

## Communities (4 total, 0 thin omitted)

### Community 0 - "Hoseo Admissions"
Cohesion: 0.56
Nodes (10): Hoseo University 2022 Rolling Admission Results, Hoseo University 2023 Rolling Admission Results, Hoseo University 2023 Regular Admission Results, Hoseo University 2025 Rolling Admission Results, Hoseo University 2025 Regular Admission Results, Admission Competition Rate, Final Registrant Grade Cutoff, Hoseo University (+2 more)

### Community 1 - "Economic Labor Context"
Cohesion: 0.32
Nodes (8): Economic Anxiety, GDP Growth, Inflation, Job Market Competition, Korea Economic Indicators, Unemployment Rate, World Bank, Youth Unemployment Rate

### Community 2 - "Education Indicators"
Cohesion: 0.29
Nodes (8): Agent Simulation Reference Data, 대학알리미, Education and Employment Conditions, Graduate Employment Rate, 교육통계서비스 / 교육부, Korea Education and Employment Indicators, 국가지표체계 / 통계청, University Entrance Rate

### Community 3 - "Graduate Employment"
Cohesion: 0.76
Nodes (7): Hoseo University 2023 Graduate Employment Status, Hoseo University 2024 Graduate Employment Status, Hoseo University 2025 Graduate Employment Status, Employment Rate, Employment Retention Rate, Graduate Employment Status, Hoseo University Employment Rate Summary

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Korea Education and Employment Indicators` connect `Education Indicators` to `Economic Labor Context`?**
  _High betweenness centrality (0.618) - this node is a cross-community bridge._
- **Why does `Employment Rate` connect `Graduate Employment` to `Education Indicators`?**
  _High betweenness centrality (0.516) - this node is a cross-community bridge._
- **Why does `Graduate Employment Rate` connect `Education Indicators` to `Graduate Employment`?**
  _High betweenness centrality (0.514) - this node is a cross-community bridge._
- **Are the 3 inferred relationships involving `Hoseo University 2023 Rolling Admission Results` (e.g. with `Hoseo University 2025 Rolling Admission Results` and `Hoseo University 2022 Rolling Admission Results`) actually correct?**
  _`Hoseo University 2023 Rolling Admission Results` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Are the 3 inferred relationships involving `Hoseo University 2024 Graduate Employment Status` (e.g. with `Hoseo University Employment Rate Summary` and `Hoseo University 2025 Graduate Employment Status`) actually correct?**
  _`Hoseo University 2024 Graduate Employment Status` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `Hoseo University 2025 Rolling Admission Results` (e.g. with `Hoseo University 2023 Rolling Admission Results` and `Hoseo University 2025 Regular Admission Results`) actually correct?**
  _`Hoseo University 2025 Rolling Admission Results` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `University Entrance Rate`, `Economic Anxiety`, `World Bank` to the rest of the system?**
  _6 weakly-connected nodes found - possible documentation gaps or missing edges._