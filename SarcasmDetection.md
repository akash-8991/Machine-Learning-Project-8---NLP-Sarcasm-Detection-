# Machine-Learning-Project-8---NLP-Sarcasm-Detection

Description 
Past studies in Sarcasm Detection mostly make use of Twitter datasets collected using hashtag based supervision but such 
datasets are noisy in terms of labels and language. Furthermore, many tweets are replies to other tweets and detecting 
sarcasm in these requires the availability of contextual tweets. 
 
In this hands-on project, the goal is to build a model to detect whether a sentence is sarcastic or not, using Bidirectional 
LSTMs. 
Dataset 
News Headlines dataset for Sarcasm Detection 
The dataset is collected from two news websites, theonion.com and huffingtonpost.com 
This new dataset has the following advantages over the existing Twitter datasets: 
 
Since news headlines are written by professionals in a formal manner, there are no spelling mistakes and informal usage. 
This reduces the sparsity and also increases the chance of finding pre-trained embeddings. 
Furthermore, since the sole purpose of TheOnion is to publish sarcastic news, we get high-quality labels with much less 
noise as compared to Twitter datasets. 
Unlike tweets that reply to other tweets, the news headlines obtained are self-contained. This would help us in teasing 
apart the real sarcastic elements 
