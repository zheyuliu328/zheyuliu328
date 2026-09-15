# Zheyu Liu

### Model validation · Credit and market risk · Reproducible analytics

I build local tools and inspectable experiments that connect financial theory, data quality and software testing.
My focus is understanding **what a model result proves, how it can fail, and how to reproduce it**.

MSc in Risk Management Science and Data Analytics, The Chinese University of Hong Kong · July 2026.

## Featured work: model review and evidence handoff

### [Forecast Review — the flagship task](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/flagship/forecast-review/README.md)

A candidate appears more accurate because it omits difficult months. The review checks the input contract,
retains missing periods, compares on an explicitly accepted common sample and hands over independently
checked results with a bounded recommendation. The worked example includes pending, accepted and
incompatible-unit states, plus a review memo and follow-up actions.

[Read the finding and action memo](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/flagship/forecast-review/REVIEW_MEMO.md) ·
[Run the actual Workbench](https://github.com/zheyuliu328/forecast-review-workbench#open-the-tool) ·
[Numerical foundation: Model Risk Lab](https://github.com/zheyuliu328/model-risk-lab)

The Workbench's training workflow uses a version-pinned Model Risk Lab kernel. Shared calculations are
not two independent validators. The portfolio's raw-CSV check independently recomputes the review metrics.
This is an executable educational workflow; production adoption and independent first-time human use
remain unverified.

## Explore by purpose

| Layer | What to inspect |
| --- | --- |
| [Specialist cases](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/specialist/README.md) | FX sensitivity challenges, ECL movement, market/collateral risk, FCT data control and negative research; each has separate scope and evidence |
| [Learning laboratory](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/lab/README.md) | Small credit, ALM, liquidity, AML and AI-control exercises; these are learning components, not equally mature products |
| [References and history](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/reference/README.md) | Team coursework, forks and supporting utilities with attribution |

[All project placements and priorities](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/catalog/PRIORITIES.md) ·
[中文学习与面试路线](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/learning/README.zh-CN.md)

The portfolio connects tasks and evidence while keeping project models, interfaces and release cycles separate.
Independent studies are not presented as client engagements or proof of personal mastery.

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
