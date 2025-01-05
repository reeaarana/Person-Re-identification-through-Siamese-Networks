# Person-Re-identification-through-Siamese-Networks
Training a simple Siamese Network for Person Re-Identification

Hi I'm Reeaa and this is one of my SNN implemented projects that i compeleted while learning this skill.

In this project we took a basic street view image data with pre identified civilians (tho low quality so the model just identifies through colour difference)
and then implements siamese neural network, trains the netwrok with triplet loss function, 
spliting and creating anchor, positive and negative image dataset through which network learns the feature embeddings

Siamese Neural Networks transforms projects with its dual-branch architecture, effortlessly enhancing accuracy in face and signature matching. 
This indispensable tool streamlines similarity assessments, making it an ideal choice for efficient and reliable comparisons.
Elevate your project with SiameseNN's seamless integration and precision. 

The Basic structure of the main code goes as
1) Importing the libraries & uploading the dataset
2) configurations
3) APN Dataset
4) Loading dataset to branches
5) Model
6) train and eval function
7) training loop (Epochs is set to 15)
8) anchor embeddings
9) inference

PS you need to download the dataset, a link to the whole dataset is also given in the second cell of the code by
!git clone https://github.com/parth1620/Person-Re-Id-Dataset
