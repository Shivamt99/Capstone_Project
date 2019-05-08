# Capstone_Project
Final Capstone Project

## WHO LET THE DOG'S OUT?


# Objective

This project hopes to identify dog breeds from images. This is a fine-grained classification problem: all breeds of Canis lupus familiaris share similar body features and over-all structure, so differentiating between breeds is a difficult problem. Furthermore, there is low inter-breed and high intra-breed variation; in other words, there are relatively few differences between breeds and relatively large differences within breeds, differing in size, shape, and color.  In fact, dogs are both the most morphologically and genetically diverse species on Earth. The difficulties of identifying breeds because of diversity are compounded by the stylistic differences of photographs used in the dataset, which features dogs of the same breed in a variety of lightings and positions.



# Data Info

The Stanford Dogs dataset contains images of 120 breeds of dogs from around the world. This dataset has been built using images and annotation from ImageNet for the task of fine-grained image categorization. Contents of this dataset: 
•	Number of categories: 120
•	Number of images: 20,580
•	Annotations: Class labels, Bounding boxes
Source Link: http://vision.stanford.edu/aditya86/ImageNetDogs/main.html


# Files

Path_setup_Preprocessing.ipynb - Set directory and preprocess the data

CNN_scratch - CNN architecture built from scratch

VGG_16_Transfer_Learning - Implementation of transfer learning
