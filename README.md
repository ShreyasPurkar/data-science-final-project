# This repository contains the pytorch implementation for two papers:

-  Paper 1: Neural Discrete Representation Learning
-  Paper 2: Denoising Diffusion Probabilistic Models (DDPM)

## To run the code for Neural Discrete Representation Learning go to the folder paper-1 and follow the below mentioned instructions:
### Requirements

#### Dependencies
- torch>=1.7.0
- torchvision>=0.8.0
- numpy>=1.19.0
- matplotlib>=3.3.0
- scipy>=1.5.0
- umap-learn>=0.5.0
- tqdm>=4.50.0
- Pillow>=8.0.0
- scikit-learn>=0.23.0

#### Hardware Requirements
- CUDA-capable GPU recommended (16GB+ VRAM for CIFAR-10, 8GB+ for MNIST)
- At least 8GB of RAM
- For CPU-only: Training will be significantly slower

#### Installation

Clone this repository:

```bash
git clone https://github.com/yourusername/data-science-final-project.git
cd ddpm-pytorch
```

Install the required packages:

```bash
pip install -r requirements.txt
```

### Open the notebook in google colab/kaggle and run each cell in sequence to reproduce the results from paper


## To run the code for DDPM go to the folder paper-2 and follow the below mentioned instructions:

### Requirements

#### Dependencies
- torch>=1.7.0
- torchvision>=0.8.0
- tqdm
- pyyaml
- matplotlib
- imageio
- numpy

#### Hardware Requirements
- CUDA-capable GPU recommended (16GB+ VRAM for CIFAR-10, 8GB+ for MNIST)
- At least 8GB of RAM
- For CPU-only: Training will be significantly slower

#### Installation

Clone this repository:

```bash
git clone https://github.com/yourusername/data-science-final-project.git
cd ddpm-pytorch
```

Install the required packages:

```bash
pip install -r requirements.txt
```

### Open the notebook in google colab/kaggle and run each cell in sequence to reproduce the results from paper