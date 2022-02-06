# Table Data Exploration

## Chocolate Ratings
Exploring the origins of the bean used in chocolate vs the rating the chocolate received:
<img width="917" alt="Rating-Origin" src="https://user-images.githubusercontent.com/11840970/152693114-b975f3d2-f648-4a0a-bf91-9d7203d1cfc5.png">

Dataset Source: [Kaggle](https://www.kaggle.com/andrewmvd/chocolate-ratings?select=chocolate_ratings.csv)

## Bike Dataset
This plot includes the popular bike rental data set from [UCI](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset). As mentioned in my other repo, I find that including the registrations data in training (as done [here](https://thinkingneuron.com/bike-rental-demand-prediction-case-study-in-python/))is kind of cheating. The amount of registered users is in fact part of the total "cnt".
<img width="964" alt="Bike-registeredVcount" src="https://user-images.githubusercontent.com/11840970/152693319-21b7fe80-8a5b-44a0-b448-98e45996a46f.png">

## Predicting Depression, Anxiety and Stress
A very interesting dataset based on surveys collected between 2017 and 2019 with 42 questions and 40,000 participants. Some interesting plots:

Average Depression, anxiety, and stress scores by age with dropping scores as age increasing, but increased variability as age gets closer to 70. 
<img width="979" alt="Depression-avgScores" src="https://user-images.githubusercontent.com/11840970/152702662-bbec0972-bb68-4b08-b8f9-5d529ddad963.png">

Scores by degree levels with lower scores as education increases.
<img width="1288" alt="Depression-avgByDegree" src="https://user-images.githubusercontent.com/11840970/152702720-f904be04-804d-4f24-938a-cc50c185f179.png">

Minimum scores with university education.
<img width="1291" alt="Depression-university" src="https://user-images.githubusercontent.com/11840970/152702744-aa22c032-e58e-4ecd-a025-68e2aea2ef02.png">

Minimum scores with a graduate degree.
<img width="1294" alt="Depression-gradDegree" src="https://user-images.githubusercontent.com/11840970/152702759-8da8d0d4-e5aa-4380-ae06-0de2bd0ba810.png">

The last two have for some reason higher scores below the age of 20 for university and graduate degrees, which is not a typical age for having a university or graduate degree.
