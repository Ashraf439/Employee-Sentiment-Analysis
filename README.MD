# Employee Sentiment Analysis Workspace

## Summary

This project analyzes employee messages to assess sentiment, identify top performers and at-risk employees, and provide actionable insights for HR and management.

### Top Three Positive Employees (Most Recent Month)
| Rank | Employee | Monthly Score |
|------|----------|--------------|
| 1    | Kayne    | 13           |
| 2    | Eric     | 9            |
| 3    | Lydia    | 9            |

### Top Three Negative Employees (Most Recent Month)
| Rank | Employee | Monthly Score |
|------|----------|--------------|
| 1    | Bobette  | 1            |
| 2    | Johnny   | 1            |
| 3    | Rhonda   | 1            |


### Employees Flagged as Flight Risks
The following employees were flagged as potential flight risks for sending 4 or more negative messages within any rolling 30-day window:

- [Johnny]
- [Don]
- [Bobette]

*See `outputs/flight_risk_employees.csv` for the full list.

---

## Key Insights and Recommendations

- **Sentiment Trends:**  
  Most employees maintain a neutral or positive sentiment, but a small group consistently expresses negative sentiment.

- **Top Performers:**  
  The top positive employees can be recognized or leveraged as ambassadors for positive workplace culture.

- **Flight Risks:**  
  Employees flagged as flight risks should be engaged proactively by HR to address concerns and improve retention.

- **Recommendations:**  
  - Regularly monitor sentiment trends to identify shifts in morale.
  - Recognize and reward consistently positive contributors.
  - Intervene early with employees showing persistent negative sentiment to reduce turnover risk.
  - Use predictive modeling to anticipate and address emerging issues.

---

## Structure
- `data/`: Input dataset(s)
- `outputs/`: All generated outputs (CSV, TXT)
- `visualization/`: All generated images
- `Employee_Sentiment_Analysis.ipynb`: Jupyter Notebook with all tasks

## Usage
1. Place your `employee.csv` in the `data/` folder.
2. Open and run `Employee_Sentiment_Analysis.ipynb` cell by cell.
3. Outputs will be saved in the `outputs/` folder.
4. Images will be saved in the `visualization/` folder.

## Dependencies
Install with:

```
pip install -r requirements.txt
```