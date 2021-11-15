# Individual-Self-Assessment

## Self-assessment
### Why this project
I started searching about 2 months ago for the idea that we can make a project on. I wanted to do something that is related to medical field. I searched various datasets and came across chest x_ray dataset that had both normal and pneumonia categories.This dataset was quite interesting for me and I wanted to make a model that process images.
Next was to see if my team agrees with it, I presented them this idea along with other ideas like heart failure prediction etc. My team liked pneumonia prediction idea and we went with it.
### My Role
I took the responsibilty of training the machine learning model because I find machine learning very interesting and I enjoyed testing various models and techniques. I decided to choose cnn model because they are  used for image classification and recognition and gives high accuracy.          
There are over 5800 images and there were difficulties reading and training and testing the images on the model. So I found google colab GPU runtime that works better than any other configuration.             
Initially I had the model for 3 dimension RGB images. our instructor Dave pointed it out and I changed it to 1 dimension grayscale images.         
I had to face difficulties along the way such as severe overfitting problem that is common for CNN models. I tried various techniques such as various hyperparameters, various activation functions and adding dropout layers, normalization functions, increasing/decreasing nodes ,to work with the model.These techniques didn't help then I started researching about the topic and realized that in order to make the model perform well I made it too complex by adding number of layers, number of dropout and normalization functions and so when it receives a new image it is not able to process it well.            
So I went back took out all the layers and started with a simple basic CNN model and started adding layers until I see better accuracy and reasonable size of saved model file.
We tested the model on validation set of images that the model has never seen before.            
Finally we have a model that was giving us Accuracy = 89.42%, Precision = 86.16% , Recall = 98.97% , Specificity = 73.50% 

F1 Score = 92.12%

### Contribution to other roles
  I set up the app file that we need in order to work with our project. We had issues with that initially but TA Mounika and TA Rebekah helped us set it up and we were able to connect it to HTML file and it started working as expected.

## Team assessment




## Summary of the project
### Topic addressed
### Machine module used
### Results of the analysis
