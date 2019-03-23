# W207 Final Project Anup Jha and Anish Phillip

## Members
* Anup Jha
* Anish Phillip
## Project Title 
Facial Key Point Detection

## Description
* The objective of this project is to identify the location of facial keypoints on the images of face  
* There are 15 keypoints on the face such as :
- left_eye_center
- right_eye_cente
- left_eye_inner_corner
- left_eye_outer_corner
- right_eye_inner_corner
- right_eye_outer_corner
- left_eyebrow_inner_end
- left_eyebrow_outer_end_
- right_eyebrow_inner_end
- right_eyebrow_outer_end
- nose_tip
- mouth_left_corner
- mouth_right_corne
- mouth_center_top_lip
- mouth_center_bottom_lip
* Each of the feature has X and Y co-ordinates 
* The image itself is 96 X 96 grayscale image 
 
## Features Available 
* The value of 9216 pixels of the image are available for each training example 
* The values of pixels vary from 0 to 255 

## Feature Engineering 
We intend to do the following feature engineering to make the predictions accurate
 * Normalization of the pixel values to be scaled between 0 and 1 
 * Since we plan to use the neural nets for the predictions we don't focus much on feature engineering

## Expected Outcome
  * We plan to create a model which can predict the location of the key features in terms of pixel position 
  * The model will be fed a gray scale image of face of size 96X96 

7. Run preliminary likelihoods for data already present to include prior scores

## Algorithms    
  *  We plan to use :
    - Fully connected neural network 
    - Convolutional neural network 

9. Try using a baseline approach first and base your improvement on it (look into ZeroR rule)
    
## Data Set 
  * For the training set we have 7049 example rows but only 2140 examples have all the facial key points 
  * We have test set set with 1783 images of 96X96 pixel images
  * The training set has 7049 X 31 shape
  * The last column has 
10. How many observations do you have and what do they look like (describe it)?
    11. What hyper parameters would you consider changing and what you achieve with each?
    12. Would you consider using dimension reduction and if so, why? What kind?
    13. Prepare 6-8 min presentation for each group
    14. Anything else that you think is important to put in writing and discuss

