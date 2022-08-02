# Object_Dectecion_and_classification_using_satellite_imagery

This project aims at working with satellite images and classifying them based on multiple classes such as Farms, Forests, Crops and Urban Areas. 

Two data-sets for the project were extracted from Sentinel Hub (open source for Satellite Image extraction) and Planet Scope, which are the designer and builder of the world’s largest constellation of Earth-imaging satellites. Area of the study was considered as Chatbir, Punjab and images were taken of Sentinel-2 L2A satellite with 10m spatial and Planet Scope with 1.5m resolution for the year 2018 to 2021 excluding cloudy images. 

We have applied machine learning algorithms such as SVM, Random forest, XGboost, Gradient Boosting, KNN and Deep Learning algorithm (CNN-1D) for crop, Farm,
Forest, Urban area classification. Multiple experiments with different combinations of feature sets as different vegetation indices were carried out to build a better model. The results showed that the augment of multi-spectral information of Sentinel-2 improved the accuracy of different class classification remarkably in Deep learning algorithm (CNN-1D), and the improvement was firmly related to strategies of feature selections and data cleaning. Compared with other
indexes, NDVI index showed a higher competence in classification. 

The combined application of images of a year is significant for achieving optimal performance. A relatively accurate classification (overall accuracy = 0.95) was obtained by giving NDVI as a feature on the yearly data on CNN 1D model. Our resluts shows that planet scope data is giving low misclassification and higher accuracy scores than sentinel hub, because planet scope has higher (1.5m spatial resolution) compared to sentinel hub. 

This study gave an inspiration in selecting targeted indexes and period of images for acquiring more accurate and timelier crop and land classification. The proposed method could be transferred to larger areas as well to see the different classification for better learning.
