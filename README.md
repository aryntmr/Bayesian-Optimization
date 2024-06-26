# Bayesian Optimization for Neural Network Architecture

## Overview

This project compares the performance of Bayesian Optimization and Grid Search for finding optimal neural network architecture hyperparameters.

## Project Details

**Objective:** Implement Bayesian Optimization and Grid Search to find the optimal neural network architecture for a classification task.

**Models Implemented:**
- ResNet18

**Evaluation Metrics:**
- Performance evaluated based on accuracy and computational efficiency.

**Key Contributions:**
- Demonstrated the effectiveness of Bayesian Optimization in finding optimal hyperparameters with reduced computational time.
- Highlighted the limitations of traditional grid search methods, which are taking almost infinite durations of time.
- For this project we searched through 10-500 number of nodes for four hidden layers and two activation function, run for 25 epochs. The time taken by Bayesian opt was 28 mins on average (tested 7 times) whereas the time taken by Grid Search was 65 hours.

## Dataset

The Sign Language Digit dataset was used for training and evaluation. This dataset contains images of hand gestures representing digits from 0 to 9 in sign language. Dataset can be found at: https://drive.google.com/file/d/1ZnZYPKxPIe68OrL6LP_gaBMlzh9n38ge/view?usp=sharing.

## Files

- `Bayesian_Optimization.ipynb`: Jupyter Notebook containing the implementation of Bayesian Optimization and Grid Search.

## Usage

1. Clone the repository.
2. Ensure the necessary dependencies are installed.
3. Run the provided Jupyter Notebooks (`Bayesian_Optimization.ipynb`) to execute Bayesian Optimization and Grid Search.

## References

- https://www.cmi.ac.in/~madhavan/courses/aml2021/

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
