# Text-Summarizer-LLM


This is a Text Summarization project that aims to generate concise summaries from given text documents using Natural Language Processing (LLM) techniques. The project includes various components and workflows to facilitate the text summarisation process.


## Introduction

Text summarization is a critical application of Natural Language Processing (NLP), particularly in scenarios where large volumes of text need to be condensed efficiently. This repository chronicles the development and deployment of a sophisticated text summarization model, highlighting the fine-tuning of a HuggingFace Transformer model on custom datasets and its deployment using AWS.

## Project Overview

This repository provides a comprehensive guide to the end-to-end process of building and deploying a text summarization model. Key areas covered include:

Fine-tuning Large Language Models (LLMs): Leveraging custom data to enhance  the performance of the HuggingFace Transformer model.

Dataset Description: Detailed insights into the datasets used for training and validation.

Project Timeline: An overview of the project's phases from inception to deployment.

Setup and Development: Step-by-step instructions on setting up the development environment and the progression through different stages of model development.

Deployment on AWS: Guidance on deploying the model using AWS services such as EC2, ECR, and GitHub Actions.

This project also emphasizes modular coding practices, Dockerized deployments, and the implementation of CI/CD workflows to ensure robust, maintainable, and scalable code.

## Features

Model Fine-Tuning: Fine-tuning a HuggingFace Transformer model on custom data to enhance summarization capabilities.

AWS Deployment: Deploying the model seamlessly using AWS services, including EC2, ECR, and GitHub Actions.

Modular Codebase: Adopting modular coding practices for improved code organization and maintainability.

FastAPI Integration: Utilizing FastAPI to create an intuitive and user-friendly interface for interacting with the model.

CI/CD Workflows: Implementing Continuous Integration and Continuous Deployment (CI/CD) workflows using GitHub Actions to streamline the development process.
Installation

## To install the required dependencies, execute the following command:


pip install -r requirements.txt

## Usage

### Clone the repository:

git clone https://github.com/Pav-03/Text-Summarizer-LLM.git

cd end-to-end-text-summarizer

### Install dependencies:

pip install -r requirements.txt

### Setup and Fine-Tuning:

Follow the detailed setup instructions provided in the repository to fine-tune the model, configure the development environment, and deploy the application on AWS.

## Note

The accuracy of the text summarization model can be further improved by adjusting various hyperparameters such as epochs, batch size, and beam size. Due to GPU limitations, this model has been fine-tuned using the highest feasible parameters. However, with greater computational power, the model's performance, as measured by the ROUGE score, can be significantly enhanced. Despite these constraints, the model demonstrates strong performance with the current configuration.