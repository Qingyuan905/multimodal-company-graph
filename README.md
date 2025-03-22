# multimodal-company-graph
A project exploring multimodal graph learning on company financial and textual data for prediction and analysis


## Goals
- Build a company graph using industry classification and relationships
- Extract financial indicators (e.g. ROE, PE, Revenue) for structured input
- Use FinBERT or LLMs to encode 10-K text into node features
- Train a Graph Neural Network to predict company performance labels

## Project Structure
```
multimodal-company-graph/
├── data/               # Raw + processed data
├── notebooks/          # Jupyter experiments
├── results/            # Visuals, output metrics, figures
├── src/                # Core scripts, graph construction, model training etc.
│   ├── data_loader.py
│   └── graph_builder.py
├── requirements.txt    # list of Python packages needed to run this project
├── README.md
└── .gitignore
```

## Dependencies
Install via:
```bash
pip install -r requirements.txt
```

##  Status
  In progress – currently working on:
- Data collection pipeline (EDGAR + yfinance)
- Basic GCN training setup with PyG
