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
3. Explore preprocessing techniques and more well log combinations.
4. Develop cross-validation approaches that mimic real-world scenarios, intervals with missing values and entire logs with missing values.

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

## References

1. Hallam, A., Mukherjee, D., & Chassagne, R. (2022). Multivariate imputation via chained equations for elastic well log imputation and prediction. *Applied Computing and Geosciences*, 14. [doi:https://doi.org/10.1016/j.acags.2022.100083](https://doi.org/10.1016/j.acags.2022.100083).
   
2. Feng, R., Grana, D., & Balling, N. (2021). Imputation of missing well log data by random forest and its uncertainty analysis. *Computers & Geosciences*, 152. [doi:https://doi.org/10.1016/j.cageo.2021.104763](https://doi.org/10.1016/j.cageo.2021.104763).

3. Lopes, R. L., & Jorge, A. M. (2018). Assessment of predictive learning methods for the completion of gaps in well log data. *Journal of Petroleum Science and Engineering*. [doi:https://doi.org/10.1016/j.petrol.2017.11.019](https://doi.org/10.1016/j.petrol.2017.11.019).

4. Dixneuf, P., Errico, F., & Glaus, M. (2021). A computational study on imputation methods for missing environmental data. arXiv. [doi:https://doi.org/10.48550/arXiv.2108.09500](https://doi.org/10.48550/arXiv.2108.09500).

For a comprehensive understanding and more information, please refer to the detailed report available at TUDelft: [TUDelft Repositories](https://repository.tudelft.nl/).
