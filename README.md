# WiDS Data Science Competition
## This is a modeling project focused on predicting ADHD diagnosis. <br>

Welcome! The results can be viewed through the preview settings of the python code. <br>
One of the challenges of this classfication problem is that there are less behavior indicators (Variables begining in SDQ) in women then there are for men. The Kaggle challenge asked contestants to use the training data to predict ADHD for men and women (without gender specified) which makes it difficult to distinguish men without ADHD from women with ADHD and predict the patient's correct diagnosis. 

<br> Other difficulties included: the data set was also imbalanced with little diversity in the demographics, contained missingness in the training data that was not present in the testing, and had values change for certain features like Demos Site Location. A seperate challenge is extrapolation, where the training data is for years 2015-2020 but the testing years are 2021-2023 and variables shift due to time passing requiring the models to predict based off changing feature values. 
