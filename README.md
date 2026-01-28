# Stellar Luminosity – Linear and Polynomial Regression

This project implements linear regression and polynomial regression from first principles to model stellar luminosity as a function of stellar mass and temperature. The project is developed as part of a Machine Learning Bootcamp within a course on Digital Transformation and Enterprise Architecture, emphasizing how intelligent models are built, optimized, and executed in cloud environments.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. Instructions for cloud execution using AWS SageMaker are included in the Deployment section.

### Prerequisites

You need the following software installed:

- Python 3.9 or later
- Jupyter Notebook or Jupyter Lab

Allowed Python libraries (as specified in the assignment):

```
numpy
matplotlib
```

High-level machine learning libraries such as scikit-learn, TensorFlow, or PyTorch are not used.

### Installing

A step by step series of examples that tell you how to get a development environment running.

Create and activate a virtual environment (optional but recommended):

```
python -m venv .venv
source .venv/bin/activate
```

Install the required dependencies:

```
pip install numpy matplotlib jupyter
```

Start Jupyter Notebook:

```
jupyter notebook
```

Open one of the notebooks, for example:

```
01_part1_linreg_1feature.ipynb
```

Run all cells to visualize the dataset, train the regression models, and observe convergence behavior and final predictions.

## Running the tests

This project does not include automated unit tests. Validation is performed through numerical results and visual inspection, which is standard for exploratory machine learning notebooks.

### Break down into end to end tests

End-to-end validation consists of:
- Running all notebook cells without errors
- Verifying that the loss decreases over training iterations
- Confirming that predicted luminosity values are reasonable compared to the observed data

Example:

```
Execute all cells in the notebook and verify that the final loss value is significantly lower than the initial loss.
```

### And coding style tests

Coding style validation focuses on:
- Clear separation of model, loss, and optimization logic
- Explicit implementation of gradient descent
- Proper use of NumPy vectorization where required

Example:

```
Review the notebook code to ensure no high-level ML libraries are imported and that vectorized operations replace explicit loops where specified.
```

## Deployment

No production deployment is required for this project.  
The notebooks must be uploaded and executed in AWS SageMaker Studio (AWS Academy environment) as execution evidence for the assignment. All cells must run successfully and produce visible outputs and plots.

## Built With

* Python – Core programming language
* NumPy – Numerical computation
* Matplotlib – Data visualization
* Jupyter Notebook – Interactive development environment
* AWS SageMaker Studio – Cloud execution platform

## Contributing

This project is developed for academic purposes. External contributions are not expected.

## Versioning

Versioning is not applied, as this project corresponds to a single academic deliverable.

## Authors

* **Valentina Gutiérrez** – Initial work and implementation

## License

This project is for academic use only as part of a university course assignment.

## Acknowledgments

* Course instructors for guidance on machine learning and enterprise architecture concepts  
* AWS Academy for providing cloud infrastructure  
* Astronomical examples inspired by main-sequence stellar behavior
