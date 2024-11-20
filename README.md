# FaceFit-MachineLearning
##  FaceFit  - Suitable Glasses, Charming Face (Team CH2-PS497) 
- Machine Learning Repository

FaceFit Machine Learning Repository for Bangkit Capstone Project. Building face shape classifier Model.
## The Trainee of Machine Learning Bangkit Academy Capstone Team CH2-PS497

| Trainee                      | Student ID    | Learning Path     | University                |
|------------------------------|---------------|-------------------|---------------------------|
| Nicolas Ray Amarco Tambunan  | M312B4KY3363  | Machine Learning  | Universitas Sebelas Maret |
| Vitto Rendi Setiawan         | M312B4KY4442  | Machine Learning  | Universitas Sebelas Maret |
| Zhafira Oktaviani            | M312B4KX4614  | Machine Learning  | Universitas Sebelas Maret |


## Tech Stack
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PIL](https://img.shields.io/badge/PIL-%23150458.svg?style=for-the-badge&logo=pypi&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)


## About 
We have model, eyeglassess frame datasets, and recomendation algorithm in this repository
### Face Shape Classifier
- [Face Shape Classifier](di isi github face_shape_classifier_fix.ipynb) 
(image classification) use MobileNet as the base model for transfer learning that is taken from [Keras](https://keras.io/api/applications/mobilenet/). The model also contains an additional layer that received output from the based model. We use datasets [Face Shape Image Dataset](https://drive.google.com/drive/folders/1pF46doNcNDE8KyE9LYjx659tZ8jvtIex?usp=sharing) that contains 3,981 face images.

#### Model Training Performance
![trainingaccuracy](di isi train accuracy assets/train_accuracy.png)
#### Performance after Fine Tuning
![finetuning](di isi train result assets/train_result.png)

#### Performance Summary
Models | Accuracy | Val Accuracy
------------ | ------------- | -------------
Face Shape Classifier | 99.8 % | 83.5 %

## Scrapping for Eyeglasses frame from Online Marketplace
We have collected a dataset of 160 diverse eyeglasses frames from various online marketplaces.
The dataset, consisting of 160 entries, is intended to facilitate the development of an eyeglasses frame recommendation system based on classified face shapes. The eyeglasses frame dataset is stored in [CleanedDataFix.csv](CleanedDataFix.csv)
### Metadata

- *MarketplaceLink:* Link to the eyeglasses frame product on the online marketplace.

- *Name:* Name or title of the eyeglasses frame.

- *Brand:* Brand of the eyeglasses frame.

- *FaceShape:* Classified face shape for personalized recommendations.

- *Price:* Price of the eyeglasses frame.

- *Gender:* Gender for which the eyeglasses frame is designed (e.g., Men, Women, Unisex).

- *FrameColour:* Color of the eyeglasses frame.

- *FrameShape:* Shape of the eyeglasses frame (e.g., Rectangular, Round, Aviator).

- *FrameStyle:* Style or design category of the eyeglasses frame.

- *FrameMaterial:* Material used to construct the eyeglasses frame.

- *Pic1, Pic2, Pic3:* Links or URLs to the images of the eyeglasses frame.

Each entry in the dataset includes these attributes, providing comprehensive information for eyeglasses frame recommendations based on face shapes.

## Eyeglasses Recommendation Based on Face Shape
The primary purpose of the eyeglasses recommendation module is to enhance the user experience by offering curated suggestions that complement different face shapes.

### Algorithm Recommendation
- The [Recommendation Algorithm](Code_Recommendation.ipynb).
- Users can explore recommended frames, view additional details, and provide feedback to further enhance subsequent recommendations.

## Run the ipynb in Google Colab
You don't need to install anything just follow the steps below:
1. Download or clone this repository
2. Open Google Colab
3. Import the .ipynb file
4. Run the code

## Run in Local

1. Download the .ipynb file or clone this repostitory
2. Run this locally using ex: jupyter notebook
3. Install all the dependencies
  
  ! pip install -r requirements.txt
  
4. Run all the code
