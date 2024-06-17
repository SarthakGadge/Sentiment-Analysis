<!DOCTYPE html>
<html lang="en">

<body>

<h1>Sentiment Analysis Project</h1>

<p>Welcome to the Sentiment Analysis Project! This repository contains code and resources for performing sentiment analysis using Hugging Face's Transformers library and uses the BERT model for analysis. This project is designed to be simple and easy to understand, making it a great starting point for anyone interested in natural language processing (NLP) and sentiment analysis.</p>

<h2>Table of Contents</h2>
<ul>
    <li>Overview</li>
    <li>Installation</li>
    <li>Usage</li>
    <li>Data Scrapping</li>
    <li>Model fitting</li>
    <li>Interpretting the results </li>
</ul>

<h2 id="overview">Overview</h2>
<p>Sentiment analysis is the process of determining the emotional tone behind a series of words. It is commonly used to understand the sentiment of user reviews, social media posts, and other forms of text. This project leverages the power of Hugging Face's Transformers library to build and fine-tune a model for sentiment analysis.</p>

<h2 id="installation">Installation</h2>
<p>To get started, clone the repository and install the necessary dependencies:</p>
<pre><code>git clone https://github.com/your-username/sentiment-analysis-project.git
cd sentiment-analysis-project
pip install -r requirements.txt
</code></pre>
<p>The <code>requirements.txt</code> file contains the following dependencies:</p>
<pre><code>transformers
torch
datasets
scikit-learn
</code></pre>

<h2 id="usage">Usage</h2>

<h3 id="dataset">Data Scrapping</h3>
<p>To perform sentiment analysis, you will need a dataset, here we have opted for web scrapping and scrape reviews off of the YELP websites for top restaurants 


</code></pre>

<h3 id="model-training">Model Fitting</h3>
<p>You can fine-tune a pre-trained Transformer model on your data. 

<h3 id="inference">Inference</h3>
<p>After training, you can use the fine-tuned model to nderstand the reviews, Here we have Used the pretrained BERT model which outputs a score from 1 to 5, so a positive review will get 5 stars but a negative review
will score 1-2 and of course revies fallng in the middle will get a 3 to 4.



<p>Happy coding! If you have any questions, feel free to reach out.</p>

</body>
</html>
