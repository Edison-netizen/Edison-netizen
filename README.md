# Jack Tan

<img align="right" src="https://raw.githubusercontent.com/Edison-netizen/Edison-netizen/main/assets/avatar.jpg" width="160" alt="profile avatar" />

```console
$ whoami
time-series ML notes, baselines, and reproducible experiments

$ uptime
slowly turning papers into runnable code
```

I keep a public lab around time-series machine learning: small baselines, paper notes, anomaly-detection utilities, and experiments that are simple enough to audit.

The goal is not to look busy. The goal is to make each claim traceable to code, a split, a metric, and a failure case.

## Research Focus

- Forecasting baselines: seasonal naive, moving average, DLinear-style questions
- Neural forecasting reading: PatchTST, iTransformer, TimesNet, FEDformer
- Anomaly detection: thresholds, event-level metrics, cooldowns, label delay
- Evaluation discipline: chronological splits, leakage checks, seed variance
- Research engineering: small scripts, explicit configs, boring tests

## Open Lab

```text
time-series-research-lab/       runnable baselines, metrics, synthetic smoke tests
neural-forecasting-notes/       paper cards, reading traces, implementation details
anomaly-detection-cookbook/     metrics, thresholding, failure cases, small utilities
temporal-foundation-models/     masking utilities and cautious pretraining notes
```

## Technical Stack

```text
Language     Python, Bash, SQL
ML           PyTorch reading notes, scikit-learn-style evaluation habits
Systems      Linux, Git, Docker, SSH, Makefiles
Research     ablations, paper replication, benchmark hygiene
Data         multivariate time series, sensor streams, event logs
```

## Selected Repositories

| Repository | What it is |
|---|---|
| [`time-series-research-lab`](https://github.com/Edison-netizen/time-series-research-lab) | Runnable forecasting baselines with chronological windows and metrics. |
| [`neural-forecasting-notes`](https://github.com/Edison-netizen/neural-forecasting-notes) | Paper cards and replication notes for modern neural forecasting. |
| [`anomaly-detection-cookbook`](https://github.com/Edison-netizen/anomaly-detection-cookbook) | Event-level anomaly metrics and thresholding notes. |
| [`temporal-foundation-models`](https://github.com/Edison-netizen/temporal-foundation-models) | Small masking utilities and design notes for temporal pretraining. |

## Research Habits

1. Treat every benchmark split as a hypothesis, not a default.
2. Write the failure cases before writing the conclusion.
3. Prefer small controlled ablations over large unclear claims.
4. Keep scripts boring, configs explicit, and logs searchable.

```console
$ next experiment
replicate a baseline, isolate one variable, write the result down
```
