# ML_UMAP_PHATE
A simple jupyter notebook implementing multivariable regression/ XGBoost regression + classification and dimensionality reduction on single-cell data in python

In this example, I have >8000 single cells with 7 variables extracted from 4 days of continuous live-cell imaging followed by subsequent multiplexed immunofluorecence staining. One of these variables is the duration spent withdrawn from the cell cycle throughout the course of live-cell imaging, which is used as the predictor variable for multivariable regression modeling. Furthermore, I implemented two dimensionality reduction approaches (UMAP and PHATE) to see how the cells clustered by cell-cycle fate.
