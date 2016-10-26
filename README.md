# academic-social-tagging-data-cleaning-and-outlier-detection

Supplementary materials in the paper "Hierarchical Clustering-Based Outlier Detection
from Academic Social Tagging Data", submitted to PAKDD 2017.

Authors: Hang Dong, Wei Wang and Frans Coenen
From Xi'an Jiaotong-Liverpool University and the University of Liverpool.

This folder contains 7 materials/files: 

Material 1 The semantic assumptions and treatment for all special characters with real tag examples in Bibsonomy (referenced in “Handling special characters semantically” in Sect. 3 in the paper).

Material 2-3 The full cleaned dataset from Bibsonomy data after Step 4 (referenced in Table 1 in the paper) containing 2502 multiword tag groups (Material 2) and 14,877 single tag groups (Material 3).

Material 4 The reduced dataset after Step 5 (referenced in Table 1 in the paper) by selecting only tag groups annotated to publications, containing 15,647 multiword and single tag groups.

Material 5 (svd-2000) The SVD-reduced matrix (15,647*2000) created from Material 4, using the binary resource-based representation method, where each row vector corresponds to a tag group and each entry in the row vector corresponds to whether tags in the tag group were used to annotate a resource (if yes then 1, no then 0). The dimension of the matrix is reduced from 301,669 (number of distinct resources after Step 5 in Table 1 in the paper) to 2000 using SVD, with around 80% of eigencomponents retained. All row vectors in Material 5 correspond to the tag groups of the same rows in Material 4.

Material 6 The clustering results and candidate outliers with data from Material 4 represented using a binary resource-based matrix reduced to 2000 dimensions after Singular Value Decomposition.

Material 7 The candidate outliers per clustering technique (Sheet 1 from Columns A to O), distinct candidate outliers from all clustering techniques (Sheet 1 Column P), human evaluation results (Sheet 1 Columns Q to W); and precision, recall, F-measure for each clustering technique (Sheets 2 to 4). 

More notes are in the file "Supplementary Materials_Hierarchical Clustering-Based Outlier Detection from Academic Social Tagging.doc"
