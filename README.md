# Computer-Vision

Image registration technique: 

Given two images; image1 and image2, the aim is to register image2 with respect to image1. 
The registration problem has to be solved by matching SIFT features extracted from the images.
Inputs: Given images, image1 and image2.
Output: image2 transformed with respect to image1 such that the difference between two images is minimum.
Tasks to be accomplished:
1. Extract SIFT features from images using a function from OpenCV library or any other library.
2. Match features using naive nearest neighbor approach (function to be implemented) and the second version of nearest neighbor approach - cv2.BFMatcher().
3. Compute the transformation matrix (affine transformation).
4. Transform image2 such that it aligns with image1.
5. Compute registration error for both feature matching methods.

Image Thresholding Techniques:

A.  Write a program to implement the Otsu's adaptive thresholding technique. Obtain the 
optimum threshold for segmenting the region of interest (dark object region with respect to a 
bright background) and create a binary image. Test and evaluate the algorithm on sample 
images of different types (single object, multiple objects, different lighting and backgrounds 
etc., see Project-Data)

B.  Write a program to implement the adaptive progressive thresholding (APT) technique. 
Obtain the optimum final threshold for segmenting the region of interest (dark object region 
with respect to a bright background) and create a binary image. Test and evaluate the 
algorithm on sample images of different types (single object, multiple objects, different 
lighting and backgrounds etc., see Project-Data)
