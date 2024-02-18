### Project README

---

#### Multi-Class Classification with PyTorch

---

### Overview:

This project implements a multi-class classification task using PyTorch, focusing on creating synthetic data, building a neural network model, training the model, and evaluating its performance.

### Dependencies:

- Python 3.x
- PyTorch
- NumPy
- Matplotlib
- Scikit-learn

### Setup:

1. Clone the repository.
2. Ensure all dependencies are installed using pip or conda.
3. Run the provided script.

### Project Structure:

- **main.py**: Python script containing the project code.
- **helper_functions.py**: Helper functions for plotting predictions and decision boundaries.
- **README.md**: Instructions and information about the project.

### How to Use:

1. Run the `main.py` script.
2. The script will download the necessary helper functions if not already present.
3. Synthetic multi-class data is generated and split into training and test sets.
4. A neural network model is built using PyTorch.
5. The model is trained using the training data.
6. Training progress and metrics are displayed.
7. Model predictions are evaluated on the test set.
8. Decision boundaries and model performance are visualized using Matplotlib.

### Important Notes:

- The script supports both CPU and GPU training depending on the availability of CUDA.
- Hyperparameters such as learning rate, number of hidden units, and epochs can be adjusted for experimentation.
- The dataset used in this project is synthetic and generated using scikit-learn's `make_blobs` function.
- The model architecture consists of linear layers with the option to include non-linear activation functions (ReLU), which can be experimented with.
- The project provides insights into how to build, train, and evaluate a simple neural network for multi-class classification tasks using PyTorch.

### License:

This project is licensed under the MIT License.

---

Feel free to contribute, modify, or expand upon this project as needed. If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue. Thank you for using this project!
