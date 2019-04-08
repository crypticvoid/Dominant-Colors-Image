# Dominant-Colors-Image
Dominant colors (hex code) eliminating the neutral colors (white, black and greys) using OpenCV

### 2 approaches were used :
1) The most common --> Color Histogrram 
2) K-Means color clusturing 

### Using clustering to find dominant colors in a picture

Applying k-means yields k separate clusters of the original n data points.

In this case, we will be clustering the pixel intensities of a RGB image. Given a MxN size image, we thus have MxN pixels, each consisting of three components: Red, Green, and Blue respectively.

Pixels that belong to a given cluster will be more similar in color than pixels belonging to a separate cluster.
