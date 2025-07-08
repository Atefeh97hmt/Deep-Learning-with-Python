Deep Learning Python Repository
Welcome to the Deep Learning Python Repository! This project contains implementations of various deep learning models, including Multi-Layer Perceptrons (MLP), Convolutional Neural Networks (CNN), and Denoising Autoencoders (DAE), with a focus on the MNIST dataset. The code is written in Python and includes Jupyter notebooks (.ipynb) and Python scripts (.py) for easy experimentation and learning.
Project Overview
This repository serves as a collection of deep learning models implemented in Python using popular libraries such as TensorFlow, PyTorch, and NumPy. The primary dataset used is MNIST, but the code is structured to be adaptable for other datasets. Key techniques like dropout regularization are included to improve model performance.
Features

Implementation of MLP, CNN, and DAE models.
Jupyter notebooks for interactive experimentation.
Modular Python scripts for reusable code.
Example workflows for training and evaluating models on the MNIST dataset.
Support for dropout regularization and other deep learning techniques.

Requirements
The required dependencies are listed in requirements.txt:

tensorflow>=2.10 or torch>=1.9
numpy
matplotlib
jupyter

To install the dependencies, run:
pip install -r requirements.txt

If using Jupyter notebooks, start the Jupyter server:
jupyter notebook

Usage

Running Notebooks: Open the .ipynb files in Jupyter Notebook to explore the models interactively. Each notebook includes detailed explanations and visualizations.

Running Scripts: Use the .py files for command-line execution. For example:
python scripts/train_cnn.py


Training on MNIST: The repository includes pre-configured scripts and notebooks for training models on the MNIST dataset. Modify hyperparameters in the scripts or notebooks as needed.


Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -m "Add feature").
Push to the branch (git push origin feature-branch).
Create a pull request.

Please ensure your code follows the PEP 8 style guidelines and includes appropriate documentation.