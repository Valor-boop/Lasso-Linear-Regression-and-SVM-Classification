# Lasso-Linear-Regression-and-SVM-Classification
The first objective was to compare the results of Lasso and Ordinary Least Squares
(OLS) when predicting commodity values. Through this, the commodity that best reflects the broad
market and the minimum number of commodities to track can be determined for amazing.inc. The
second objective was to use an SVM with an unscaled Gaussian kernel to classify non-linearly
separable data. Lasso and OLS were implemented on a dataset provided by the U.S Federal
Reserve Bank of St. Louis Economic Data (FRED) website. Both methods were used to predict the
value of the ‘Lead’ commodity and had their predicted values graphed compared to the actual
values. Before applying the SVM with a Gaussian kernel, the data set needed to be dimensionally
reduced to a 2 dimensional set. Once reduced the data set was run through the SVM and the values
were classified. By observing Figure 3, it is apparent that Lasso was able to better predict the
‘Lead’ commodity values compared to OLS due to OLS’s susceptibility to outliers. As well Figure 2
shows that the commodity that best represents the broad market is B2: ‘Copper’ as it is non zero at
the highest lambda value. Figure 2 also shows that the minimum number of commodities to track is
6 (B1: ‘Coal’, B4: ‘Fish meal’, B6: ‘Hides’, B12: ‘Tin’, B13: ‘Uranium’, and B15: ‘Zinc’) as these
variables have a non-zero value at the minimum MSE lambda. By observing Figure 4, it can be seen
that applying an SVM with an unscaled Gaussian kernel was able to achieve an accuracy of 100%
when classifying the non-linearly separable data. Overall Lasso proved to be a more effective
prediction method compared to OLS as it generated a more general solution that was less affected
by outliers at a lower computational cost. As well, SVM with an unscaled Gaussian kernel was an
effective classification tool when dealing with non-linearly separable data.
