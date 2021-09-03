### Diabetic Retinopathy Detection

In this implementation I used the dataset available at - https://www.kaggle.com/mohammadasimbluemoon/diabeticretinopathy-messidor-eyepac-preprocessed .

Please cite these papers for the dataset usage:
1. https://jamanetwork.com/journals/jama/fullarticle/2588763
2. http://www.ias-iss.org/ojs/IAS/article/view/1155
3. https://doi.org/10.1001/jamaophthalmol.2013.1743

Diabetic Retinopathy is an eye-condition developed in patients with diabetics that gradually turn into blindness. This is a code implementation of the paper - **"Diabetic Retinopathy Detection using Texture Features and Ensemble Learning"** (Cite from here - https://doi.org/10.1109/TENSYMP50017.2020.9230600) 

**What are Texture Features?**
An image texture is a set of metrics calculated in image processing designed to quantify the perceived texture of an image. Image texture gives us information about the spatial arrangement of color or intensities in an image or selected region of an image.
Different ways are used to extract texture features from an image, to hand-craft the feature space that can be used for further analysis of an image by various algorithms. 

The dataset I used was a little different from the original mentioned one. I have only taken 360 photos of the nomral eye and 360 images of proliferative DR condition. Thus, a total of 720 images to perform binary classification. I tried to make feature extraction method as similar as possible with the information given in the paper. The results are however better due to the varying components such as dataset, feature vector length, preprocessing, etc.

