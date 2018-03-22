# Question-Classification
Classifying questions from UIUC's CogComp QC Dataset

# Classifying Questions into Coarse (6 classes) and Fine (50 classes) classes.

# Approach
1. Text Exploration
2. Text Cleaning
3. Obtaing POS Tags, Identifying Named Entities, Lemmas, Syntactic Dependency Relations and Orthographic Features.
4. Using the obtained properties as Features.
5. Using a Linear SVM model on the engineered features.

# Results
* 88.2% accuracy on Coarse classes.
* 81.6% accuracy on Fine classes.

| Variations in Features Used  | Coarse Set Accuracy | Coarse:Fine Set Accuracy | Fine Set Accuracy |
| ------------- | ------------- | ------------- | ------------- |
| Named Entity Recognition + Lemmas + POS Tags + Syntactic Dependency + Shape | 87.8 | 80.4 | 80.8 |
| Named Entity Recognition + Lemmas + POS Tags + Syntactic Dependency | 87.2 | 80.6 | 81.4 |
| Named Entity Recognition + Lemmas + POS Tags | **88.2** | **81.4** | 81.2 |
| Named Entity Recognition + Lemmas | 86.4 | 80.6 | **81.6** |
| Lemmas | 86.2 | 80.4 | **81.6** |

# References
https://nlp.stanford.edu/courses/cs224n/2010/reports/olalerew.pdf
