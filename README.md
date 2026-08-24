# Prosper Loan Data Analysis

An exploratory analysis of Prosper peer-to-peer loan data, focused on how lending activity, borrower characteristics, interest rates, and outcomes changed around the 2008 financial crisis.

## Questions explored

- How did loan volume and funded amounts change over time?
- How did borrower rates and loan outcomes evolve after 2008?
- Which loan purposes became more common?
- What distinguishes debt-consolidation loans from other borrowing?

## Key findings

- Loan counts and funded amounts fell sharply after the financial crisis, then recovered and reached their highest levels in the dataset by 2013.
- Borrower rates increased after 2008 before beginning to decline around 2011.
- Default rates were highest among the earliest cohorts and declined as completed loans became more common.
- Debt consolidation became the dominant stated purpose, representing roughly 80% of loans by 2013.
- Debt-consolidation borrowing became more prevalent as the number of open credit lines increased.

These results are descriptive patterns in the available data and should not be interpreted as causal effects.

## Dataset

The analysis uses the [Prosper Loan dataset](https://www.kaggle.com/datasets/yousuf28/prosper-loan). Variable definitions are available in the accompanying [feature documentation](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

## Analysis workflow

1. Assess data quality and select relevant variables.
2. Explore loan activity and pricing over time.
3. Compare loan status and purpose distributions.
4. Investigate debt-consolidation behavior in greater depth.
5. Communicate the main patterns through explanatory visualizations.

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, and Jupyter Notebook.

## Limitations

The dataset represents Prosper applicants rather than the broader credit market. Later loans also have less time to reach a final outcome, so comparisons of defaults across origination years require care.
