# Reflection Suppression

This is the code repository for our Convex Optimization (CSE203B) project titled "Ghosting Regularizers for Single Image Reflection Suppression".

#### Code organization

* Closed form solution [1] reimplemented in Python - [notebook](reflection_suppression_closedform.ipynb)
* Iterative solution without regularizer - [notebook](reflection_supp_iterative.ipynb)
* Iterative solution with regularizer [2] (analytically derived gradient) - [notebook](regularizer_iterative.ipynb)
* Synthetic data generation for evaluation - [notebook](datasetGeneration.ipynb)


#### References
* [1] Yang et al., "Fast Single Image Reflection Suppression via Convex Optimization", CVPR19
* [2] Huang et al., "Removing reflection from a single image with ghosting effect", IEEE Transactions on Computational Imaging, 2019
