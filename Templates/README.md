# Goal: create code fragments that can be used multiple times and speed up analysis.

# Explained Metrics and Models

| №   | Link       | Template description|  
| --- |:-----------------------------------------:| -------------------------:| 
|1    |[Spearman correlation](Explained\Metrics\Spearman correlation.ipynb)  |  Nonparametric measure of rank correlation (statistical dependence between the rankings of two variables)| 
|2    |[Hierachical clustering](Explained\Unsupervised learning\Hierarchical clustering.ipynb)  |  Unsupervised clustering algorithm for finding close points and dendrogram visualization | 
|3    |[Variance inflation factor](\Explained\Metrics\Variance inflation factor.ipynb)  | Shows multicolinearity (by checking if feature can be predicted by other features) | 
|4    |[Mutual information](\Explained\Metrics\Mutual information.ipynb)| Measure of dependence between two variables. Used for feature importance goals.|
|5    |[R regression (correlation coefficient)](\Explained\Metrics\R regression or correlation.ipynb)| Measure of linear dependence between feature and dependent varible.|
|6    |[F-regression](Explained\Metrics\F-regression and p-values.ipynb)| ANOVA statistic for feature importance, compares xplained variance to unexplained variance or <br> between group variability and within group variability.|
|6    |[Chi-squared](Explained\Metrics\Chi2.ipynb)| Test for significant difference between expected and observed results.|
|6    |[Gini imputiry](Explained\Metrics\Gini imputiry.ipynb)| Statistic to calculate probability of misclassifying item if it is randomly classified, used by tree models.|

|<td colspan=3><font size="24">Distribution transform: </tr>|
|7    |[Skewness](Explained\Stats\Skewness.ipynb)| Measure of symmetry of distribution|
|<td colspan=3><font size="24">Statistics: </tr>|
|8    |[Covariance matrix](Explained\Stats\Covariance matrix.ipynb)| Matrix with variance on diagonal and covariance on other places. |
|9    |[Mahalanobis distance](Explained\Stats\Mahalanobis distance.ipynb)| Distance between a vector and a matrix taking into account feature collinearity. |
|10   |[Matrix form of linear regression.](Explained\Stats\Matrix form of Linear regression.ipynb)| How to calculate coefficients by normal equation. |
|11   |[Projection or hat matrix and leverage](Explained\Stats\Projectionn or hat matrix and leverage.ipynb)| Leverage - influence of each observation on regression line. How much this observation is used when calculating <br> the regression line.|
|12   |[Studenized residuals](Explained\Stats\Studenized residuals.ipynb)| Residuals standardized by dividing by standard deviation. |
|13   |[Cooks distance](Explained\Stats\Cooks distance.ipynb)| How removing an observation changes the regression line. Counts both leverage and residual size. |

# Plots and graphics

| №   | Link       | Template description|  
| --- |:-----------------------------------------:| -------------------------:| 
|1    |[Picture of gif video](\Picture and gif\Picture or gif video.ipynb) |  Embed a picture or a gif video in your notebook | 
|2    |[Create gif](\Picture and gif\Create gif.ipynb)                     |  Create a gif image out of repeated matplotlib plots | 

# Clustering:
| №   | Link                                        | Template description|  
| --- |:-------------------------------------------:| -------------------------:| 
|<td colspan=3><font size="24">Hierarchical: </tr>|
|1    |[Hierachical clustering scipy](\Clustering\Hierarchical\Hierarchical clustering scipy.ipynb)      | Allows to find and eliminate close features.| 
|2    |[Feature agglomeration](\Clustering\Hierarchical\Feature agglomeration.ipynb) | Remove (join into centers) multicolinear features. |
|3    |[Agglomerative clustering sklearn](\Clustering\Hierarchical\Agglomerative clustering sklearn.ipynb)      | Allow to agglomerate data points into clusters.|
|<td colspan=3><font size="24">K-means: </tr>|
|1    |[K-means clustering example](\Clustering\K-means\K-means clustering.ipynb) | Mall customer clustering by K-Means, reduce distances within clusters. |
|2    |[Elbow method](\Clustering\K-means\Elbow method.ipynb)      | Allows to check how many clusters you need.|
|3    |[Find optimal number of clusters](\Clustering\K-means\Find optimal number of clusers by cross-validation.ipynb)      | Allows to find number of clusters which cleads to score increase.|


# Voting ensemble:
| №   | Link                                        | Template description|  
| --- |:-------------------------------------------:| -------------------------:| 
|1    |[Voting ensemble](VotingEnsemble.ipynb)      | A controlled ensemble for prediction and fold scores.| 
|2    |[Category ensemble](VotingEnsemble.ipynb)    | Category ensemble to check prediction accuracy for different values of a feature.| 

