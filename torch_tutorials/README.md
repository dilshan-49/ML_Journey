# PyTorch Tutorials

This folder contains Jupyter notebooks and Python scripts for learning PyTorch, following the "Programming PyTorch for Deep Learning" book. The materials cover fundamental concepts and practical implementations of deep learning using PyTorch.

## 📁 Contents

### Notebooks

- **`intro.ipynb`** - Introduction to PyTorch basics
  - Tensor creation and manipulation
  - Basic tensor operations
  - CUDA availability checking
  - Tensor reshaping and permutation

- **`CNN.ipynb`** - Convolutional Neural Networks
  - CNN architecture and implementation
  - Building convolutional layers
  - Understanding convolution operations

- **`imageClassifier.ipynb`** - Image Classification Project
  - Complete image classification pipeline
  - Data preprocessing and augmentation
  - Model training and evaluation
  - Working with the Fish vs Cats dataset

### Saved Models

- **`models/`** - Directory for saved model checkpoints
  - `simplenet_adam` - Trained model using Adam optimizer

## 🚀 Getting Started

### Prerequisites

```bash
pip install torch torchvision numpy pandas urllib3
```

### Running the Notebooks

1. **Start with `intro.ipynb`** to understand PyTorch basics
2. **Complete the project with `imageClassifier.ipynb`** for hands-on experience with a Simple Neural network for classification.

## 📖 Book Reference

These materials follow the concepts and examples from "Programming PyTorch for Deep Learning". Each notebook corresponds to specific chapters and builds upon previous concepts.

## 💡 Tips for Learning

1. **Run each cell sequentially** in the notebooks
2. **Experiment with parameters** to see how they affect results
3. **Visualize the data** to better understand what you're working with
4. **Save your progress** by running the training notebooks completely
5. **Try modifying the architectures** to see how they perform

## 🔧 Troubleshooting

- If you encounter CUDA issues, check GPU availability with `torch.cuda.is_available()`
- If notebooks don't run, verify all dependencies are installed

---

Happy Learning! 🚀
