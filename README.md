# Automobile Customer Segmentation: Unsupervised Machine Learning Investigation

Dataset: Sales team at an automobile company has classified all customers into 4 segments (A, B, C, D ). A strategy of performing segmented outreach and communication has worked exceptionally well for them. 
Objective: Can an unsupervised machine learning (ML) model predict the 4 segments? or Is domain knowledge and further data required?
Approach: Took training dataset and removed A-D segmentation to review against unsupervised ML results

Summary: Conducted an exploratory data analysis and cleaned data. Regularised data using scaling or normalisation. Ran PCA of original and regularised data. Iterated Kmeans and Agglomerative clustering models for different combinations (orginal [+/- PCA], regularised [+/- PCA], in future look to implement pipeline/functions to do this). Unsupervised models successfully created a new categorisation heavily based on customer age.  Compared unsupervised models to expected A-D segmentation categories but unsupervised learning was unable to model the original categorisation, visualised by various methods.  

Tools used: Python, pandas, numpy, matplotlib, seaborn, scikitlearn, regularisation (scaling and normalization), PCA, K means clustering, Agglomerative clustering, Dendrogram

Files:

3feat_model_v_target_results.png, 8feat_model_v_target_results.png, Cluster_visualisation.png - Images to display in ipynb files

Customer Segmentation_ unsupervised learning_DBoland Feb 25.ipynb - main code*

Customer Segmentation_ unsupervised learning_DBoland Feb 25 - less features.ipynb - copy of main code, remodelled data for less features and re-ran*

Customer Segmentation_ unsupervised learning_DBoland Feb 25.pdf - Pdf of presentation of data analysis, visualisation and unsupervised ML*

Customer Segmentation_ unsupervised learning_DBoland Feb 25.pptx - Presentation of data analysis, visualisation and unsupervised ML (View raw to view online and interact with links)*

 *extra visualisations in ipynb files generated post presentation to better show reasons behind models performance
 
Dendogram_visualistion_Customer Segmentation_ unsupervised learning_DBoland Feb 25.ipynb.xlsx -  Excel table comparing row data classification to dendrograms (View raw to view online)

Train.csv - data input. 

