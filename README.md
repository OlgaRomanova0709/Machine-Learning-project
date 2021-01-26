# Know-Before-You-Eat
An Interactive web application for identifying food names based on the images, providing nutritional facts (For eg: calculating calories of the food you're eating) for diet advice and predicting the recipes based on the predicted food names.

## <ins> Final Deployed Application Link </ins>
<a href="http://34.94.205.236:5000/#About"> Know Before You Eat </a>

![Home Page Pic](KnowBeforeYouEat.png)

## <ins> Presentation Link </ins>
https://docs.google.com/presentation/d/1L3HPKQ_NltZVhTflytylM7TNFtg3tfW1BnI9JeCAXP4/edit?usp=sharing

## <ins> Source Data </ins>

1) Food101 Dataset
https://www.vision.ee.ethz.ch/datasets_extra/food-101/

2) Nutritional Facts 
https://www.fatsecret.com/calories-nutrition/
http://ahealthylifeforme.com

3) Recipe
https://www.kaggle.com/kaggle/recipie-ingredients-dataset
https://en.wikipedia.org/wiki/

## <ins> Tools/Models Reference </ins>

1) Classification/Training Models

   > Transfer Learning With MobileNet 
   
   > Transfer Learning With VGG16
   
   > KNN & Random Forest

2) Keras Image Data Generator for Image Augmentation

3) Front End Application - HTML, CSS, Bootstrap and Javascript

4) Retrieving Data From Back End : Python (SQLAlchemy and Flask)

5) Missing Link AI - Platform to Run deep learning experiments on hundreds of machines, on and off the cloud, manage huge data sets and gain unprecedented visibility into your experiments.
https://missinglink.ai/

Presentation: https://docs.google.com/presentation/d/1UvU7sMPkn2Y5I88bmdoH0Sog3SpyQeSPeVdtSZoHrDk/edit#slide=id.g6ea730b6b1_7_5

![pres1](Presentation_snapshots/1.png)
![pres2](Presentation_snapshots/2.png)
![pres3](Presentation_snapshots/3.png)
![pres4](Presentation_snapshots/4.png)
![pres5](Presentation_snapshots/5.png)
![pres6](Presentation_snapshots/6.png)

## <ins> Results </ins>
1) After fine-tuning a pre-trained MobileNet model achieved about 99.03% Top-1 Accuracy on the Training set and about 73% accuracy on Valid & test data.
2) After fine-tuning a pre-trained VGG16 model achieved about 98.03% Top-1 Accuracy on the Training set and about 70% accuracy on Valid & test data.
3) Using KNN  Algorithm achieved at score:0.404 at K=3
4) Using Random Forest Model achieved at score:0.2


## <ins> Key TakeAways </ins>
1) Through application of Various Machine Learning Algorithms - K-Nearest Neighbour, Random Forest Classification and Deep Learning(CNN) Algorithms for image classification we concluded that CNN is the best model for classification of images in our data set.
2) In CNN pretrained models  Mobilenet model is the best in terms of both speed and accuracy in our dataset.
3) MobileNet is the best method and quickest way to implement transfer learning for CNN’s.
