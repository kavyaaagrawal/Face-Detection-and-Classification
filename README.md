# Face-Detection-and-Features-Classification

### AIM of the lab:
###### The aim of the lab is to detect faces in a group image. We extract color based features like hue and saturation from the detected faces. To visualise clustering results with centroids and feature scatter plots.

### Methodology:
###### 1. Face detection
###### 2. Feature extraction from the faces
###### 3. K-Means clustering
###### 4. Visualisation 
###### 5. Template face classification
###### 6. Plotting template face on the same feature graph

### KEY FINDINGS
###### Faces can be grouped using only simple color statistics.
###### Even without deep learning, basic clustering can separate faces based on skin tone, lighting conditions and background influence
###### K-means is sensitive to initial centroids, feature scaling and choice of K 
###### Cluster numbering (0 or 1) has no inherent meaning.
###### Fixing random_state ensures reproducibility.

### OBSERVATIONS
###### Total detected faces ≈ 30.
###### One cluster had significantly more samples.
###### Template face was classified consistently into one cluster.
###### Clear separation observed in Hue space.

### CONCLUSIONS
###### Face detection + simple color features can be used for unsupervised grouping.
###### K-Means successfully divided faces into two clusters based on color characteristics.
###### The method is simple, computationally light and interpretable
###### However, clustering based only on Hue and Saturation does not identify individuals, perform identity recognition and does not identify only groups based on color similarity
