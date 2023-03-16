# ML_UMAP_PHATE
A simple jupyter notebook implementing multivariable regression/ XGBoost regression + classification and dimensionality reduction on single-cell data in python

In this example, I have >8000 single cells with 7 variables extracted from 4 days of continuous live-cell imaging followed by subsequent multiplexed immunofluorecence staining. One of these variables is the duration spent withdrawn from the cell cycle throughout the course of live-cell imaging, which is used as the response variable for regression modeling. Furthermore, I implemented two dimensionality reduction approaches (UMAP and PHATE) to see how the cells clustered by cell-cycle fate.

Preview: PHATE (colored by cell fate)

![download](https://user-images.githubusercontent.com/121640997/225477340-5d376c7d-61a2-413a-827a-3e404130fd3b.png)
