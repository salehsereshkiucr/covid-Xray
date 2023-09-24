# COVID-19 Detection Using X-ray Images

## Project Overview

This project is an exploration into the capabilities of utilizing X-ray images for the detection of COVID-19 cases. Leveraging a robust dataset and advanced machine learning techniques, the endeavor aims to lay the groundwork for improved diagnostic procedures and enhance our understanding of how imaging can contribute to tackling the pandemic.

## Dataset

The dataset is comprised of the following X-ray images:

- 219 images of COVID-19 cases
- 1345 images of Viral Pneumonia cases
- 1341 images of normal chest X-rays

### Dataset Distribution

The table below provides a detailed distribution of the raw and augmented datasets used in this project for training, validation, and testing:

| Class Label | Raw Train | Raw Valid. | Raw Test | Augmented Train | Augmented Valid. | Augmented Test |
|-------------|-----------|------------|----------|------------------|------------------|-----------------|
| COVID-19    | 141       | 35         | 43       | 2820             | 700              | 43              |
| Normal      | 858       | 215        | 268      | 2574             | 645              | 268             |
| Pneumonia   | 861       | 215        | 269      | 2583             | 645              | 269             |

*Table I: COVID-19 dataset with class distributions.*

## Methodology

The approach employed in this project involves the application of transfer learning and hyper-parameter optimization to train a variety of models. The models implemented include:

- AdaBoost
- CNN+XGBoost

### AdaBoost

AdaBoost emerged as the most successful model in terms of accuracy, demonstrating the potential for ensemble learning in medical image analysis.

### CNN+XGBoost

This model is a hybrid approach, combining Convolutional Neural Networks (CNN) with XGBoost, showing promise in extracting features and handling classification tasks.

## Augmented Data and Self-Supervised Learning

The project also delves into testing the models with augmented data and discusses the prospects of self-supervised learning. The exploration points towards the possibility that, given a larger dataset, self-supervised learning could play a pivotal role in enhancing the model's performance.

## Conclusion and Future Work

The report concludes that the current models, if supplied with more data, can be trained to detect COVID-19 cases with higher accuracy. This study serves as a stepping stone towards the development of more refined and accurate models for detecting COVID-19 through X-ray images, thereby contributing to the ongoing efforts against the pandemic.

