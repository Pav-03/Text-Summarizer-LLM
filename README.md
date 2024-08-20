# Text-Summarizer-LLM


This is a Text Summarization project that aims to generate concise summaries from given text documents using Natural Language Processing (LLM) techniques. The project includes various components and workflows to facilitate the text summarisation process.


## Introduction

Text summarization is a critical application of Natural Language Processing (NLP), particularly in scenarios where large volumes of text need to be condensed efficiently. This repository chronicles the development and deployment of a sophisticated text summarization model, highlighting the fine-tuning of a HuggingFace Transformer model on custom datasets and its deployment using AWS.


## Project Overview

This repository provides a comprehensive guide to the end-to-end process of building and deploying a text summarization model. Key areas covered include:

1. Fine-tuning Large Language Models (LLMs): Leveraging custom data to enhance  the performance of the HuggingFace Transformer model.

2. Dataset Description: Detailed insights into the datasets used for training and validation.

3. Project Timeline: An overview of the project's phases from inception to deployment.

4. Setup and Development: Step-by-step instructions on setting up the development environment and the progression through different stages of model development.

5. Deployment on AWS: Guidance on deploying the model using AWS services such as EC2, ECR, and GitHub Actions.

This project also emphasizes modular coding practices, Dockerized deployments, and the implementation of CI/CD workflows to ensure robust, maintainable, and scalable code.


## Features

1. Model Fine-Tuning: Fine-tuning a HuggingFace Transformer model on custom data to enhance summarization capabilities.

2. AWS Deployment: Deploying the model seamlessly using AWS services, including EC2, ECR, and GitHub Actions.

3. Modular Codebase: Adopting modular coding practices for improved code organization and maintainability.

4. FastAPI Integration: Utilizing FastAPI to create an intuitive and user-friendly interface for interacting with the model.

5. CI/CD Workflows: Implementing Continuous Integration and Continuous Deployment (CI/CD) workflows using GitHub Actions to streamline the development process.
Installation


## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Pav-03/Text-Summarizer-LLM.git
   cd end-to-end-text-summarizer
   
2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt

3. **Setup and Fine-Tuning:**

Follow the detailed setup instructions provided in the repository to fine-tune the model, configure the development environment, and deploy the application on AWS.


## Note

The accuracy of the text summarization model can be further improved by adjusting various hyperparameters such as epochs, batch size, and beam size. Due to GPU limitations, this model has been fine-tuned using the highest feasible parameters. However, with greater computational power, the model's performance, as measured by the ROUGE score, can be significantly enhanced. Despite these constraints, the model demonstrates strong performance with the current configuration.
