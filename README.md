# ML Learning Notebooks

A collection of Jupyter notebooks for learning machine learning with PyTorch.

## Notebooks

### `ml_training_intro.ipynb`
An introduction to the core machine learning workflow using PyTorch. Covers:
- Generating a noisy dataset and splitting it into **training** and **test** sets
- Building a simple neural network
- Training the model and visualising the loss curve as it learns
- Watching the model improve across training epochs
- Running **inference** on held-out test data and measuring accuracy

The example task is fitting a sine wave from noisy observations — simple enough to understand visually, but representative of how real models are trained.

## Requirements

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Then open any notebook in VS Code or Jupyter and run all cells.

## License

BSD 3-Clause — see [LICENSE](LICENSE).
