![Hiragana](http://i.imgur.com/rFEs2jM.png "Hiragana")
# Hiragana-Identifier
Machine Learning project to identify Japanese characters (hiragana) from a data set. 
## Introduction
 Image recognition is very important in the evolution of artificial intelligence. Specifically, finding an efficient model for reading handwritten characters is an ongoing research for very different alphabets, whose symbols vary drastically. In this poster the problem of reading Japanese characters (hiragana) will be solved using Convolutional Neural Networks (CNN). The data set used was taken from a Github repository, which contained 50 different characters and 20 different samples for each one. While sample size is small, a considerable level of certainty can be obtained utilizing a good learning model. 
 ## Objective
 The objective of this project is to demonstrate that despite utilizing a small sample as training data, its possible to create a learning model utilizing convolutional neural networks to classify 50 different Japanese hiragana characters. The following algorithm is proposed in order to solve the problem:
 
 ![Flowchart](https://github.com/RakuTheSenpai/Hiragana-Identifier/blob/master/img/flowchart.png "Flowchart")

 ## Methodology

Our convoultional neural network consists of: 

- A convolutional layer with 50 kernels of size 5x5 with activation function ReLU
- A maxpooling layer in order to reduce computational workload.
- A fully connected layer consisting of 128 nodes with activation function ReLU.
- A fully connected output layer with 50 nodes and activation function softmax.

![CNN](https://github.com/RakuTheSenpai/Hiragana-Identifier/blob/master/img/model.png "CNN")

## Results

An accuracy of around 85% was obtained by training the model through the CNN with five iterations (epochs) without further improvement. There were 200 samples in the test data.
![results](https://github.com/RakuTheSenpai/Hiragana-Identifier/blob/master/img/results.png "Results")

Data set available at: [Hiragana73](https://lab.ndl.go.jp/cms/hiragana73?fbclid=IwAR2isHvlc2sxjzytRbHRXDaNQM__sevaA9azydGpcrUqlgXdK8LcMpXi13E) and 
[HiraganaGit](https://github.com/inoueMashuu/hiragana-dataset)

Project by [@RakuTheSenpai](https://github.com/RakuTheSenpai), [@TheChouzenOne](https://github.com/TheChouzanOne) and [@KillerFarmer](https://github.com/KillerFarmer)
