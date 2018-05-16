# Perceptron
 A perceptron is the simplest neural network possible: a computational model of a single neuron. A perceptron consists of one or more inputs, a processor, and a single output.

![Perceptron](https://i.imgur.com/iqIvKMy.png)

For further more info about Perceptron reference <b> Nature of code</b> [ Chapter 10. Artificial Neural Networks: Introduction and Application](http://natureofcode.com/book/chapter-10-neural-networks/#102-the-perceptron) 

## Table of contents
- [Introduction](#perceptron)
- [Colaboratory Link ](#colaboratory-link-for-ipython-notebook)
- [About this IPython Notebook](#about-this-ipython-notebook)

### Colaboratory Link for IPython Notebook 
[https://colab.research.google.com/driv.....](https://colab.research.google.com/drive/15tLW-Uv62823MCtu4L4oakPDDw_fQOm8)


## About this Ipython Notebook
This notebook contains a Perceptron class with n inputs,bias,and learning rate
```python
class Perceptron:
    """"Perceptron class with n input and one output"""
    def __init__(self,noOfInputs,bias = 0,learningRate = 0.1):
```
I used this perceptron to classify points above and below line y=x.

*This can be done using simple regression model.*  (I know that,this is done for learning purpose.)


The train set and test set data are generated randomly from (0,0) to (100,110).Also the bias and weights were generated randomly.

![Imgur](https://i.imgur.com/nle9haf.png)

After training the perceptron using 100 data set for 90% accuracy The error decreases below 10% only after 3 ilteration.

![Imgur](https://i.imgur.com/CQwDpM1.png)

So after training I used 100 test set to test the effectiveness of this Perceptron,Following are the results.
![Imgur](https://i.imgur.com/28xsPMQ.png)

Just amazing...

### Once again [Colaboratory Link](https://colab.research.google.com/drive/15tLW-Uv62823MCtu4L4oakPDDw_fQOm8)


