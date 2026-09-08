# Zheyu Liu

### Model validation · Credit and market risk · Reproducible analytics

I build inspectable experiments that connect financial theory, data quality and software testing.
My focus is understanding **what a model result proves, how it can fail, and how to reproduce it**.

MSc in Risk Management Science and Data Analytics, The Chinese University of Hong Kong · July 2026.

## Start here

### [Model Risk Lab](https://github.com/zheyuliu328/model-risk-lab)

Independent validation experiments built from public methods and fully synthetic inputs.

- **Credit regression:** information availability, forward time splits, baseline comparisons and a locked holdout.
- **FX sensitivities:** European option pricing, analytical Greeks, unit contracts and finite-difference convergence.
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
| [Financial Control Tower](https://github.com/zheyuliu328/financial-control-tower) | Reconciliation and audit-rule demonstrations | [Verified scope and remaining work](https://github.com/zheyuliu328/financial-control-tower/blob/main/docs/PORTFOLIO_STATUS.md) |
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

**Currently improving:** data-release timing, synthetic robustness experiments and numerical diagnostics.
[Follow the next experiments](https://github.com/zheyuliu328/model-risk-lab/blob/main/ROADMAP.md).
