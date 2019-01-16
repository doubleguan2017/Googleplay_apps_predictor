# Googleplay_apps_predictor
Teammates: Jingyao Yu, Lingfei Cui

# Background
Nowadays, people download Android Apps from Google Play and IOS Apps from Apple Store. In the Google Play, people feel it’s difficult to find the best one among those similar Apps especially for some new ones. It is impossible for them to use each of them and find the most usable one. So a more precisely rating is great and convenient to give users a reference when choose a functional App. An accurate rate could save time and give people better experience. Also it could help developers to improve their product.

# Datasets and Methodolgies
In this project, we investigated and predicted the rating of Apps based on attributes of the 12 terms, includes App, Category, Reviews, Size, Installs, Type, Price, Content Rating, Genres, Last Updated, Current Ver and Android Ver. We scratched data from www.kaggle.com and used the decision tree and LOOCV to get our preliminary results.

Four festures are designed to implement our tree nodes, which are attribute, children, label and isLeaf.

ID3 algorithm is used to do the decision tree learning, and missingProcess function is used to do the data pre-processing

# Results
After doing the training and purning, we could fianlly get our results:

training accuracy: 0.9988137603795967 
test accuracy: 0.9787234042553191

# More Information
More information regarding to the project: 
https://www.youtube.com/watch?v=pAH1r-a9834
