# Using AI to process stream data from Apache Kafka topic
This repository contains code for two demos showcasing how to use AI Models and Amazon SageMaker to analyse data flowing from Apache Kafka topic. The data is processed using AI model and send into a separate topic.

## Demo 1: social media posts 
Messages are processed one by one and we use two models to get sentiment analysis and offensiveness score. Origin of data is Mastodon, you can load Mastodon data by following the steps described in this article - https://aiven.io/developer/mastodon-kafka-js.

## Demo 2: Amazon reviews
Each review is processed using two AI models - one to get sentiment analysis and another to classify the review.
Data is taken from Amazon Fine Food Reviews dataset - https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

## Visualisation
You can visualise the results with OpenSearch Dashboards. You'll find an example of Kafka-OpenSearch connector in the file  opensearch-connector.json.
