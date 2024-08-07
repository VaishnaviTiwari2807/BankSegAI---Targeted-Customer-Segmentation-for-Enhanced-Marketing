# Customer Segmentation for Enhanced Marketing

## Introduction
Marketing is crucial for the growth and sustainability of any business. Effective marketing strategies help build the company's brand, engage customers, grow revenue, and increase sales. One of the key challenges for marketers is to know their customers and identify their needs. By understanding the customer, marketers can launch targeted marketing campaigns tailored to specific needs.

## Problem Statement
The marketing team at a bank  wants to launch a targeted ad marketing campaign. To achieve this, they need to divide their customers into at least three distinctive groups. The bank has extensive data on their customers' transactional behaviors and financial profiles over the past six months. This data provides an excellent opportunity to apply data science techniques for market segmentation.

## Objective
To segment the bank's customers using Autoencoders and clustering techniques, based on their transactional behaviors and financial profiles. The segmentation results will be utilized to design targeted marketing campaigns, aiming to enhance customer engagement and optimize resource allocation.

## Key Features
- **Segmentation Modeling:** Application of K-means clustering to segment customers into distinct groups based on behavioral and financial characteristics.
- **Customer Data Analysis:** Exploration and preprocessing of customer financial data including balance, purchases, and cash advances.
- **Data Preprocessing**: Cleansing and normalization of customer transactional data.
- **Visualization:** Graphical representation of data distributions and clustering results to provide intuitive insights into customer groups.
- **Segmentation Modeling:** Application of K-means clustering to segment customers into distinct groups based on behavioral and financial characteristics.
- **Dimensionality Reduction**: Implementation of Autoencoders to reduce feature dimensions while capturing essential information.

## Technologies Used
- TensorFlow for building and training the Autoencoder model.
- Keras for model architecture and execution.
- Scikit-learn for applying clustering algorithms and additional preprocessing.

## Model Architecture
The clustering is performed on the encoded data to ensure that customers with similar financial behaviors are grouped together.

The Autoencoder used in this project is designed with the following layers:
- **Input Layer**: 17 features representing various customer attributes.
- **Encoding Layer**: Compressed representation with an encoding dimension of 7.
- **Decoding Layer**: Reconstruction of the input data from the encoded representation.



