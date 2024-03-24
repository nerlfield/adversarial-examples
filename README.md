# adversarial-examples

## Setup

To set up the environment for running the adversarial examples, follow these steps:

1. Create a new conda environment:
```bash
conda create --name advexamples python=3.11
```

2. Activate the newly created environment:
```bash
conda activate advexamples
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Lab to open the notebooks:
```bash
jupyter lab --no-browser --ip 0.0.0.0 --port 8888 --allow-root --notebook-dir=.
```

## Notebooks

The `notebooks` directory contains Jupyter notebooks for various experiments with adversarial examples:

- `00_adv_noise_exp_sandbox.ipynb`: A sandbox notebook for experimenting with adversarial noise.

