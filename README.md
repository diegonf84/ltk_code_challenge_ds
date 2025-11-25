# Senior Data Scientist Code Challenge - ShopFlow Returns Prediction

Challenge submission for Senior Data Scientist position. Predictive model for e-commerce return optimization with business impact analysis.

## Files

- `frigerio_diego_challenge.ipynb` - Complete analysis and model development
- `summary.md` - Executive summary with deployment recommendations
- `xgboost_model.pkl` - Trained model artifact
- `requirements.txt` - Python dependencies

## Reproduction

This project uses [UV](https://github.com/astral-sh/uv) for dependency management.
```bash
# Install UV
curl -LsSf https://astral.sh/uv/install.sh | sh

# Create environment and install dependencies
uv venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
uv pip install -r requirements.txt

# Run notebook
jupyter lab frigerio_diego_challenge.ipynb
```

**For exact reproducibility:** Use `uv.lock` if available:
```bash
uv sync
```