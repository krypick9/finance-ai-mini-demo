# T1 Project Plan

## Project Goal

Develop a clear and reproducible research workflow that compares three familiar asset classes represented by ETFs: SPY (US equities), TLT (long-term US Treasury bonds), and GLD (gold). The focus is on building a verifiable, AI-assisted analysis process rather than collecting real market data.

## Available Data

`data/etf_snapshot.csv` is a small, fixed dataset with one row per illustrative ETF and six columns:

- `ticker` — ETF identifier
- `asset_class` — broad type of asset
- `expected_return_pct` — illustrative annual return assumption (% per year)
- `volatility_pct` — illustrative annual variability assumption (% per year)
- `max_drawdown_pct` — illustrative largest peak-to-trough loss (%)
- `expense_ratio_pct` — illustrative annual fund fee (% per year)

The dataset is synthetic teaching data, not live or historical market observations, and must not be used for investment decisions.

## Expected Final Deliverable

A written project plan and a reproducible workflow that compares SPY, TLT, and GLD using the provided snapshot. The plan will define a bounded analysis task and an organized, verifiable agent workflow that later tutorials can run on the same repository.

## Three Project Milestones

1. **Project setup (T1)**: Create this initial project plan and confirm the repository structure and data files are in place.
2. **Bounded analysis design (planned)**: Define a specific comparison question and the expected analysis steps using the snapshot fields.
3. **Workflow verification (planned)**: Run the analysis as a verifiable agent workflow and review the results against the plan.

## One Data Limitation

All numeric values in the dataset are synthetic teaching assumptions, not current quotations, verified historical estimates, or forecasts. The dataset also omits correlations, taxes, transaction costs, liquidity, currency exposure, and investor-specific constraints.

## Next Action

Review this plan with the student, then commit the `artifacts/t1/project-plan.md` file with Git. The commit and push are performed manually by the student; JiuWenSwarm will not run Git commands that change files, commits, branches, or remotes.