# Feature selection:
| №   | Link                                        | Template description|  
| --- |:-------------------------------------------:| -------------------------:| 
|<td colspan=3><font size="24">Importance based methods: </tr>|
|1    |[Random column](FeatureSelection\Importance based\Random column as feature importance indicator.ipynb) |Add a random column and calculate importances.<br> Any importances below random column should be dropped.|
|2    |[Recursive feature elimination](\FeatureSelection\Importance based\Recursive feature elimination.ipynb) | Remove features accoding to their importances. |
|3    |[Select from model](\FeatureSelection\Importance based\SelectFromModel.ipynb) | Selects features with importances larger than threshold. |
|<td colspan=3><font size="24">Scoring based methods: </tr>|
|1    |[Drop-out importance](FeatureSelection\Scoring-based\Drop-out importance.ipynb) | Remove the columns one by one and check how score decreases.|
|2    |[Permutation importance](\FeatureSelection\Scoring-based\Permutation importance.ipynb) |Randomly permutate a feature and check if the results get worse. <br> The features that decrease results the most are most important.|
|3    |[Forward selection and backward elimination](\FeatureSelection\Scoring-based\Forward selection and backward elimination SequentialFeatureSelector.ipynb) | Consequtively selects best features based on model score. |
|<td colspan=3><font size="24">Univariate based methods: </tr>|
|1    |[SelectKBest features based on univariate stats](\FeatureSelection\Univariate based\Select k best.ipynb) | Selects Best features based on univariate stats.|
|2    |[Remove features with low variance](\FeatureSelection\Univariate based\Remove features with low variance.ipynb) | Remove columns with constants or with very low variance, useless for prediction.|
|<td colspan=3><font size="24">Unsupervised methods: </tr>|
|1    |[Feature agglomeration](\Clustering\Hierarchical\Feature agglomeration.ipynb) | Remove (join into centers) multicolinear features. |
|2    |[Hierachical clustering scipy](\Clustering\Hierarchical\Hierarchical clustering scipy.ipynb) | Allows to find and eliminate close features.| 


# Multicollinearity:
| №   | Link                                        | Template description|  
| --- |:-------------------------------------------:| -------------------------:| 
|1    |[Identify multicollinearity](\Multicollinearity\Identify multicolinearity.ipynb) | Check if multicollinearity is present.|

# Distribution transform:
| №   | Link                                        | Template description|  
| --- |:-------------------------------------------:| -------------------------:| 
|1   |[Log based on skewness](\Distribution transform\Skewness.ipynb)| Find and remove skewness.|

# Outlier detection:
| №   | Link                                        | Template description|  
| --- |:-------------------------------------------:| -------------------------:| 
|1    |[PCA visual approach](\outliers\PCA visual approach.ipynb)|  Use PCA to visually identify outliers and remove them. |
|2    |[Isolation Forest](\Outliers\Isolation forest.ipynb)| Base on Extra Trees to find outliers. The less splits you need to find a point, the more probable that this is an outlier.|
|3    |[Elliptic Envelope](\Outliers\Elliptic Envelope.ipynb)| Based on Mahalanobis distances. Use robust covariance estimate (Minimum Covariance Determinant) and Mahalanobis distance to find outliers. |
|4    |[Local outlier factor](\Outliers\Local outlier factor.ipynb)| Based on neighborhood. Finds neighbor points and compares density of points in the checked point and neighbor points. |
|5    |[One class SVM](\Outliers\One class SVM.ipynb)| Based on support vector machines (SVM). Unsupervised outlier detection. |
|5    |[Univariate outlier detection](\Outliers\Univariate outlier detection.ipynb)| Based on univariate stats: boxplots, histograms, z-statistic, IQR, clustering.  |
|5    |[Handle outliers](\Outliers\Handle outliers.ipynb)| Remove, widsorize, impute mean/median. |

# Numpy:
| №   | Link                                        | Template description|  
| --- |:-------------------------------------------:| -------------------------:| 
|1   |[Meshgrid, linspace, r_, c_](\Numpy\Meshgrid linspace r c.ipynb)| Use numpy to generate coordinate grid. |

# Analyze model:
| №   | Link                                        | Template description|  
| --- |:-------------------------------------------:| -------------------------:| 
|1   |[Analyze model results by class (bin)](\Analyze model\Analyze scores by classes or bins.ipynb)| Score each class (bin) separately to get weak points understanding. |

# Feature generation:
| №   | Link                                        | Template description|  
| --- |:-------------------------------------------:| -------------------------:| 
|1    |[Transformation indicator](\Feature generation\Transformation indicator.ipynb)| Leave a feature that indicates that a value was filled, transformed, was an outlier.  |
|1    |[Categorical](C:\python\ML Course\Code templates\Feature generation\By types\Categorical features.ipynb)| Create new features out of categorical features.|
|1    |[Lists](C:\python\ML Course\Code templates\Feature generation\By types\Lists.ipynb)| TODO! Create new features out of feature of lists.|

# Feature encoding:
| №   | Link                                        | Template description|  
| --- |:-------------------------------------------:| -------------------------:| 
|1    |[Frequency encoding](C:\python\ML Course\Code templates\Feature encoding\Frequency encoding.ipynb)| Replace each categorical feature with number of times it appears in dataset. |
|1    |[Target encoding](\Feature encoding\Taget encoding or mean encoding.ipynb)| Encode the feature with mean of dependent variable. |
|1    |[One-hot encoding](\Feature encoding\One-hot encoding.ipynb)| Encode the featuers in one-hot manner, keeping column names and taking into account values of features that come only from test dataset. |
