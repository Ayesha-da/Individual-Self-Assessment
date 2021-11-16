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
We had an awesome team. Each member of the team brought so much to the table. I learned so many new things from my teammates.I learnt how to affectively research and cohesively present information from Mathew. I learnt how to efficiently do preprocessing and getting the dataset up and running on the database from Nidhi.I learnt how to explore valuable information and organize all the details and present them in an engaging format from William.I also learnt good html formatting and styling from chelsea.

Our main communication protocol was slack.We also had regular meetings on zoom graciously arranged by one of our team member William, where we discussed so many issues, troubleshoot and get things up and running.

I think if given a chance we would like to add more time during live presentation.All of us has worked so hard but due to very limited time for live presentation, we will not be getting the time required to present each section.

For the new cohort, I would be suggesting to start early and this way when they are already prepared about what they would like to do on a project, it will become much easier when it actually begins.There is limited time for the project and there will be so many issues to deal with. The earlier the project idea exploration starts, the better.

## Summary of the project
 Our project will use CNN model to interpret chest x-ray images and classify them as normal or pneumonia.
### Topic addressed
- The use case for generating this model is to develop a process to objectively analyze and interpret x-ray images with a rate of speed and accuracy that is potentially better than the human eye.
- This model could be a valuable resource for doctors and students as another tool for interpreting x-ray images and validating/invalidating their personal diagnoses.
Additionally, this model could be further applied to chest x-rays with diagnoses outside of pneumonia and be adapted to interpret the x-rays of patients with an array of diagnoses.
### Machine module used
We used convolutional neural network (CNN/ConvNet), a class of deep neural networks, most commonly applied to analyze visual imagery. We are primarily working with images, and we need CNN model to take in these images, process them and give us the desired output by classifying them correctly as "Normal" or "Pneumonia".
### Results of the analysis
We have a model that gives us about 89.45% accuracy and ROC curve accuracy of 96.29%. When we upload an image of a chest X_ray the model accurately classifies the image into "Normal" or "Pneumonia". 
