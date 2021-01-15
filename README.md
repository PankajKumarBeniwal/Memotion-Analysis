# Memotion-Analysis
## Emotion Analysis of memes
It is the multi-level classification of the emotions of Meme's
### Dataset - kaggle datasets download -d williamscott701/memotion-dataset-7k
#
Preview of Dataset
![data](https://user-images.githubusercontent.com/63897550/104676479-78ee3300-570d-11eb-8e47-c489e2aa6c79.PNG)
### The Project is divided into three tasks Task A, Task B, Task C
Task A - It reffers to the sentiment analysis of the text and image wheather the meme is Very Positive, Positive, Neutral, Negetive, Very Negetive
#
Task B - This reffers to the 1st level of classification where the meme is classified into diffrent categories (Humour, Offensive, Motivational, Sarcasm)
#
Task C - Finally this Task reffers to 2nd level classification where the meme is further classified into sub categories(like in humour subclass(Very funny, not funny, funny, hilarious))
### Technologies Used

#### Language Used - Pyhon
#### Pandas Library
#### Deep Learning Models(CNN For Image(Resnet, VGG16), Bidirectional GRU for Text )
#### OpenCV for Image Processing
#### Tensorflow / Keras
#### NLP Tools (Word Embedding)
### Here is the Model Summarization and model that is implemented
![model](https://user-images.githubusercontent.com/63897550/104676749-016cd380-570e-11eb-9cb8-5e985986e777.png)

## Evaluation
#### Model     #### Resnet50     #### VGG16        #### Resnet50 + VGG16
#### Task A    #### 0.23952      #### 0.23952      #### 0.23952
#### Task B    #### 0.42857      #### 0.42857      #### 0.42857
#### Task C    #### 0.47441      #### 0.47332      #### 0.47461
Evaluation is done in form of F1 Score

## Comparision
![eval](https://user-images.githubusercontent.com/63897550/104677599-a9cf6780-570f-11eb-8f99-1f8fa0e8ab58.PNG)











