# Cancer-stage-prediction
Non-invasive cancer diagnosis based on liquid biopsies depending on the stage of advancement using AI

## Gdańsk University of Technology
## Research project
## 3@KAMS'2023

This solution is based on training few classification models, fine-tuning and fitting then to few subsets of preprocessed data, and hard voting using votes that maximilize validation scores.

Classifiers:
- kmeans
- SGDClassifier
- RandomForrestClassifier
- ExtraTrees
- LightGBM
  
Cndividual subsets:
a = patients + markers
b = patients + markers_scaled
c = patients + markers_scaled_pca
d = patients + markers_scaled_pca_scaled
e = patients + markers_pca
f = patients + markers_pca_scaled
