# Project Outline
1. Filling empty values with neighbors mean.
2. Split in windows, choose Dims and step (jump)
3. Split Train and Test
4. Feature selection
    1. RandomForest on Train
        * With error features
        * Without error features
    2. SelectKBest form SKLearn
5. Pipeline Models
    * KNeighborsTimeSeriesClassifier
    * CNN
    * LSTM
6. Model comparison
    * Learning Curve 
    * Conf Matrix -> Recall, Precision, F1 
