# TRINIT_594092-U0G1HN92_ML03

Here I have used crop prediction dataset for Predicting the optimal crop that could be grown in a particular location based on the
soil composition, rainfall, temperature and return of investment is essential for any farmer of the modern world. 
This could not only save farmers from spending extra money on fertilizers but also avoid the dangerous practice of growing the same crops
on the same patch of land repeatedly, which depletes the solid from its natural
resources.

Initially we have created a custom dataset which contains all the attribute as mentioned in the given problem statement.
Using pandas we have initially read the data present in it and checked wheather any kind of null data is present in it or not.
Also using scikit library we have check wheather the created dataset is ideal to proceed with training or not
The details of those parameter are shared in the repository under the file Tri_para_check.ipynb

I have used Tensor flow and ANN (Artificial Neural Network) with 4 hidden layers for training the model, wecomplied the model with ADAM optimizer 
with a learning rate of 0.01. Upon training for 50 epochs we gained an accuracy of 0.9627 and a loss of 0.084
Then I have also used Gradio Library for User Interface.
