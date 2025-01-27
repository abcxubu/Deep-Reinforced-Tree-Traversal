# Deep-Reinforced-Tree-Traversal
This is the official released code for **A Deep Reinforced Tree-traversal Agent for Coronary Artery Centerline Extraction**. 
Here we released detailed codes and also a set of toy models in order to visualize the result. Please check the original paper (https://doi.org/10.1007/978-3-030-87240-3_40) for detailed ideas.

![alt text](images/pipeline.png "pipeline")

## Requirements:
We only test codes under the following environment, other reasonable environment settings should work as well.
* Ubuntu 16.04
* CUDA 10.1
* Python 3.8
* Pytorch 1.6.0
*  .....

pip install all other required libaries.

## Usages:
Download the example_data from the link: https://drive.google.com/file/d/1yeJIoBALUGasHyFHAijkNILTtjhwfGXx/view?usp=sharing. Then substitute the place-holder folder with the one you downloaded.

1. To check the effect of the proposed method, run the inference through:
```shell
python tracer/inference.py
```
2. One can also run the train code with the toy data. However it's not likely to get any reasonbale result or weight:
```shell
python tracer/main.py
```
3. Train the discriminator with the following command. Still no sensable result is guaranteed:
```shell
python discriminator/main.py
```
## More Words:
For those who are truly interested in DRL, please reference https://github.com/p-christ/Deep-Reinforcement-Learning-Algorithms-with-PyTorch for more details.
And honestly speaking, this code is a little bit messy and surely there are more elegent ways to organize the code as well as data structure. However, due to many reasons (mainly because I am too lazy	:ghost:	:ghost:	:ghost:) here we are. So try not to stuck in detailed codes. Feel free to contact me (lzvv123456@icloud.com) if you have any confusion.
