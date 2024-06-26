# Credit Risk PD Modelization

This repository contains a Jupyter Notebook for performing credit risk Probability of Default (PD) modelization. The model utilizes the `optbinning` library for optimal binning and employs the Information Value (IV) and Weight of Evidence (WoE) approach for binning and feature selection.

## Repository Contents

- `credit_risk_pd_modelization.ipynb`: The main Jupyter Notebook containing the entire workflow for credit risk PD modelization.
- `data/`: Directory where you can place your dataset(s).
- `results/`: Directory to store results such as figures, tables, and model outputs.
- `requirements.txt`: List of required Python libraries for running the notebook.

## Key Features

1. **Optimal Binning with `optbinning`**: The notebook demonstrates how to use the `optbinning` library to perform optimal binning of continuous variables.
2. **Information Value (IV) Calculation**: Calculation of IV for feature selection, helping to identify the predictive power of each variable.
3. **Weight of Evidence (WoE) Transformation**: Transformation of categorical and continuous variables using WoE, which is beneficial for logistic regression modeling.
4. **Feature Selection**: Based on IV values, features are selected to build a robust credit risk PD model.
5. **Model Building and Evaluation**: Building a logistic regression model for PD prediction and evaluating its performance.

## Setup Instructions

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/credit_risk_pd_modelization.git
    cd credit_risk_pd_modelization
    ```

2. **Install Dependencies**:
    It is recommended to create a virtual environment before installing the dependencies.
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```
    Open `CreditRisk.ipynb` in the Jupyter interface to explore the workflow.

## Data

Place your dataset(s) in the `data/` directory. Ensure that the data is properly formatted and preprocessed before running the notebook.

## Usage

Follow the steps in the notebook to:

1. Load and preprocess the data.
2. Perform optimal binning using the `optbinning` library.
3. Calculate IV for feature selection.
4. Transform features using WoE.
5. Build and evaluate a logistic regression model.

## References

- [optbinning Documentation](https://gnpalencia.org/optbinning/)
- [Information Value and Weight of Evidence](https://en.wikipedia.org/wiki/Weight_of_evidence)

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any questions or issues, please open an issue in the repository or contact [esteban.braganza@gmail.com](mailto:esteban.braganza@gmail.com).

