# Machine Learning-Based Hardness Prediction of Refractory High-Entropy Alloys

## Overview

This repository contains the machine learning implementations and dataset used to predict the hardness of refractory high-entropy alloys (RHEAs) using alloy composition data collected from the scientific literature.

Four machine learning algorithms—Extreme Gradient Boosting (XGBoost), Random Forest (RF), Support Vector Regression (SVR), and Multilayer Perceptron (MLP)—were developed and evaluated to investigate their applicability to hardness prediction.

This work explores the use of data-driven modelling to establish relationships between alloy composition and hardness, supporting the screening and design of advanced materials.

## Project Objectives

- Develop machine learning models for predicting the hardness of refractory high-entropy alloys.
- Investigate the relationship between alloy composition and hardness.
- Compare the predictive performance of four machine learning algorithms.
- Explore the potential of machine learning for data-driven materials screening.

## Dataset

The dataset comprises **86 alloy-composition samples** collected from the scientific literature for machine learning-based hardness prediction.

- **Input:** Alloy composition.
- **Target property:** Hardness.
- **Data source:** Published scientific literature.

The dataset provided in this repository is intended to support the modelling work described in the associated research.

## Machine Learning Algorithms

The following algorithms were implemented:

1. **Extreme Gradient Boosting (XGBoost)**
2. **Random Forest (RF)**
3. **Support Vector Regression (SVR)**
4. **Multilayer Perceptron (MLP)**

The implementations and corresponding evaluation procedures are available in the uploaded code files.

## Repository Contents

This repository contains the dataset used for the analysis and the code files implementing the four machine learning models.

The individual files provide the model implementations and supporting materials required to reproduce the analysis.

## Installation and Requirements

The project uses Python and Jupyter Notebook to run the machine learning implementations.

The required Python packages may include:

- NumPy
- pandas
- Matplotlib
- scikit-learn
- XGBoost
- openpyxl, if Excel files are used

Install Jupyter Notebook and the required packages using pip:

```bash
python -m pip install notebook numpy pandas matplotlib scikit-learn xgboost openpyxl
```

Additional packages may be required depending on the imports used in the individual notebooks.

## Usage

1. Clone or download this repository.
2. Install the required Python packages.
3. Open a terminal or command prompt in the repository directory.
4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the notebook corresponding to the required machine learning model.
6. Ensure the dataset path specified in the notebook matches the location of the dataset file.
7. Run the notebook cells sequentially to execute the implementation.

## Methodology and Results

The modelling methodology, evaluation procedures, performance metrics, and detailed findings are presented in the associated research paper and implemented in the corresponding code files.

For a comprehensive understanding of the modelling approach and results, readers are encouraged to consult the associated publication.

## Reproducibility

The code and dataset are shared to support transparency and reproducibility in machine learning-based materials research. Reproducing the results requires using the appropriate dataset, software dependencies, and model settings specified in the code.

## Citation

The dataset used in this study was collected from the published literature. The original source of the data is acknowledged through the following reference : A. Detor, S. Oppenheimer, R. Casey, and C. Crawford, “Refractory high entropy alloy dataset with room temperature ductility screening,” Data Brief, vol. 45, p. 108582, Dec. 2022, doi: 10.1016/j.dib.2022.108582.

## Contact

For questions about the code or dataset, please contact the repository owner through GitHub.
