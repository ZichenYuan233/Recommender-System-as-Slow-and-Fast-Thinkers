# Recommender System as Slow and Fast Thinkers

This repository contains the source code for **Recommender System as Slow and Fast Thinkers**, a sequential recommendation project that studies adaptive fast-slow inference for heterogeneous user environments.

## Overview

DS-Frame combines:

- a fast recommendation path for routine user sequences;
- a slow latent-refinement path for harder cases;
- a learned selector that routes samples under a controllable computation budget.

The framework figure is available at [picture/algorithm.pdf](picture/algorithm.pdf).

## Structure

```text
.
├── main.py
├── helpers/
├── models/
├── utils/
└── picture/
    └── algorithm.pdf
```

## Usage

The main entry point is:

```bash
python main.py --model_name PRL
```

Model, dataset, and training options can be configured through command-line arguments in `main.py`, `helpers/`, and `models/`.
