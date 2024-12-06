# Cat vs Dog Classification Project

## Overview
This project aims to build a machine learning model that classifies images of cats and dogs, using TensorFlow. The model learns by analyzing images from a specified dataset and outputs predictions based on new input images.

## Table of Contents
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Dataset](#dataset)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Installation

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Set Up Anaconda Environment**
   ```bash
   conda create --name CleanMLEnv python=3.10
   conda activate CleanMLEnv
   conda install -c conda-forge notebook tensorflow opencv matplotlib
   python -m ipykernel install --user --name=CleanMLEnv --display-name="Python (Clean ML)"
   ```

## Getting Started

1. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

2. **Open the Notebook**
   Navigate to the notebook you want to run (located in your project directory) and select the `Python (Clean ML)` kernel.

3. **Run the Cells**
   Execute the cells in order to preprocess the data, build the model, and make predictions.

## Dataset

The dataset used in this project is a collection of images of cats and dogs, downloaded from this link: `https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765`

## Usage

- Load the dataset and preprocess the images.
- Train the machine learning model on the images.
- Evaluate its performance using test data.
- Visualize the results.

### Example Commands
To visualize the first image after loading:
```python
plt.imshow(x_train[0], cmap='gray')
plt.show()
```

## Dependencies

- Python 3.10
- TensorFlow
- NumPy
- Matplotlib
- OpenCV
- Jupyter Notebook

You can install the dependencies using Anaconda with the specified commands above.
