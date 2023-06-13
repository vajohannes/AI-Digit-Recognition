# AI-Digit-Recognition
Use STL from C++ to do data preprocessing and network testing.

This project focuses on digit recognition using a simple neural network and a dataset of handwritten digits. The dataset is split into "train" and "test" sets, with the "train" set used for training the network and the "test" set used for evaluating the network's performance. A complete and class-balanced "train" set is important for achieving high accuracy.\

The program pipeline involves training a network with the complete and class-balanced "train" data, testing it on the "test" data, and reporting overall and digit-wise accuracy. The next step is to remove part of the "train" data for a digit, create a class-imbalanced dataset, and retrain the network to test accuracy for that specific digit. Finally, we generate more "train" data for the imbalanced digit by applying geometrical transformations like shifting, resizing, and cropping.\

Throughout the assignment, we will use STL containers, iterators, algorithms, and function objects to implement data preprocessing and network testing.
