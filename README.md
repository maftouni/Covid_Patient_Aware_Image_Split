# Patient_Aware_Image_Split
This repository splits a sample Covid/Normal classification dataset into validation and training sets in a patient aware manner. It is important not to split images of the same patient between the sets (to avoid overfitting); therefore, we have used meta-data file to group the images based on Patient-ID first. 