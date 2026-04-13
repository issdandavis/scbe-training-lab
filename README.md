# SCBE Training Lab

> QLoRA configs, training scripts, eval harness, and dataset pipelines for the SCBE-AETHERMOORE ecosystem.

Extracted from the main framework so ML engineers can clone only what they need
on HuggingFace / Google Colab / ephemeral compute without pulling the entire
governance pipeline.

## What's here

- **QLoRA configs** for fine-tuning open models on SCBE training data
- **Vertex AI / HuggingFace training scripts**
- **Dataset ingest pipelines**
- **SFT records and eval harnesses**

## Published datasets

All training data is published on HuggingFace:

- [scbe-aethermoore-training-data](https://huggingface.co/datasets/issdandavis/scbe-aethermoore-training-data) — 1,484+ downloads
- [scbe-red-team-benchmarks](https://huggingface.co/datasets/issdandavis/scbe-red-team-benchmarks) — 91 prompts, 10 categories
- [polly-training-data](https://huggingface.co/datasets/issdandavis/polly-training-data)
- [scbe-aethermoore-datasets](https://huggingface.co/datasets/issdandavis/scbe-aethermoore-datasets) — 15,206-row SFT corpus

## Published models

The Polly family + PHDM embedding model + GeoSeed network:

- [polly-chat-qwen-0.5b](https://huggingface.co/issdandavis/polly-chat-qwen-0.5b)
- [scbe-pivot-qwen-0.5b](https://huggingface.co/issdandavis/scbe-pivot-qwen-0.5b)
- [phdm-21d-embedding](https://huggingface.co/issdandavis/phdm-21d-embedding)

## Related repos

- [SCBE-AETHERMOORE](https://github.com/issdandavis/SCBE-AETHERMOORE) — main framework
- [scbe-experiments](https://github.com/issdandavis/scbe-experiments) — reproducible benchmark scripts
- [scbe-agents](https://github.com/issdandavis/scbe-agents) — HYDRA swarm runtime

## Paid training datasets

Curated commercial datasets are sold directly at [aethermoore.com/datasets.html](https://aethermoore.com/datasets.html):
$49-$399 for individual packs, $399 for the Full Arsenal bundle.

## License

MIT (code) — training data licenses vary per dataset, see individual HF cards
