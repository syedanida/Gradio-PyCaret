<h1>Gradio-Based Machine Learning Examples: Text and Image Classification</h1>

<p>This repository contains two interactive machine learning examples using <a href="https://gradio.app/" target="_blank">Gradio</a>, a Python library that simplifies the process of creating user-friendly web interfaces for ML models. These examples demonstrate how to build and deploy text classification and image classification models, making it easy to interact with and visualize the predictions.</p>

<h2 id="introduction">Introduction</h2>
<p>In this project, we explore the application of machine learning models using Gradio for:</p>
<ul>
    <li><strong>Text Classification</strong>: A model trained to predict the sentiment of tweets related to airlines.</li>
    <li><strong>Image Classification</strong>: A model that identifies the class of an image from a predefined set of categories.</li>
</ul>
<p>These examples demonstrate how easy it is to integrate interactive web UIs with machine learning models and make them accessible to users. Each example includes the code, as well as instructions to run it on Google Colab.</p>

<h2 id="example-1-text-classification">Example 1: Text Classification</h2>
<p>In this example, we create a text classification model using PyCaret and Gradio to classify airline-related tweets into different sentiment categories: positive, negative, or neutral.</p>

<h3>Dataset</h3>
<p>We use the <a href="https://www.kaggle.com/crowdflower/twitter-airline-sentiment" target="_blank">Airline Sentiment Dataset</a> from Kaggle, which contains tweets about airlines labeled with sentiments.</p>

<h3>Steps:</h3>
<ol>
    <li><strong>Model Training</strong>: We use PyCaret's Natural Language Processing (NLP) module to train a model on the dataset.</li>
    <li><strong>Gradio Interface</strong>: A Gradio interface is created that allows users to input their own tweets and receive predicted sentiments.</li>
</ol>

<h3>Key Features:</h3>
<ul>
    <li>The model takes user input (a tweet) and classifies it as <strong>positive</strong>, <strong>negative</strong>, or <strong>neutral</strong>.</li>
    <li>The output displays the predicted sentiment label along with a confidence score.</li>
</ul>


<h2 id="example-2-image-classification">Example 2: Image Classification</h2>
<p>This example shows how to build a simple image classification interface using a pre-trained model and Gradio. The model predicts which class an image belongs to from a list of common objects.</p>

<h3>Dataset</h3>
<p>We utilize a pre-trained model from PyCaret’s image classification module, which can classify a wide variety of image categories.</p>

<h3>Steps:</h3>
<ol>
    <li><strong>Model Setup</strong>: We load a pre-trained image classification model using PyCaret.</li>
    <li><strong>Gradio Interface</strong>: A Gradio interface is created where users can upload an image to classify it into one of the pre-defined categories.</li>
</ol>

<h3>Key Features:</h3>
<ul>
    <li>Upload an image and get real-time predictions of the class (e.g., cat, dog, etc.).</li>
    <li>Displays the top predicted class along with the confidence score.</li>
</ul>

<h2 id="video-tutorials">Video Tutorials</h2>
<p>Watch the full tutorial on how to implement these examples:</p>
<ul>
    <li><strong>Text Classification Tutorial</strong>: <a href="#link-to-video-1" target="_blank">Watch Here</a></li>
    <li><strong>Image Classification Tutorial</strong>: <a href="#link-to-video-2" target="_blank">Watch Here</a></li>
</ul>

</body>
