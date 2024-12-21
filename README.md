# AI-Based Turbulence Modeling with Machine Learning

This project explores the use of **Artificial Intelligence (AI)** and **Machine Learning (ML)** techniques to assist in modeling turbulence, a complex phenomenon in fluid dynamics. Specifically, the project leverages methods like **Neural Networks**, **Regression**, and **Deep Learning** models to predict or approximate turbulence closures in fluid flow simulations. The work is based on the **Johns Hopkins Turbulence Database (JHTDB)** and follows the methodologies described in the paper [DOI: 10.1007/s40314-023-02547-9](https://doi.org/10.1007/s40314-023-02547-9).

## Table of Contents
1. [Project Overview](#project-overview)
2. [Research and Methodology](#research-and-methodology)
3. [Data Selection](#data-selection)
4. [Model Implementation](#model-implementation)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Evaluation and Results](#evaluation-and-results)
8. [License](#license)

---

## Project Overview

The objective of this project is to implement machine learning models to enhance turbulence modeling in computational fluid dynamics (CFD) simulations. Traditional turbulence models, such as **RANS (Reynolds-Averaged Navier-Stokes)** and **LES (Large Eddy Simulation)**, often struggle with capturing the full complexity of turbulent flows. Machine learning techniques, particularly **neural networks**, can potentially provide a more accurate and computationally efficient approach for predicting turbulence closures.

---

## Research and Methodology

In this project, we explore the use of machine learning techniques for turbulence modeling, with a focus on:
- **Neural Networks**: To predict or enhance existing turbulence models.
- **Regression Techniques**: To model the turbulence behavior based on available CFD data.
- **Deep Learning Models**: For more complex, high-dimensional turbulence data.
---

## Data Selection

The primary dataset used in this project is the **Johns Hopkins Turbulence Database (JHTDB)**. This dataset contains high-resolution, time-varying simulations of turbulent flows and is ideal for training and testing machine learning models. The data is available for various turbulence conditions and is widely used in turbulence research.

---

## Model Implementation

The machine learning model is implemented as a **Feedforward Neural Network** (FNN), using **Python** and libraries like **TensorFlow**, **Keras**, and **NumPy**. The model is trained to predict the turbulence closures (such as Reynolds stresses) based on CFD simulation data.

Key steps in the implementation:
1. **Data Preprocessing**: Clean and preprocess the JHTDB dataset for input to the machine learning model.
2. **Model Architecture**: Design and train a simple feedforward neural network to predict turbulence quantities.
3. **Evaluation**: Evaluate the model’s performance against traditional turbulence models (e.g., RANS, LES).

---

## Installation

To run the project locally, follow these steps:

### Prerequisites
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Pandas
- JHTDB Data (available upon request from the JHTDB website)

### Download the JHTDB dataset
Download the relevant dataset from the **JHTDB website** (details in the "Data Selection" section).

---

## Usage

Once the project is set up, you can run the following Python script to train and evaluate the model:


The training script will preprocess the data, train the neural network, and save the model weights. The evaluation script will compare the model’s predictions with traditional turbulence models (e.g., RANS, LES).

---

## Evaluation and Results

The model is evaluated on various performance metrics, including:
- **Accuracy**: How well the model predicts turbulence closures (e.g., Reynolds stresses).
- **Comparison with Traditional Models**: The model's performance is compared against traditional turbulence models like **RANS** and **LES** in terms of computational cost and prediction accuracy.

Expected outcomes:
- A working machine learning model that improves or enhances existing turbulence models.
- A detailed comparison with traditional models, showcasing the potential benefits of AI-based turbulence modeling.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- The **Johns Hopkins Turbulence Database (JHTDB)** for providing high-quality CFD data.
- The research paper [DOI: 10.1007/s40314-023-02547-9](https://doi.org/10.1007/s40314-023-02547-9) for inspiration and methodology.
