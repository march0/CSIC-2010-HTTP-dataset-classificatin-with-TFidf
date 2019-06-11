# CSIC-2010-HTTP-dataset-classificatin-with-TFidf

## TFidf features

**Normal request top features**

![Normal request](./figs/normal.png)

**Anomalous request top features**

![Anomalous request](./figs/anomalous.png)

## Results with a Linear SVM
ROC-AUC score : 0.9333679153693484

Confusion Matrix: 

|    |    | 
|----|----|
|3652|30  | 
| 403|2818|

### Requirements
```
numpy==1.16.2
matplotlib==3.0.3
pandas==0.24.2
scikit_learn==0.21.2
```

## Reference
1) https://github.com/Monkey-D-Groot/Machine-Learning-on-CSIC-2010 (took some ideas about parsing)

2) https://buhrmann.github.io/tfidf-analysis.html (plot function for TFidf)
