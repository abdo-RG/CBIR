# CBIR

We've developed this software using Python, OpenCV, numpy, scipy, and other libraries. The system allows you to index a database of images in a JSON table that contains description of each image in different features spaces, and then make queries using images as query elements. It then computes the similarity between the images in the database and the query image, returning the best matches.

The user can choose between a range of feature vectors to compare images such as color (RGB, HSV, YCrCb), texture (LBP, LBQ, GLCM) or shape (LoG, Sobel, Hu), with customizable ponderation.

We also conducted an experimental study to figure out which of the 4 metrics (Euclidian distance, Chebychev distance, Hamiltonian distance, and cosine distance) is the best in terms of accuracy and found that Cosine distance gives the best results.
