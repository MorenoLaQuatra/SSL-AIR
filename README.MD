# SSL-based Sequence Matching for Unsupervised Audio Retrieval

This repository contains the code for the paper "SSL-based Sequence Matching for Unsupervised Audio Retrieval". The paper is currently under review and this repository will be updated with the link to the paper once it will be published.

### Problem Statement

Given a query audio sequence, the task is to retrieve the most similar audio sequences from a large unlabelled dataset. 
This is a challenging problem as the audio sequences can be of different lengths and the similarity between the sequences is not only dependent on the content but also on the temporal alignment of the content.

- We leverage Transformer-based, Self-Supervised Learning (SSL) models to extract audio representations.
- We investigate the use of dynamic time warping (DTW) on embeddings or TF-IDF/BM25 on discrete units for sequence matching.
- We evaluate the proposed approach on query-by-humming and query-by-example tasks.

> [!IMPORTANT]  
> 🚨 The repository is under construction and will be updated with data, code, and instructions after the review process is completed.