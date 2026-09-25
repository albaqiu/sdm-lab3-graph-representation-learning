# Citation Network Representation Learning

Experiments with representation learning for scholarly citation networks, combining knowledge graph embeddings (KGEs) and graph neural networks (GNNs).

## What it explores

- Transforming a publication citation dataset into a knowledge graph
- Training and evaluating knowledge graph embedding models with PyKEEN
- Comparing GCN, GraphSAGE, and GAT architectures on graph data
- Building classical machine-learning baselines for comparison
- Evaluating models through reproducible notebook experiments

## Contents

- `SDM_Lab3.ipynb` — data preparation, model training, and evaluation experiments
- `main.tex` / `main.pdf` — technical report source and rendered report
- `KGEStatement.pdf` — project brief

## Environment

Use Python 3.10+ and install the dependencies:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

`torch-geometric` installation may need the wheel matching your installed PyTorch version; see its official installation instructions if a normal `pip install` fails.

## Authors

Laia Jané and Runxiao Qiu
