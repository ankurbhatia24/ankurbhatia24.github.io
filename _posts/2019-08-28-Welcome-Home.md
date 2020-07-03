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
