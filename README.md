# Learning Data Science 

In this repository, I'll keep the code I write as I learn about Data Science. 

I write about what I am learning here: 
https://medium.com/@gabrieltseng/

For all notebooks which require a GPU I use an [AWS P2 instance](https://aws.amazon.com/ec2/instance-types/p2/). 

## 
I approached the projects in the following order (latest to earliest):

<details>
<summary><strong><em>Table of Contents</em></strong></summary>

* [MNIST WGAN](#WGAN)
* [Language Model](#LanguageModel)
* [Object Detection](#ObjectDetection)
* [Stanford Databases Course](#StanfordDatabases)
* [ThinkBayes (Bayesian Statistics)](#ThinkBayes)
* [Twitter Disasters (NLP)](#Twitter)
* [Detecting Bullies (NLP)](#Bullies)
* [Style Neural Network](#StyleNeuralNetwork)
* [Quora (NLP)](#Quora)
* [Recommender System](#recsys)
* [Image Recognition](#ImageRecognition)

</details>

### [MNIST WGAN](gans/mnist_wgan)<a name="WGAN"></a>

A [WGAN](https://arxiv.org/abs/1701.07875) used to generate MNIST digits.

### [Language model](natural_language_processing/language_model)<a name="LanguageModel"></a>

I experiment with two language models, one based of the [weight dropped LSTM](https://arxiv.org/abs/1708.02182), and one
based off [temporal convolutional networks](https://arxiv.org/abs/1803.01271). Both are trained on the 
[Wikitext 2 dataset](https://einstein.ai/research/the-wikitext-long-term-dependency-language-modeling-dataset).

### [Object Detection](computer_vision/object_detection)<a name="ObjectDetection"></a>

I build a single and multi image object detector, which can label and locate objects in an image. Both models are trained on
the [Pascal VOC 2007 challenge dataset](http://host.robots.ox.ac.uk/pascal/VOC/voc2007/index.html).

### [Stanford Databases](databases/stanford_databases)<a name="StanfordDatabases"></a>

I work through the [Stanford Databases](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about) by Jennifer Widom.
The folder contains my solutions to the exercises. In the case where there were no exercises (i.e. there was only a quiz),
I only added the statement of accomplishment.

### [Think Bayes](bayesian_statistics/think_bayes)<a name="ThinkBayes"></a>

I work through [Think Bayes](http://greenteapress.com/wp/think-bayes/) by Allen Downey. The folder contains my solutions
to the exercises.

I took the exercises from both the book, and the [GitHub repository](https://github.com/AllenDowney/ThinkBayes2)

### [Twitter Disasters](natural_language_processing/twitter_disasters)<a name="Twitter"></a>

I build a tweet summarizer ([COWTS](http://dl.acm.org/citation.cfm?id=2914600)), with the goal of providing a useful summary of tweets to a rescue team in a disaster scenario. This involves experimenting with Integer Linear Programming, term frequency - inverse document frequency scores and word graphs. 

  * [Post 1 on medium](https://medium.com/@gabrieltseng/summarizing-tweets-in-a-disaster-e6b355a41732) 
  * [Post 2 on medium](https://medium.com/@gabrieltseng/summarizing-tweets-in-a-disaster-part-ii-67db021d378d)

### [Detecting Bullies](natural_language_processing/detecting_bullies)<a name="Bullies"></a>

I train machine learning algorithms on a smaller dataset (~3000 datapoints) to recognize bullying in online discussions, as part of Kaggle's [Detecting Insults in Social Commentary](https://www.kaggle.com/c/detecting-insults-in-social-commentary) competition. By implementing word embeddings, I significantly improve the competition's best result. 

  * [Post on medium](https://medium.com/towards-data-science/using-scikit-learn-to-find-bullies-c47a1045d92f)

### [Style Neural Network](computer_vision/style_neural_network)<a name="StyleNeuralNetwork"></a>

I experiment with generative neural networks by building a style neural network, which takes as input two images, and outputs an image with the content of the first image and the style of the second image. I improve the original neural style network ([A Neural Network of Artistic Style](https://arxiv.org/abs/1508.06576)) by implementing two additional papers ([Incorporating Long Range Consistency in CNN based Texture Generation](https://arxiv.org/pdf/1606.01286.pdf) and [Stable and Controllable Neural Texture Synthesis and Style Transfer Using Histogram Losses](https://arxiv.org/abs/1701.08893)). 

  * [Post on medium](https://medium.com/towards-data-science/montreal-painted-by-huang-gongwang-neural-style-networks-ec1697b2ac54) 
  
### [Quora](natural_language_processing/quora)<a name="Quora"></a>

I build a recurrant neural network based on the [GloVe](https://nlp.stanford.edu/projects/glove/) word embeddings to recognize the intent of questions posted on [Quora](https://www.quora.com) as part of Kaggle's [Quora Question Pairs](https://www.kaggle.com/c/quora-question-pairs) competition. 

  * [Post on medium](https://medium.com/towards-data-science/natural-language-processing-with-quora-9737b40700c8) 

### [Recommender System](recommender_system)<a name="recsys"></a>

In this project, I use the [Movie Lens](https://grouplens.org/datasets/movielens/) dataset to explore a variety of data science tools, including dimensionality reduction and word embeddings. I build a recommender system using a recurrant neural network, and implement Google's [Wide and Deep](https://arxiv.org/abs/1606.07792) recommender neural network. 

  * [Post 1 on medium](https://medium.com/@gabrieltseng/clustering-and-collaborative-filtering-visualizing-clusters-using-t-sne-f9718e7491e6)
  * [Post 2 on medium](https://medium.com/@gabrieltseng/clustering-and-collaborative-filtering-implementing-neural-networks-bccf2f9ff988) 
  * [Post 3 on medium](https://medium.com/towards-data-science/clustering-and-collaborative-filtering-using-word-embeddings-56ee60f0575d)

### [Image Recognition](computer_vision/image_recognition)<a name="ImageRecognition"></a>

In this project, I finetune and ensemble a variety of pretrained convolutional neural networks in Keras to identify invasive plant species in images, as part of Kaggle's [Invasive Species Monitoring](https://www.kaggle.com/c/invasive-species-monitoring) competition. 

  * [Post 1 on medium](https://medium.com/@gabrieltseng/learning-about-data-science-building-an-image-classifier-3f8252952329)
  * [Post 2 on medium](https://medium.com/towards-data-science/learning-about-data-science-building-an-image-classifier-part-2-a7bcc6d5e825)
  


