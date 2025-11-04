# Linear Regression - Chicago Taxi Fare

This repository contains a small interactive Jupyter notebook (`linear_regression_taxi.ipynb`) that demonstrates training a simple TensorFlow/Keras linear regression model to predict taxi fares from trip features (e.g. `TRIP_MILES`).

## Contents

- `linear_regression_taxi.ipynb` — primary notebook used for data exploration, model definition, training and visualization.

## Quick start

1. Create and activate a Python virtual environment (optional but recommended):

```powershell
python -m venv myenv
.\myenv\Scripts\Activate.ps1
```

2. Install required packages. The notebook expects TensorFlow and plotting libraries. Example:

```powershell
pip install -r requirements.txt
```

If `requirements.txt` is not present, install minimal packages used in the notebook:

```powershell
pip install tensorflow plotly pandas matplotlib
```

3. Open the notebook in Jupyter or VS Code and run the cells.

## Notes

- The notebook downloads a sample Chicago taxi dataset from a public URL.
- Training may be slow on CPU; consider reducing epochs or using a smaller sample during testing.


