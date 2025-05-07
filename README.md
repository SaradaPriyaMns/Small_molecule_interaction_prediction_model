# kaggle-Competition
# Kaggle Leash-BELKA Competition Submission
# Small molecule interaction prediction model

## Description
This repository contains my submission for the [Kaggle Leash-BELKA competition](https://www.kaggle.com/competitions/leash-BELKA). The objective of the competition is to predict molecular properties based on the given dataset.

## Project Structure
- **molecule-properties-model.ipynb**: Jupyter notebook containing the data analysis, feature extraction, and model training processes.

## Methodology
1. **Data Processing**: Utilizes libraries such as Pandas and RDKit for handling and analyzing molecular data.
2. **Feature Engineering**: Generates molecular descriptors to use as features in the model.
3. **Modeling**: Implements the CatBoost classifier for predicting molecular properties based on the generated features.

## Results
The notebook is structured to demonstrate the process of loading data, preprocessing, and training the model. Please refer to the notebook for detailed outputs and evaluations.

## How to Use
1. Clone this repository.
2. Install the required dependencies using:
   ```bash
   pip install schrodinger openbabel rdkit joblib
   ```

3.Open the Jupyter notebook and run the analyses:
```bash
jupyter notebook molecule-properties-model.ipynb
```
