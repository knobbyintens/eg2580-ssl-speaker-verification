# Self-Supervised Speaker Verification with Contrastive Pretraining

Official implementation for the paper **"Self-Supervised Speaker Verification with Contrastive Pretraining"**, accepted at Odyssey 2025.

## Status

**Released.** The complete training code, evaluation scripts, configuration files
and pretrained checkpoints are publicly available in this repository.

## Repository layout

```
├── src/          core model and training code
├── data/         data preparation and splits
├── experiments/  experiment configurations
├── results/      evaluation tables and figures
├── notebooks/    analysis notebooks
└── tests/        unit tests
```

## Quick start

```bash
git clone https://github.com/knobbyintens/eg2580-ssl-speaker-verification.git
cd eg2580-ssl-speaker-verification
pip install -r requirements.txt
python src/train.py --config experiments/odyssey2025.yaml
```

## Citation

```bibtex
@inproceedings{brooks2025sslverification,
  title={Self-Supervised Speaker Verification with Contrastive Pretraining},
  author={Brooks, Stephen and others},
  booktitle={Odyssey 2025},
  year={2025}
}
```
