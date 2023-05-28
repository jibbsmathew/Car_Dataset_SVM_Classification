# Dataset for Car Classification

This repository provides a dataset for car classification, consisting of attributes related to car buying, maintenance, doors, persons, luggage boot, safety, and the overall classification of the car. The dataset contains 1,728 instances with 7 columns.

## Dataset Description

The dataset contains the following columns:

- `buying`: Represents the buying price of the car.
- `maint`: Represents the maintenance price of the car.
- `doors`: Represents the number of doors.
- `persons`: Represents the seating capacity of the car.
- `lug_boot`: Represents the size of the luggage boot.
- `safety`: Represents the safety rating of the car.
- `car`: Represents the overall classification of the car.

The dataset statistics are as follows:

- Count: 1,728
- Unique values: 
  - `buying`: 4
  - `maint`: 4
  - `doors`: 4
  - `persons`: 3
  - `lug_boot`: 3
  - `safety`: 3
  - `car`: 4
- Most frequent values:
  - `buying`: vhigh
  - `maint`: vhigh
  - `doors`: 2
  - `persons`: 2
  - `lug_boot`: small
  - `safety`: low
  - `car`: unacc (unacceptable)

## Prerequisites

To implement classification models and analyze the results, the following prerequisites are needed:

- Python 3 (https://www.python.org/downloads/)
- NumPy (http://www.numpy.org/)
- Pandas (https://pandas.pydata.org/)
- Scikit-learn (https://scikit-learn.org/stable/)

It's recommended to set up a virtual environment to keep your dependencies isolated.

## Getting Started

1. Clone this repository:

```shell
git clone https://github.com/your-username/car-classification.git
```

2. Change into the project directory:

```shell
cd car-classification
```

3. Install the required dependencies:

```shell
pip install -r requirements.txt
```

## Usage

The provided dataset can be used to implement various classification models, such as SVM, polynomial SVM, and RBD SVM. The steps to implement these models and plot ROC curves are as follows:

1. Load the dataset using Pandas.
2. Perform any necessary preprocessing steps, such as encoding categorical variables or scaling numerical features.
3. Split the dataset into training and testing sets.
4. Implement and train the SVM model using Scikit-learn's SVM implementation.
5. Implement and train the polynomial SVM model using Scikit-learn's SVC implementation with a polynomial kernel.
6. Implement and train the RBD SVM model using Scikit-learn's SVC implementation with an RBF kernel.
7. Evaluate the performance of each model using appropriate metrics, such as accuracy, precision, recall, or F1-score.
8. Plot the ROC curves for each model and analyze the results.
9. Make any necessary adjustments or optimizations to improve the models' performance.
