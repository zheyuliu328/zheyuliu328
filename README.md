# Zheyu Liu

### Model validation · Credit and market risk · Reproducible analytics

I build browser tools, local utilities and inspectable experiments that connect financial theory, data quality and software testing.
My focus is understanding **what a model result proves, how it can fail, and how to reproduce it**.

MSc in Risk Management Science and Data Analytics, The Chinese University of Hong Kong · July 2026.

## Open a tool

| Your task | Browser tool | Result |
| --- | --- | --- |
| Compare actuals and forecasts on the same sample | [Forecast review](https://forecast-review-zheyuliu.mystic-pear-2111.chatgpt.site) | Errors, excluded periods and a downloadable review |
| Check differences between two CSV/Excel tables | [Table check](https://table-check-zheyuliu.mystic-pear-2111.chatgpt.site) | Differences, missing records, duplicates and exports |

No installation or account is required. Selected files are processed in the browser; both tools include invented examples. [Current status and remaining gaps](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/catalog/RELEASE_STATUS.zh-CN.md) distinguish these public tools from local experiments and unfinished prototypes. Independent human first use and repeat use remain unverified.

## Featured case · The model ranking reversed

Candidate A looked more accurate: **MAE 1.56 vs 4.30**. But it omitted different months.
Comparing the same seven months changed the result: **A 2, B 1**. The conclusion was to request
missing coverage and forecast-vintage evidence, not automatically approve B.

[![Different evaluation samples favor A; the same seven months favor B. Invented teaching data.](https://raw.githubusercontent.com/zheyuliu328/risk-practice-portfolio/main/assets/forecast-ranking.png)](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/flagship/forecast-review/README.md)

**What you can run:** import actuals and forecast CSV/Excel files, inspect coverage, explicitly accept
a common sample, compare errors, record a reason and export offline evidence.

[**Explore the case →**](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/flagship/forecast-review/README.md) ·
[Read the review memo](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/flagship/forecast-review/REVIEW_MEMO.md) ·
[Open the Workbench](https://forecast-review-zheyuliu.mystic-pear-2111.chatgpt.site)

## More work you can inspect or use

| Work question | Executable work | Evidence to inspect |
| --- | --- | --- |
| Can equal totals hide errors? | [Financial Control Tower](https://table-check-zheyuliu.mystic-pear-2111.chatgpt.site): compare CSV/Excel records | Missing keys, duplicates and numeric exceptions |
| Prices agree; do the Greeks? | [Model Risk Lab](https://github.com/zheyuliu328/model-risk-lab): analytical/finite-difference challenges | Unit conventions, bump sensitivity and retained failures |
| Why did the loss estimate rise? | [ECL movement case](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/examples/ecl-movement.json): fixed-order parameter bridge | Reconciled movement, assumptions and limits |
| Does collateral mean available cash? | [Margin stress case](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/examples/broker-margin.json): haircut and liquidity stress | Required calls versus realizable cash |

[**Full portfolio**](https://github.com/zheyuliu328/risk-practice-portfolio) ·
[Learning laboratory](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/lab/README.md) ·
[中文学习与面试路线](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/learning/README.zh-CN.md) ·
[References and attribution](https://github.com/zheyuliu328/risk-practice-portfolio/blob/main/reference/README.md)

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
