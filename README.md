# Classification and Clustering of Dry Grains

Grain classification is an important task for selective cultivation and marketing. This task can be automated using Computer Vision and Machine Learning techniques. In this work, several classification models such as SVM, MLP, XGB and KNN are applied and compared to determine which type of classifier is the best to perform this task. On the other hand, clustering models such as AC, K-means and HDBSCAN are applied and compared to determine which method allows finding groupings that are as close as possible to the real classification of the grains. The main results are that SVM is the most appropriate classifier for this problem and that of the clustering methods analyzed none is close enough to the real classification of the grains.

The pdf file "DryBeansClassification.pdf" is the paper that explains in more detail all the procedure and results, a translation of this paper to English is pending.

## Important

In this directory there are 3 Jupyter notebooks where there are several phases of the research process of "Classification and Clustering of Dry Grains".

In "clasificacion.ipynb" -> there is the pre-processing of the dataset used, the validation techniques used, the training of the various ML models, the metrics resulting from each of these and the pairwise tests of McNemar and t -test carried out to find the best model.

In "prueba_mejora_clasificacion_reduccion_dimensiones.ipynb" -> There is an attempt to improve the best model found in the previous notebook through the application of several dimension reduction techniques. In addition, there are McNemar tests to determine if there is an improvement when applying them.

In "clusterización.ipynb" -> there is the application of several clustering algorithms on the unaltered dataset and on the dataset transformed by various dimension reduction techniques. The Adjusted Rand Index is obtained for each clusterization and each cluster is visualized in a two-dimensional graph thanks to the same dimension reduction techniques.


## Acknowledgements (Dataset):

KOKLU, M. and OZKAN, I.A., (2020), “Multiclass Classification of Dry Beans Using Computer Vision and Machine Learning Techniques.” Computers and Electronics in Agriculture, 174, 105507.
DOI: https://doi.org/10.1016/j.compag.2020.105507


