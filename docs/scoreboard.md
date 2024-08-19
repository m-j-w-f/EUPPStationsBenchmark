---
layout: default
title: "Scoreboard"
description: "Performance on the R2R and R2F tasks"
---

## Scores on the *R2R* and *R2F* tasks

### Reforecast to Reforecast

| Model | CRPS (24h) | CRPS (72h) | CRPS (120h) |
|---|---|---|---|
| ENS | 1.20 | 1.28 | 1.54 |
| [DRN](https://journals.ametsoc.org/view/journals/mwre/146/11/mwr-d-18-0187.1.xml) | 0.66 | 0.87 | 1.18 |
| [GAT](https://arxiv.org/abs/2407.11050#) | **0.63** | **0.85** | **1.17** |

### Reforecast to Forecast

| Model | CRPS (24h) | CRPS (72h) | CRPS (120h) |
|---|---|---|---|
| ENS | 1.12 | 1.18 | 1.38 |
| [DRN](https://journals.ametsoc.org/view/journals/mwre/146/11/mwr-d-18-0187.1.xml) | 0.61 | 0.79 | 1.11 |
| [GAT](https://arxiv.org/abs/2407.11050#) | **0.60** | **0.78** | **1.09** |

## How to contribute

Just create a pull request and append the scores of your model here.
