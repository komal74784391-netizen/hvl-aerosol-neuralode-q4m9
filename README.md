# Aerosol Neural ODE

Release repository for the paper **"Neural ODEs for Aerosol Transport Forecasting"**
(Miller, Osei and Novak, Environmental Modelling & Software, 2025).

## Release status

The release bundle for the paper's experiments is archived under `releases/`.
See `releases/manifest.json` for the artifact index and download URLs. The
per-step training history is indexed as `releases/history.jsonl`; the evaluation
history is stored as `releases/artifacts/0000.parquet`. These are the artefacts
used to produce the results reported in the paper, and the bundle is published
for external reuse.

## Contents

- `config.yaml` — experiment configuration used for the reported results
- `output.log` — training log
- `wandb-summary.json` — final metrics reported in the paper
- `requirements.txt` — environment pins
- `releases/` — archived release artifacts
