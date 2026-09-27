# Data

The dataset is not stored in this repository.

**Source:** the Google Advanced Data Analytics capstone dataset, also available on Kaggle as
[HR Analytics and Job Prediction](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction).

**Setup:** download the CSV and save it here as `HR_capstone_dataset.csv`.

| Column | Description |
|---|---|
| `satisfaction_level` | Self-reported job satisfaction (0–1) |
| `last_evaluation` | Most recent performance review score (0–1) |
| `number_project` | Number of projects the employee contributes to |
| `average_montly_hours` | Average monthly hours worked (renamed to `average_monthly_hours` in the notebook) |
| `time_spend_company` | Years at the company (renamed to `tenure`) |
| `Work_accident` | Whether the employee had a work accident (0/1) |
| `left` | Whether the employee left the company (0/1) — **target** |
| `promotion_last_5years` | Whether the employee was promoted in the last 5 years (0/1) |
| `Department` | Department |
| `salary` | Salary level: low / medium / high |

Shape: 14,999 rows × 10 columns; 3,008 exact duplicates are removed in the notebook, leaving 11,991 rows.
