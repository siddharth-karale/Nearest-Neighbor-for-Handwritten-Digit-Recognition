# Nearest Neighbor for Handwritten Digit Recognition

This repository implements a Nearest Neighbor classifier for recognizing handwritten digits from the MNIST dataset.

## Requirements

* Python 3.x
* numpy
* matplotlib
* scikit-learn

## MNIST Dataset

The MNIST dataset is a classic dataset in machine learning for handwritten digit recognition. This implementation uses a subset of the dataset containing 7,500 training examples and 1,000 testing examples.

## Usage

1. Clone this repository.
2. Install the required libraries (`numpy`, `matplotlib`, and `scikit-learn`).
3. Run the script (`NEAREST NEIGHBOUR FOR HANDWRITTEN DIGIT RECOGNITION.ipynb` or your equivalent).

The script will:

* Load the MNIST dataset.
* Visualize some examples of handwritten digits.
* Implement a nearest neighbor classifier using squared Euclidean distance.
* Evaluate the performance of the classifier on the test set.
* Utilize BallTree and KdTree from scikit-learn for faster nearest neighbor search.

## Performance

The script reports the error rate and classification time of the nearest neighbor classifier. Additionally, it compares the classification times using BallTree and KdTree to the naive implementation.

## Conclusion

This project demonstrates a simple nearest neighbor approach for handwritten digit recognition. While the naive implementation is slow, scikit-learn's BallTree and KdTree offer significant speed improvements for nearest neighbor search.

