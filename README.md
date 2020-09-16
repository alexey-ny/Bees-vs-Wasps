# Bees vs Wasps
This project is aimed at building a prototype/template approach to selecting the best model for image recognition. <br>
4 CNNs were used to distinguish between bees and wasps for which I used a dataset published to Kaggle datasets by George Rey at 
https://www.kaggle.com/jerzydziewierz/bee-vs-wasp. 
And I created a supplemental dataset of flowers without insects to check how well the trained model able to discriminate flowers from the insects https://www.kaggle.com/antaresnyc/flowers-blossom. <br>
As was expected models confused what they were recognizing, and after mixing 370 images of just flowers in the test set we saw that most of them were classified as images of wasps. <bt>
So the next step would be to expand that supplemental dataset with more flowers images and retrain the models on it to improve the accuracy.<br>
As for the model selection it is quite impressive how much more <i>efficient</i> EfficientNet architecture is. 
