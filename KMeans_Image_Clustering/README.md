# Image Clustering using K-Means on MNIST Dataset

## Objective
Apply unsupervised learning to handwritten digit images by using the K-Means clustering algorithm to group similar images and analyze the formed clusters.

## Dataset
- Dataset: MNIST Handwritten Digit Dataset
- Contains grayscale images of handwritten digits (0–9)
- Images: 28 × 28 pixels
- Total classes: 10 digits
- Each image is flattened into a 784-dimensional feature vector before clustering

## Steps
1. Load and explore the MNIST dataset
2. Preprocess images by flattening 28×28 pixel images into feature vectors
3. Apply K-Means clustering with 10 clusters
4. Assign images to clusters based on similarity using Euclidean distance
5. Map generated clusters with actual digit labels to estimate clustering accuracy
6. Visualize cluster centroids to understand learned digit patterns
7. Interpret the quality and limitations of the generated clusters

## Results
- Successfully grouped handwritten digit images using an unsupervised learning approach
- Estimated clustering accuracy by comparing cluster assignments with true digit labels
- Visualized cluster centroids representing the average pattern of each group
- Identified similarities and overlaps between visually similar digits

## Skills Demonstrated
- Unsupervised learning using K-Means clustering
- Image preprocessing and feature extraction
- Working with high-dimensional image data
- Cluster evaluation and accuracy estimation
- Data visualization and interpretation of machine learning results
