# Deep Learning Python Repository

Welcome to the **Deep Learning Python Repository**!  
This project provides clean and modular implementations of deep learning models, including **Multi-Layer Perceptrons (MLP)**, **Convolutional Neural Networks (CNN)**, and **Denoising Autoencoders (DAE)**, with a focus on the **MNIST** dataset.  
The codebase is designed using **Python** and includes both **Jupyter Notebooks (`.ipynb`)** and **Python scripts (`.py`)** for flexible usage in experimentation, learning, and extension.


## 📌 Project Overview

This repository showcases core deep learning techniques using libraries like **TensorFlow**, **PyTorch**, and **NumPy**. While the primary dataset used is MNIST, the code is modular and easily adaptable to other datasets.

Key concepts like **dropout regularization**, model evaluation, and visualization are included to enhance understanding and model robustness.


## 🚀 Features

- ✅ Implementations of **MLP**, **CNN**, and **DAE** architectures  
- 🧪 **Jupyter notebooks** for interactive experimentation  
- 🔁 **Modular Python scripts** for training and evaluation  
- 🖼️ Preconfigured workflows using the **MNIST** dataset  
- 🧠 Support for deep learning techniques like **dropout regularization**


## 📦 Requirements

To install dependencies, run:

```bash
pip install -r requirements.txt
```

Contents of `requirements.txt`:

```
tensorflow>=2.10 OR torch>=1.9
numpy
matplotlib
jupyter
```


## 💻 Usage

### ▶️ Running Jupyter Notebooks

Start the Jupyter server with:

```bash
jupyter notebook
```

Then open and run any `.ipynb` file to interactively explore and experiment with the models.

### 🖥️ Running Python Scripts

Use the `.py` files for training/evaluation from the command line. For example:

```bash
python scripts/train_cnn.py
```

### 🧪 Training on MNIST

The project includes ready-to-run notebooks and scripts for training models on the **MNIST** dataset.  
You can modify hyperparameters such as learning rate, batch size, and number of epochs directly in the code files.


## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository  
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-branch
   ```
5. Create a pull request

Please make sure to:

- Follow the **PEP 8** coding style  
- Include clear documentation and meaningful commit messages

**Happy Learning and Experimenting with Deep Learning! 🚀**
