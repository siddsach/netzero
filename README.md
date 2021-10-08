# Results from analysis of cities' climate plans

## Look in notebooks for the analysis

### OCR

Contains code for running OCR libraries on PDFS to get text outputs.

### Notebooks

1. `text-preprocessing.ipynb` Run this first to get serialized features used for the  other notebooks
2. `Keyterm-based topic analysis.ipynb` uses word2vec and tfidf to construct emissions source lexicons, and uses factor analysis to show how cities are taking different climate strategies 
3. `Net Zero Ambition Regression.ipynb` uses the text features and labels from human review of which plans have a concrete goal of reaching net zero, and performs logistic regression to find significant terms that distinguish ambitious plans from non-ambitious plans
4. `similarity_valuation.ipynb` applies pairwise similarity of text features to identify how regions and coordinator networks influence climate plans' language
