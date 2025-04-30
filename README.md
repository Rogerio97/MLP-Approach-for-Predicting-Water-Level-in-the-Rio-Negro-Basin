# MLP Approach for Predicting Water Level in the Rio Negro Basin

This repository presents a **Multilayer Perceptron (MLP)**-based approach for predicting water levels in the **Rio Negro Basin**, one of the major sub-basins of the Amazon River. The model is trained on historical water level data from multiple hydrometric stations and aims to provide reliable predictions for hydrology applications, water resource management, and flood prevention.

##  Objective

To investigate the performance of a simple MLP neural network in forecasting water levels at the **Mercedes** station, using past water level data from surrounding stations within the basin.

## Methodology

- **Model**: Multilayer Perceptron (MLP)
- **Input**: 18 numerical features representing water levels at various stations (excluding `Villa_Soriano_level`)
- **Output**: Predicted water level at `Mercedes_level`
- **Preprocessing**: Data normalization and train/test split (20% of the latest values used for testing)
- **Evaluation**: Metrics include Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and visual comparisons

## Repository Structure

```
MLP-Approach-for-Predicting-Water-Level-in-the-Rio-Negro-Basin/
│
├── MLP_Approach_for_Predicting_Water_Level_in_the_Rio_Negro_Basin_.ipynb  # Main implementation notebook
├── README.md                                                               # This file
└── data/                                                                   # (Optional) Folder for local data files
```

## Expected Results

- Accurate forecasts of `Mercedes_level` water levels
- Performance evaluation and graphical comparison between actual and predicted values
- A baseline for future comparisons with more advanced methods (e.g., PINNs or hydrodynamic models)

##  Requirements

- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `sklearn`
  - `torch`

Install dependencies using:

```bash
pip install -r requirements.txt
```

*(Note: If `requirements.txt` is missing, generate it with `pip freeze > requirements.txt` after installing the packages.)*

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Rogerio97/MLP-Approach-for-Predicting-Water-Level-in-the-Rio-Negro-Basin.git
   cd MLP-Approach-for-Predicting-Water-Level-in-the-Rio-Negro-Basin
   ```

2. Open the notebook using Jupyter or Google Colab:
   - [Open in Google Colab](https://colab.research.google.com/github/Rogerio97/MLP-Approach-for-Predicting-Water-Level-in-the-Rio-Negro-Basin/blob/main/MLP_Approach_for_Predicting_Water_Level_in_the_Rio_Negro_Basin_.ipynb)

3. Run the notebook cells sequentially.

##  Author

- **Rogério Costa de Oliveira Junior**  
  M.Sc. Applied Computer Science
  Advisors: Leonardo Bacelar Lima Santos and Rogério Galante Negri

