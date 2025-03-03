# CS106 Project - Artificial Intelligence

## Video Summarization with Reinforcement Learning

This project is based on the paper [Deep Reinforcement Learning for Unsupervised Video Summarization with Diversity-Representativeness Reward](https://arxiv.org/pdf/1801.00054). The goal of this project is to apply reinforcement learning to train a **Deep Summarization Network (DSN)** for automatic video summarization.

The method used in this project does not require labeled data. Instead, the system utilizes a reward function to assess the **diversity** and **representativeness** of the summary text. This enables the creation of high-quality video summaries that accurately reflect the content of the video without relying on labeled training data.

## Main Components:
- **Deep Summarization Network (DSN):** A deep network used for video summarization.
- **Reinforcement Learning:** A machine learning technique to train the model without the need for labeled data.
- **Diversity and Representativeness Reward Function:** Evaluates the quality of video summaries based on the representativeness of the scenes and the diversity within the summary.
