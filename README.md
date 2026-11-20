Astro project with one TaskFlow DAG that prepares data, trains two models, and compares them.

DAG ID: `weekly_model_comparison`
Schedule: `@weekly`
Start command: `astro dev start`
UI: http://localhost:8080 (admin / admin)

DAG file: `dags/weekly_model_comparison.py`