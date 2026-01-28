# Stellar Luminosity – Linear and Polynomial Regression

This project implements linear regression and polynomial regression from first principles to model stellar luminosity as a function of stellar mass and temperature. The project is developed as part of a Machine Learning Bootcamp within a course on Digital Transformation and Enterprise Architecture, emphasizing how intelligent models are built, optimized, and executed in cloud environments.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. Instructions for cloud execution using AWS SageMaker are included in the Deployment section.

### Prerequisites

You need the following software installed:

- Python 3.10.6
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


### Break down into end to end tests

End-to-end validation consists of:
- Running all notebook cells without errors
- Verifying that the loss decreases over training iterations
- Confirming that predicted luminosity values are reasonable compared to the observed data

Example:

```
Execute all cells in the notebook and verify that the final loss value is significantly lower than the initial loss
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

## both notebooks visible/open in SageMaker

The image shows the workbooks open in the AWS virtual environment

<img width="1386" height="800" alt="Captura de pantalla 2026-01-27 a la(s) 11 13 59 p m" src="https://github.com/user-attachments/assets/3f1a3868-76ed-4ede-a517-550fc9ae7f44" />

## successful execution (cells run and outputs visible)

Successful execution in the virtual environment

<img width="1069" height="620" alt="Captura de pantalla 2026-01-27 a la(s) 11 15 41 p m" src="https://github.com/user-attachments/assets/8a4817e2-dc3d-458c-a0b1-24d6b59d503e" />


Successful execution in my remote Visual Studio

<img width="1180" height="822" alt="Captura de pantalla 2026-01-27 a la(s) 11 16 57 p m" src="https://github.com/user-attachments/assets/9dfd1d0b-daef-4b4e-8e9f-56926fba3551" />

## Rendered plot in SageMaker

Code execution in SageMaker for corresponding graphs


<img width="562" height="695" alt="Captura de pantalla 2026-01-27 a la(s) 11 18 25 p m" src="https://github.com/user-attachments/assets/1832d397-4d64-49e3-837c-4c5bf5ad86e6" />


## Comparison: Local vs. AWS SageMaker Execution

Runtime Performance:
For the small datasets used, both local execution and SageMaker produce similar results. However, some cells in SageMaker took slightly longer to execute compared to local runs.

Environment Consistency:
SageMaker provides a standardized, pre-configured environment, reducing issues related to local dependency management.

Startup and Initialization:
Local notebooks start almost instantly, while SageMaker requires additional time to initialize the instance and kernel.

Visualization and Outputs:
Matplotlib inline plots render correctly in both environments without noticeable differences.

Architectural Perspective:
Executing the notebooks in SageMaker illustrates how model training can be moved to cloud infrastructure, which is essential for scalable enterprise intelligence.


'' Testing the difference in execution time ''

<img width="1166" height="497" alt="Captura de pantalla 2026-01-27 a la(s) 11 22 31 p m" src="https://github.com/user-attachments/assets/f28e5105-d11a-4d4a-aeef-86328e4c1944" />

<img width="1114" height="418" alt="Captura de pantalla 2026-01-27 a la(s) 11 22 46 p m" src="https://github.com/user-attachments/assets/d6d50c2b-955b-451a-b206-a67e5f66aee4" />



## Deployment

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
