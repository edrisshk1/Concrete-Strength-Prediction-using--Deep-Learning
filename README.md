# 🧱 Concrete Strength Prediction using Deep Learning

This repository contains a model training and evaluation for the prediction of concrete compressive strength prediction using a Concrete info dataset from Kaggle using multiple libraries especially Keras which is an upper layer using the low layer library TensorFlow developed and maintained by Google for building and training neural networks and Scikit-learn for model evaluation.

![concrete](https://github.com/edrisshk1/Concrete-Strength-Prediction-using-Deep-Learning/assets/122979130/eda3aba5-7a3d-4a1e-952a-2454f2a96277)

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Models](#models)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction

Concrete is a fundamental construction material utilized in various infrastructural projects. Accurately predicting its compressive strength is crucial for ensuring the safety and longevity of buildings and structures. In this deep learning project, we focus on developing robust predictive models using deep learning techniques with Keras. By analyzing diverse input parameters and historical concrete strength data, our objective is to create reliable and precise predictions. Join us on this journey to harness the power of neural networks for enhanced concrete strength forecasting, revolutionizing the way we approach construction and engineering practices.

## Dataset

The data can be gathered from [URL to Dataset Source](http://www.bom.gov.au/climate/dwo/.)

The dataset is about the compressive strength of different samples of concrete based on the volumes of the different ingredients that were used to make them. Ingredients include:

1. Cement
2. Blast Furnace Slag
3. Fly Ash
4. Water
5. Superplasticizer
6. Coarse Aggregate
7. Fine Aggregate

## Installation

To run the code in this repository, follow these installation instructions:

1. Clone this repository to your local machine using the following command:

   ```
   git clone thttps://github.com/edrisshk1/Rain-Prediction-In-Australia
   ```
2. Download the Dataset
3. Open Jupyter Notebook:

   ```
   jupyter notebook
   ```
4. Follow the instructions within the notebooks to preprocess the data, train the deep learning models, and make predictions.

## Models

We build different neural networks using different numbers of hidden layers, different numbers of nodes in each hidden layer, and different training epochs.

We used ReLu as the activation function, Adam Optimizer, and Mean Squared Error for loss calculations.

## Evaluation

To evaluate our models, we used :

- Mean Squared Error between the predicted concrete strength and the actual concrete strength.
- Log Loss

## Results

The evaluation results and insights are summarized in the notebooks. 

## Contributing

Contributions to this project are welcome! If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch to your fork.
4. Submit a pull request, detailing the changes you made.

## Acknowledgements

I want to thank the following organizations for their contributions and the amazing tools provided to accomplish this project :
- **Coursera**: This platform gave me the idea for the project and provided me with the tools needed for this project.
- **Kaggle & Google Colab**: These platforms provided me with the workspace and the processing power needed to train and evaluate the models
- The contributors to **Keras & scikit-learn**’s development and maintenance

## License

This project is licensed under the [MIT License](LICENSE).
