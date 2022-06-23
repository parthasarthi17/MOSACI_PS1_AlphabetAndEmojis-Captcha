In this project i have created two notebook
1) Emoji Model_training :- In this I have read all the emoji data , performed augmentation on them and saved them in a CSV file. Created a emoji prediction model and saved that named as "emoji_model.h5" .


2) Alphabet_Model_training :- In this i have used a alphabet datset from kaggle and created a model for alphabets prediction and saved that as "only_alphabet_model.h5" .

Now I created a segmentar file which is used to segment image.

###### To run this project we can run main.py file. #####

In main.py file there is a Get_Ans function which uses Get_Images function from segmentar.py and predict the output.
