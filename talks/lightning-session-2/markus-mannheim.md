---
order: 3

title: "Investment uncertainty: modelling the caution that holds firms back"

authors:
  - name: Markus Mannheim
    affiliation: Department of Climate Change, Energy, the Environment and Water / Australian National University
    affiliation-short: DCCEEW / ANU

links:
  - label: Repository
    url: https://github.com/MarkusMannheim/investment_sandbox
  - label: Notebook
    url: https://colab.research.google.com/github/MarkusMannheim/investment_sandbox/blob/main/notebooks/investment_sandbox.ipynb
---

Least-cost models work out what an electricity system should contain, and assume that whatever is cheapest gets built. This agent-based model asks who is *willing* to build it. The model has no planner, and no one in it knows the future. It plays out a year at a time. Each year, the firms, which dislike risk, decide what to commit, using a forecast of what new plant might earn.

In a least-cost model, a higher cost of capital (WACC) makes plant more expensive, but everything still gets built. In this model, cautious firms hold back, so prices rise and demand goes unmet.

The model also tests the effect of government intervention. It includes a reliability tender, whose contract length can be varied, and shows what it does to unmet demand and what the contracts cost.

The model follows one region for 20 years, runs in a notebook and is a much simplified version of a larger, higher-fidelity model of the National Electricity Market. Participants can run it during the workshop, and each run takes seconds.
