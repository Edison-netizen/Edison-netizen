# Jack Tan

<img align="right" src="https://raw.githubusercontent.com/Edison-netizen/Edison-netizen/main/assets/avatar.jpg" width="160" alt="profile avatar" />

```console
$ whoami
time-series deep learning researcher, linux-first builder

$ uptime
building reproducible experiments for temporal data
```

I work around deep learning for time series: forecasting, anomaly detection, representation learning, and the engineering needed to make experiments reproducible.

My current focus is turning papers into runnable baselines, writing down what actually changes model behavior, and keeping research code clean enough that future-me can trust it.

## Research Focus

- Long-horizon forecasting: PatchTST, iTransformer, TimesNet, DLinear/NLinear
- Temporal representation learning: masking, contrastive objectives, sequence encoders
- Anomaly detection: reconstruction error, predictive uncertainty, thresholding protocol
- Evaluation discipline: rolling windows, leakage checks, ablations, seed variance
- Research engineering: Linux, Python, PyTorch, experiment configs, clean logs

## Open Lab

```text
time-series-research-lab/       baselines, experiment structure, reproducibility notes
neural-forecasting-notes/       paper cards, reading traces, implementation details
anomaly-detection-cookbook/     metrics, thresholding, failure cases, small utilities
temporal-foundation-models/     data windowing, pretraining sketches, config templates
```

## Technical Stack

```text
Language     Python, Bash, SQL
ML           PyTorch, NumPy, pandas, scikit-learn
Systems      Linux, Git, Docker, SSH, Makefiles
Research     ablations, paper replication, benchmark hygiene
Data         multivariate time series, sensor streams, event logs
```

## Selected Repositories

| Repository | What it is |
|---|---|
| [`time-series-research-lab`](https://github.com/Edison-netizen/time-series-research-lab) | Research-grade scaffold for forecasting experiments and baselines. |
| [`neural-forecasting-notes`](https://github.com/Edison-netizen/neural-forecasting-notes) | Paper notes for modern neural forecasting models. |
| [`anomaly-detection-cookbook`](https://github.com/Edison-netizen/anomaly-detection-cookbook) | Practical recipes for time-series anomaly detection and evaluation. |
| [`temporal-foundation-models`](https://github.com/Edison-netizen/temporal-foundation-models) | Early experiments around masked modeling and temporal pretraining. |

## Research Habits

1. Treat every benchmark split as a hypothesis, not a default.
2. Write the failure cases before writing the conclusion.
3. Prefer small controlled ablations over large unclear claims.
4. Keep scripts boring, configs explicit, and logs searchable.

```console
$ next experiment
replicate a baseline, isolate one variable, write the result down
```
