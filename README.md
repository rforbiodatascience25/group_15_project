# Group 15: Chronic Kidney Disease project

This is the final project for the course "R for bio data science" at DTU, autumn semester of 2025.

**Members:**

-   Palliotto Giosuè (s253716)

-   Palova Zoja (s225185)

-   Pålsson Joel Sebastian (s253731)

-   Humaira Amin (s235423)

-   Anas Majed El-Youssef (s233381)

## Data and aim

Information and link to the data can be found here: <https://www.kaggle.com/datasets/mansoordaku/ckdisease>

Downloading from above requires a Kaggle account. The data is also available here without an account: <https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease>

The data was collected over 2 months in India, and includes a set of 25 physiological features of the individuals, as well as information on whether the individual has chronic kidney disease ("classification" in the original data).

In this project, we aim to identify if any of these 25 physiological features are correlated with and can predict the presence of chronic kidney disease in an individual.

## How to run

The rendered .qmd files can all be found as html documents in the results folder, as well as a selection of graphs from the analysis. To render the project yourself, do the following:

1.  Download the data from Kaggle (requires account), or from UV Irvine archive (no account needed).
2.  Unzip the data and save the .`csv` in a new folder called `_raw` in the repository.
3.  Run `00_all.qmd`
4.  The html files will be rendered into the `results` folder

## Sources

### **Data**:

Chronic KIdney Disease dataset. Kaggle.com. Available: <https://www.kaggle.com/datasets/mansoordaku/ckdisease/data>

### **Packages**:

A.C. (Fortran, port), A.L. (R, and port), M.W. (R (2024). randomForest: Breiman and Cutlers Random Forests for Classification and Regression.

Peterson, B.G., Carl, P., Boudt, K., Bennett, R., Ulrich, J., Zivot, E., Cornilly, D., Hung, E., Lestel, M., Balkissoon, K., et al. (2024). PerformanceAnalytics: Econometric Tools for Performance and Risk Analysis.

Wickham, H., Averick, M., Bryan, J., Chang, W., McGowan, L.D., François, R., Grolemund, G., Hayes, A., Henry, L., Hester, J., et al. (2019). Welcome to the Tidyverse. Journal of Open Source Software *4*, 1686. <https://doi.org/10.21105/joss.01686>.

### **Miscellaneous**:

CKD-EPI Creatinine Equation (2021) \| National Kidney Foundation.

Kaufman, D.P., Basit, H., and Knohl, S.J. (2025). Physiology, Glomerular Filtration Rate. In StatPearls, (Treasure Island (FL): StatPearls Publishing), p.
