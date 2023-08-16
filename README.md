# Evaluating the Performance of Multivariate Imputation by Chained Equations (MICE) when Predicting Missing Well-Log Data in Sedimentary Basins

## Abstract
This research evaluates the applicability of Multivariate Imputation by Chained Equations (MICE) for 
estimating missing well-log data across different sedimentary basins. By utilizing various machine learning 
techniques, including XGBoost (XGB), Random Forest (RF), K-Nearest Neighbors (KNR), and Bayesian Ridge (BR),
the performance of MICE was tested across three different datasets from distinct geological contexts with
minimal user input. 

**Key Findings**:
- The performance of MICE varied across datasets and well-logs due to the complexity of imputing missing data in heterogeneous sedimentary basins.
- The number of MICE iterations did not significantly impact the models' performance.
- Data quality, preprocessing, and geological complexities were significant determinants of imputation performance.
- The Force-200 dataset showed better imputation performance compared to the Montney and Beetaloo datasets.
- XGBoost (XGB) generally outperformed other algorithms.

The study concludes that there's a pressing need for more research to:
1. Minimize user input in the imputation process.
2. Develop more robust and adaptable models.
3. Refine preprocessing techniques and explore further combinations of well-logs.
4. Evolve cross-validation approaches that mimic real-world scenarios.

## Repository Structure
The repository is organized into three main folders corresponding to each dataset: 
1. **Montney**
2. **Beetaloo**
3. **Force-200**

**Inside each dataset folder, you will find**:
- **Notebooks** for exploratory data analysis.
- Notebooks used to evaluate the MICE model performance with 1, 10, and 20 iterations.
- Sensitivity analysis notebooks for both Random Forest (RF) and XGBoost (XGB).

**Results Folder**:
- Contains notebooks detailing the results of this study.

For a comprehensive understanding and in-depth information, please refer to the detailed report available at TUDelft: [https://repository.tudelft.nl/] TUDelft Repositories
