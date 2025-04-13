## Summary

- Dataset: NYC Jobs postings
- Tools: PySpark, Pandas, Seaborn, Docker, Matplotlib
- Pipeline Included:
  - Data Cleaning
  - Feature engineering(degree tagging, Salary Mean, year extraction)
  - Visual analysis in Juypter
 
## Assumption
- Advanced degree inferred from text search
- Salary mean used as central metrics

## Challenges
- Inconsistent formatting in salary and date
- Missing values in some rows

## Suggested deployment
- Package PySpark job into a scheduled job (e.g. Airflow DAG)
- Store Result in BigQuery or GCP

## Triggering Approach
- Use CLI or REST API
- Schedule as part of weekly ETL Job


