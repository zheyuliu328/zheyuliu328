# Zheyu Liu

### Model validation · Credit and market risk · Reproducible analytics

I build local tools and inspectable experiments that connect financial theory, data quality and software testing.
My focus is understanding **what a model result proves, how it can fail, and how to reproduce it**.

MSc in Risk Management Science and Data Analytics, The Chinese University of Hong Kong · July 2026.

## Start here

### [Forecast Review Workbench](https://github.com/zheyuliu328/forecast-review-workbench)

A local browser tool with three connected workflows: screen monthly regression candidates,
review supplied forecasts on a common sample, and reconcile financial result rows with additive totals.
Select your own CSV/XLSX files, map their columns, inspect failures and missing coverage,
record your reasoning and download offline evidence.

Version 0.2 retains every attempted single/pair OLS candidate and two baselines, fixes selection on
development data before explicit holdout evaluation, and exposes reported-total errors even when
individual rows agree. The workbench has 126 passing Python tests and real-file browser acceptance
with independently recomputed exports. Independent human usability testing remains open.
Source declarations and model suitability still require judgment.

[Open and use the tool](https://github.com/zheyuliu328/forecast-review-workbench#open-the-tool) ·
[See the interface and verification](https://github.com/zheyuliu328/forecast-review-workbench/blob/main/docs/VALIDATION.md) ·
[中文使用指南](https://github.com/zheyuliu328/forecast-review-workbench/blob/main/docs/QUICKSTART.zh-CN.md)

### [Model Risk Lab](https://github.com/zheyuliu328/model-risk-lab)

Independent validation experiments built from public methods and fully synthetic inputs.

- **Credit regression:** information availability, forward time splits, baseline comparisons and a locked holdout.
- **FX sensitivities:** European option pricing, analytical Greeks, unit contracts and finite-difference convergence.
- **Monthly candidate tool:** configurable observations, lag/release-delay checks, retained failures,
  development selection, explicit holdout reveal and a standalone evidence CLI.
- **Evidence:** runnable tests, generated reports, complete inputs and explicit limitations.

[Read the experiment report](https://github.com/zheyuliu328/model-risk-lab/blob/main/docs/sample/REPORT.md) ·
[See what the second review caught](https://github.com/zheyuliu328/model-risk-lab/blob/main/docs/REVALIDATION.md) ·
[Read the methods](https://github.com/zheyuliu328/model-risk-lab/tree/main/docs) ·
[Run it locally](https://github.com/zheyuliu328/model-risk-lab#run-locally)

### [VaR Backtesting](https://github.com/zheyuliu328/risk-var-dashboard)

A focused market-risk project: rolling forecasts use only earlier returns; coverage tests expose
their assumptions and edge cases. A reproducible offline example accompanies the implementation.

## Earlier projects, with current status

| Project | Area | Where to look |
|:--|:--|:--|
| [CreditOne](https://github.com/zheyuliu328/algorithmic-credit-risk-engine) | Credit-scoring and data-processing prototypes | [Verified scope and remaining work](https://github.com/zheyuliu328/algorithmic-credit-risk-engine/blob/master/docs/PORTFOLIO_STATUS.md) |
| [Financial Control Tower](https://github.com/zheyuliu328/financial-control-tower) | CSV/Excel reconciliation, field mapping, tolerances and readable reports | [Table comparison guide](https://github.com/zheyuliu328/financial-control-tower/blob/main/docs/table-comparison.md) |
| [Signal Foundry](https://github.com/zheyuliu328/signal-foundry) | Local-first information tooling | [Project overview](https://github.com/zheyuliu328/signal-foundry#readme) |

These projects have different levels of maturity. Their status records distinguish working examples,
incomplete features and future designs. Forked repositories in this account are learning references
and are not presented here as original implementations.

## How I work

1. Define the question, input units and information available at the decision time.
2. Establish a simple baseline and an independent check before adding complexity.
3. Retain negative results and failure cases, with enough evidence to reproduce them.
4. Separate implementation checks from real-world suitability and approval.

The featured validation experiments use public methods and invented inputs. Older projects document
their data sources and unverified legacy assets in their status notes. Professional/client files,
code, templates and confidential outputs remain outside this portfolio. The projects are educational;
they do not imply employer endorsement or regulatory approval. AI-assisted development is disclosed
in the projects where used; explanation, review and reproducibility remain part of the work.

**Next validation:** independent human use and repeat real-task adoption of the tools.
Broader release-delay and robustness sweeps in the separate quarterly teaching experiment remain future work.
[Follow the next experiments](https://github.com/zheyuliu328/model-risk-lab/blob/main/ROADMAP.md).
