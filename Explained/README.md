# Goal: create code fragments that can be used multiple times and speed up analysis.

# Feature selection
| №   | Link       | Template description|  
| --- |:-----------------------------------------:| -------------------------:| 
|1    |[Chi squared](FeatureSelection/Chi2.ipynb)| Test for significant difference between expected and observed results.|
|2    |[R regression](FeatureSelection/RRegressionCorrelation.ipynb)| Measure of linear dependence between feature and dependent varible.|
|3    |[F regression](FeatureSelection/FRegressionAndPvalues.ipynb)| ANOVA statistic for feature importance, compares xplained variance to unexplained variance or <br> between group variability and within group variability.|

| №   | Link       | Template description|  
| --- |:-----------------------------------------:| -------------------------:| 
|1    |[Spearman correlation](Explained\Metrics\Spearman correlation.ipynb)  |  Nonparametric measure of rank correlation (statistical dependence between the rankings of two variables)|
|3    |[Variance inflation factor](\Explained\Metrics\Variance inflation factor.ipynb)  | Shows multicolinearity (by checking if feature can be predicted by other features) |
|4    |[Mutual information](\Explained\Metrics\Mutual information.ipynb)| Measure of dependence between two variables. Used for feature importance goals.|

|6    |[Gini imputiry](Explained\Metrics\Gini imputiry.ipynb)| Statistic to calculate probability of misclassifying item if it is randomly classified, used by tree models.|
|13   |[Cooks distance](Explained\Stats\Cooks distance.ipynb)| How removing an observation changes the regression line. Counts both leverage and residual size. |


|2    |[Hierachical clustering](Explained\Unsupervised learning\Hierarchical clustering.ipynb)  |  Unsupervised clustering algorithm for finding close points and dendrogram visualization | 
|<td colspan=3><font size="24">Distribution transform: </tr>|
|7    |[Skewness](Explained\Stats\Skewness.ipynb)| Measure of symmetry of distribution|
|<td colspan=3><font size="24">Statistics: </tr>|
|8    |[Covariance matrix](Explained\Stats\Covariance matrix.ipynb)| Matrix with variance on diagonal and covariance on other places. |
|9    |[Mahalanobis distance](Explained\Stats\Mahalanobis distance.ipynb)| Distance between a vector and a matrix taking into account feature collinearity. |
|10   |[Matrix form of linear regression.](Explained\Stats\Matrix form of Linear regression.ipynb)| How to calculate coefficients by normal equation. |
|11   |[Projection or hat matrix and leverage](Explained\Stats\Projectionn or hat matrix and leverage.ipynb)| Leverage - influence of each observation on regression line. How much this observation is used when calculating <br> the regression line.|
|12   |[Studenized residuals](Explained\Stats\Studenized residuals.ipynb)| Residuals standardized by dividing by standard deviation. |
