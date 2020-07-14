---
layout: post
title: "Bienvenue. You're with Ankur Bhatia!"
date: 2019-08-28
desc: "Welcome to Ankur's personal blog."
keywords: "Blog, Tensorflow, Keras, C++, Jupyter, Notebook, OpenCV, Federated-Learning, Robotics, Drones, Electronics, and much more..."
categories: [Blog]
tags: [Blog]
published: true
blog: Home
images:
  - url: /assets/Cover-Home.jpg
icon: icon-html
---

## Status
I am open for Internship Opportunities in Fall 2020 and my near goal is to do a Masters in the field of Deep Learning. <br>

------



<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:6675080824905375744" allowfullscreen="" title="Embedded post" width="504" height="676" frameborder="0"></iframe>  <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:6673205140901777408" allowfullscreen="" title="Embedded post" width="504" height="676" frameborder="0"></iframe> <br>

------
# ICML 2020: Review - 
### [link](https://ankurbhatia24.github.io/ICML2020/)

# Proof: Floyd's cycle finding Algorithm (Hare and Turtle algo)  <img src="/assets/HomePage_Blogs/new_small.gif"> <br>
Floyd's cycle-finding algorithm is a pointer algorithm that uses only two pointers, which move through the sequence at different speeds. This algorithm can be used to detect cycle in linked lists in O(n) time and O(1) Space and also detect the position of start of the linked list. This video tutorial explains the concept and proof of the algorithm. <br>
Video_link: [https://youtu.be/iQmFtH0kj2c](https://youtu.be/iQmFtH0kj2c) <br>
<img src="/assets/HomePage_Blogs/HareAndTurtle.gif" height="174" width="600">  <br>

# Paper Review on Ranknet <img src="/assets/HomePage_Blogs/new_small.gif"> <br>
In this video, we understand about Ranknet. Learning to Rank using Ranknet (by Microsoft) is a Ranking Algorithm that is used to rank the results of a query. The ranking comparison is performed pairwise, no mapping to particular rank values is required and no rank boundaries are needed. Hence, this paper removes the need of performing ordinal regression. Also, this paper presents a probabilistic cost function and learning using Gradient Descent.<br>
Video Link: [https://www.youtube.com/watch?v=MuAhhikIm2U](https://www.youtube.com/watch?v=MuAhhikIm2U) <br>
Paper Link: [ICML_RankNet](https://icml.cc/2015/wp-content/uploads/2015/06/icml_ranking.pdf) <br>
Code: [ranknet.py](https://github.com/airalcorn2/RankNet/blob/master/ranknet.py) <br>


# Deploy a flask app on Amazon AWS EC2 and keep it running while you are offline. <br>
This blog is published under [Analytics Vidhya Publication](https://medium.com/analytics-vidhya). Flask is a micro web framework in python. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It’s easy to get started with to deploy .py’s on the web....... <br>
[Read More](https://medium.com/analytics-vidhya/deploy-a-flask-app-on-amazon-aws-ec2-and-keep-it-running-while-you-are-offline-38d22571e2c5)


### Some Helpful Blogs:
1. Getting Started with Docker - [https://championshuttler.github.io/docker-basicLearning/](https://championshuttler.github.io/docker-basicLearning/)
2. Bayesian Inference for Parameter Estimation - [Medium Article](https://towardsdatascience.com/probability-concepts-explained-bayesian-inference-for-parameter-estimation-90e8930e5348)
	* This includes details about Bayes Theorem, Prior, Posterior, Liklihood and Marginal (evidence) distributions (i.e. all parts of the bayes formula)
	* Maximum a posteriori probability estimate or simply, the MAP estimate - The most important statistic calculated from the Posterior Distribution. (called Mode (statistics))
	* The fact that the posterior and prior are both from the same distribution family (they are both Gaussians) means that they are called conjugate distributions. In this case the prior distribution is known as a conjugate prior.
	* Includes a best blog for Latent Dirichlet Allocation (LDA) which is an unsupervised learning algorithm for finding topics in text corpa.[Blog](http://blog.echen.me/2011/08/22/introduction-to-latent-dirichlet-allocation/)
	* Markov Chain Monte Carlo methods - If the prior and or liklihood are not gaussians, then their multiplications (Bayes) is difficult. [Blog](https://towardsdatascience.com/a-zero-math-introduction-to-markov-chain-monte-carlo-methods-dcba889e0c50)
	* Continous Updating Bayesian Inference if new data points arises. Application in Kalman Filters. [Blog](http://www.bzarg.com/p/how-a-kalman-filter-works-in-pictures/)
	* How can priors acts as regularizers.
3. How to Use t-SNE Effectively - [distill Pub T-SNE](https://distill.pub/2016/misread-tsne/)
4. Stratifying the data during Train Test Slplit - [https://towardsdatascience.com/3-things-you-need-to-know-before-you-train-test-split-869dfabb7e50](https://towardsdatascience.com/3-things-you-need-to-know-before-you-train-test-split-869dfabb7e50)
	* Using seed is important so that results are reproducible (seed numpy, tf, cuda)
	* Stratification is necessary so that the data distribution remains same in both train set and test. Not be the case like most data from 3 classes (say) are in train set and other 2 classes (say ) in test set. Easily be done using stratify argument in train_test_split() from sklearn.
5. Self Supervised Representational Learning - [https://lilianweng.github.io/lil-log/2019/11/10/self-supervised-learning.html](https://lilianweng.github.io/lil-log/2019/11/10/self-supervised-learning.html)
6. Deep Learning Based Text Classification: A Comprehensive Review (2020) - [arXiv pdf](https://arxiv.org/pdf/2004.03705.pdf)
7. Deep Learning for Single Image Super-Resolution : A Brief Review (2019) - [arXiv pdf](https://arxiv.org/pdf/1808.03344.pdf)

### To Read about:
1. Soap Bubble Effect in High Dimensionals Gaussians - Much of the density of a high dimensional Gaussian lies close to the surface of a hypersphere: [Stack Exchange Question](https://stats.stackexchange.com/questions/419412/why-is-gaussian-distribution-on-high-dimensional-space-like-a-soap-bubble)
2. One of the best explanations of Gaussian Processes - 2019 distill Publication: [visual-exploration-gaussian-processes/](https://distill.pub/2019/visual-exploration-gaussian-processes/)
3. Deep NN's as Gaussian Processes: [Paper](https://arxiv.org/pdf/1711.00165.pdf)
4. Fast and Easy Infinite Wide Networks - Google ICML 2020: [Google AI Blog](https://ai.googleblog.com/2020/03/fast-and-easy-infinitely-wide-networks.html)
5. Infinitely Deep Infinite Width Networks - ICLR 2019: [Paper](https://openreview.net/pdf?id=SkGT6sRcFX)
