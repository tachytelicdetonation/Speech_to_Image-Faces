# Speech_to_Image-Faces

Speech to Face matching program

## Steps for implementing the program 

#### Step 1: Creating a dataset 
 1. Description of faces:
    First we need description of faces. Here we use : https://arxiv.org/pdf/1803.03827.pdf
    This allows us to get rich description of images from the dataset.
 2. Images of faces:
    Secondly we need a database of faces to which we can comapare the description given by user.
    We will be using : https://www.kaggle.com/jessicali9530/celeba-dataset

#### Step 2: Process to create the program
1. Speech to Text :
    We will be using google speech to text module to collect description of face from user.
    link: https://console.cloud.google.com/marketplace/details/google/speech.googleapis.com?filter=solution-type%3Aservice&id=7ae3f475-64e7-4123-880a-a889f34fa714

2.  Preprocessing Text:
    We will be using NLP to preprocess text received from speech-to-text API.
    After preprocessing the text is then passed to another machine learning model.

3. Machine Learning model:
    Using preprocessed text as input our machine learning model will it to retrive an image from our database.

## References 

* http://cs229.stanford.edu/proj2018/report/59.pdf
* https://scholarworks.sjsu.edu/cgi/viewcontent.cgi?article=1686&context=etd_projects
* https://arxiv.org/pdf/1803.03827.pdf
* https://arxiv.org/ftp/arxiv/papers/1904/1904.12403.pdf
* https://arxiv.org/pdf/1712.01769.pdf
