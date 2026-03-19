# Parameter Golf — Working Fork

Fork of [openai/parameter-golf](https://github.com/openai/parameter-golf) for local experimentation and development.

## Setup

- Local training via PyTorch on a single GPU
- 1 training shard for fast iteration, full validation set for scoring

## Structure

- `train_gpt.py` / `train_gpt_mlx.py` — baseline training scripts (from upstream)
- `run_sweep*.sh` — experiment runners
- `logs/` — training outputs (gitignored)
