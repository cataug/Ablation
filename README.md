# Graph Anomaly Ablation Experiments

This repository contains a lightweight snapshot of the authors' graph anomaly detection ablation experiments.

It includes the project notebooks, compact summaries, selected logs, aggregate result tables, sampled versions of oversized result CSV files, and selected figures. Public third-party dataset copies and external benchmark repositories are intentionally excluded.

## Repository contents

```text
*.ipynb
    Main project notebooks.

ablation_trivial_baselines_outputs/summary/
    Aggregated trivial-baseline ablation summaries.

kkt_anomaly_outputs/summary/
    Compact KKT anomaly summaries and selected figures.

kkt_anomaly_outputs/sampled_results_csv/
    Reduced samples of oversized ranked CSV outputs.

kkt_data_audit_outputs/
    Lightweight data audit reports and samples.

robustness_attribute_structure_outputs/summary/
    Robustness summaries.

MANIFEST.json
    File selection manifest.

Large ranked CSV files are not copied in full. Instead, reduced samples are generated and stored under:

kkt_anomaly_outputs/sampled_results_csv/
Notes

This repository is intended to preserve the authors' experimental logic and compact result evidence without redistributing public datasets, third-party repositories, or large generated artifacts.
