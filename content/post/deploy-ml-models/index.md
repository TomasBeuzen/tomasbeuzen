---
title: Deploying machine learning models with Amazon SageMaker or Flask & Heroku
subtitle: Simple tutorials of how to build and deploy machine learning models with commonly used tools.
summary: Simple tutorials of how to build and deploy machine learning models with commonly used tools.
authors:
- admin
tags: []
categories: []
date: "2020-02-01T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
### Introduction

I recently wrote up some [tutorials on my GitHub](https://github.com/TomasBeuzen/machine-learning-tutorials/tree/master/ml-deploy-model) to help data scientists deploy machine learning models. The aim of the tutorials is to provide a simple guide to deploying machine learning (ML) models for data scientists familiar with machine learning in a local environment, but interested in learning how to deploy their models. Deployment refers to the act of making your ML model available in a production environment, where it can be accessed and utilised by other software.

Perhaps surprisingly, deployment is a process that is quite unfamiliar to many data scientists - in large part due to the need for some level of familiarity with software engineering. Fortunately, there are many tools avaialble to help us data scientists with deploying our models. The tutorials focus on currently and commonly used tools for ML deployment and are overwhelmingly practical, aiming to provide a useful overview of these tools and a foundation for using and expanding upon them in future. Here is a current list of tutorials, click a link to get started (to follow these tutorials, I recommend cloning the GitHub repository to your local machine):

1. [Building and deploying a machine learning model with Amazon Sagemaker](https://github.com/TomasBeuzen/machine-learning-tutorials/blob/master/ml-deploy-model/deploy-with-sagemaker.ipynb)
2. [Deploying a machine learning model with Flask and Heroku](https://github.com/TomasBeuzen/machine-learning-tutorials/blob/master/ml-deploy-model/deploy-with-flask.ipynb)