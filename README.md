# Data Science Tools and Ecosystem

An introductory Python notebook for the IBM Data Science learning exercises. It summarizes common languages, libraries, and tools, then demonstrates arithmetic and conversion from minutes to hours.

## Contents

[`DataScienceEcosystem`](DataScienceEcosystem) is a Jupyter notebook stored as JSON without an `.ipynb` extension. Its metadata identifies a Python 3 kernel (Python 3.11.7 when saved).

Examples evaluate `(3 * 4) + 5` and `200 / 60`. Libraries such as pandas, NumPy, and TensorFlow are discussed, but are not required by these arithmetic cells.

## Open the notebook

Install Python 3 and JupyterLab in your preferred Python environment. From the repository root, create a copy with the standard extension:

```powershell
Copy-Item DataScienceEcosystem DataScienceEcosystem.ipynb
python -m pip install jupyterlab
python -m jupyterlab DataScienceEcosystem.ipynb
```

Choose the Python 3 kernel and run cells in order. The original file remains unchanged.

## Scope

This is a learning exercise, not a trained model or production data pipeline. No external dataset is needed for the included examples.
