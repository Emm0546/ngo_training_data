# NGO Training Sessions: Data Analysis in Excel

Excel analysis of training sessions run by a small NGO in 5 districts
(Sept to Oct 2026).

> **Note:** the dataset is synthetic, made for practice. The numbers are
> not real figures.

## Context
I played the role of an M&E assistant. The manager needed answers about
participation, women's attendance, trainer satisfaction and costs.

## Data
`ngo_training_data.xlsx`
- `sessions`: one row per training session (date, district, topic, trainer,
  participants, women, satisfaction score from 1 to 5, cost in FCFA)
- `planned_costs`: planned cost per session for each topic

## Problems in the raw data
- District names written in different ways (extra spaces, capitals)
- [number] duplicate session IDs
- Blank and "n/a" values in the satisfaction column





## Tools
Excel (web): TRIM, Remove Duplicates, XLOOKUP, SUMIFS, COUNTIFS, AVERAGEIFS,
IF, pivot tables
