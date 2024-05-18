---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

Education
=========

* B.Sc in Computer Science and Engineering, Rajshahi University of Engineering and Technology, Jan 2018 - Sep 2023

Work experience
===============

#### Data Scientist — Manaknightdigital (Toronto, Ontario, Canada) , March 22, 2023 – Present, Full-Time

**1. Atlas Copco Chatbot**:

* Primary Goal: to create a chatbot that will answer the questions based on the requirements using the given data.
* Solution: Collect the data(excel file) which contains various product info(Model Name, Price, Capacity, Products Links). Then used the GPT(GPT- 4) model to answer the questions of what the user need. Also, tackle the token size in the GPT models.
* Library: openai, Flask, openpyxl,pandas
* Website: [Atlas Copco](https://atlascopco.manaknightdigital.com/)

2 . **Fraud Transaction Detection**:

* Primary Goal: Given a dataset of past transactions then from this data set have to build an ML model that can detect fraud transactions.

* Solution: performed EDA and Feature Extraction apply multiple ML algo(Xgboost,SVC,Logistic Regression) then apply hyperparameter optimization and deployed on the server for production. Got 90% accuracy using Xgboost.
* Library: scikit-learn,Flask

**3. Michel AI Parabroker ChatBot**:

* Primary Goal: scrape data from different lenders then get answer out the data from user query

* Solution: used Retrieval Augmented Generation(RAG) based searching techniques to get the answers and for data storing used Pinecone also used Cohere Reranking to refine the RAG search

* Library: PyPDF2,beautifulsoup,gunicorn,GPT-4, Pinecone,RAG, Cohere, Flask

* Website: [Cynario AI](https://cynario.ai/)


**4. Football Analyst ChatBot**:

* Primary Goal: to make a Football Analyst which will analyze the pass data for a particular Team and Player and Predict the future match

* Solution: scrap data from different football data sources and then used RAG,Pinecone and Cohere to get the response out of the huge amount of data

* Library: BeautifulSoup, PyPDF2, RAG, Pinecone, Cohere

* Website: [Kaizenwin](https://kaizenwin.com/)

**5. Image Generation (Aieventbooth)**:

* Primary Goal: user will add some presets for a given image then it will generate the image

* Solution: used Stable Diffusion Image Generation, trained on custom image and then based on the used presets generates the image

* Library: transformers,PyTorch

* Website: [Aieventbooth](https://aieventbooth.com/)

**6. Ai Energy**:

* Primary Goal: clients have some organization's privacy and policy, now a tender will came and we have look up the organization's data how many matches each of the tender's and why matched

* Solution: to solve this problem first chuck the data into different sections for this finetuned different models like Llama-2-7B and 13B also Mistral-7B then used the cosine similarity to get the matched data and then used the GPT-4 to get the answer out of the data

* Library: transformers,PyTorch

* Website: [Ai Energy](https://aienergy.manaknightdigital.com/)

Skills
======

* Natural Language Processing (NLP)
* Large Language Models (LLM)
* MLOps
* PyTorch
* TensorFlow
* Exploratory Data Analysis
* Computer Vision
* Data Visualization
* GPT-3
* Artificial Intelligence (AI)
* Data Science
* Time Series Analysis
* Deep Learning
* Machine Learning
* Python (Programming Language)
* Fine Tuning LLM's
* Computer Vision
* Convolutional Neural Networks
* Recurrent Neural Networks
* Long Short-Term Memory (LSTM)
* Generative Adversarial Networks (GAN)
* Cloud Computing
* Data Mining
* Prompt Engineering

Publications
============

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Competitions
============

<ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
========

<ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======================

* Currently signed in to 43 different slack teams
