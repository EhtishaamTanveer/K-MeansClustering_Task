# Applying K-means Clustering Algorithm for Image Compression

### Description

This repository explores the application of the K-means clustering algorithm for image compression. It aims to significantly reduce image file size while maintaining a visually acceptable representation. First, we notice that I have applied K-means to a random dataset to show how the clustering works and why the choice of number of centroids is important. Then, I will move on to the Image Compression application.

I started working on this project all by myself while completing my Coursera specialization called "[Machine Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/NG3GPTVN7M8E?utm_source=link&utm_medium=certificate&utm_content=cert_image&utm_campaign=sharing_cta&utm_product=s12n)"

### Key Features

- K-Means Clustering Implementation: Leverages K-means to group pixels with similar color values, resulting in a smaller color palette.
- Reduced File Size: Achieves significant file size reduction compared to uncompressed images.

### How K-means works?

1. Deciding how many centroid points you need around the data.
2. Computing the mean of each centroid.
3. Assigning each example in the dataset to its closest centroid according to mean.
4. Finally, recomputing the mean of each centroid and assigning only the closest points to it (with minimum distance)

### Benefits

- Faster Transmission: Compressed images download and upload faster, enhancing web performance and user experience.
- Storage Optimization: Efficiently store large image collections by reducing their overall footprint.
- Scalability: The K-means approach can be applied to images of various sizes and formats.
