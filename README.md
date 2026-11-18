# Deep Learning — Coursework

Assignments, workshops and the course project from three deep learning
courses, implemented in PyTorch and Keras. Notebooks are committed with their
outputs.

## 1401-2 · Dr. Soleymani (Sharif, CE-40719)

| Folder | Topic |
|---|---|
| [`HW1_MLP`](1401-2-soleymani/HW1_MLP) | PyTorch tensor basics; an MLP from scratch in NumPy and in PyTorch; Newton's method |
| [`HW2_CNN`](1401-2-soleymani/HW2_CNN) | CNN image classification (Fashion-MNIST); U-Net semantic segmentation |
| [`HW3_RNN_Transformer`](1401-2-soleymani/HW3_RNN_Transformer) | Character-level RNN language model; the Transformer architecture |
| [`HW4_Generative`](1401-2-soleymani/HW4_Generative) | VAEs, GANs and diffusion models |
| [`Workshops`](1401-2-soleymani/Workshops) | PyTorch and autograd basics; Hugging Face `transformers` tour; autoregressive image models (Gated PixelCNN) — each with a student version |

## 1401-1 · Dr. Pilehvar

| Folder | Topic |
|---|---|
| [`HW2`](1401-1-pilehvar/HW2) | A first neural network: features, training, prediction |
| [`HW3`](1401-1-pilehvar/HW3) | MLP on MNIST in PyTorch |
| [`HW4`](1401-1-pilehvar/HW4) | Recurrent neural networks (stock prices, Persian names) |

## 1400-1 · Dr. Fatemizadeh

| Folder | Topic |
|---|---|
| [`HW1`](1400-1-fatemizadeh/HW1) | Neural network training: splits and normalisation |
| [`HW2`](1400-1-fatemizadeh/HW2) | Image classification; studying a CNN architecture (in Persian) |
| [`HW3`](1400-1-fatemizadeh/HW3) | Twitter sentiment analysis; training on a custom dataset |
| [`HW4`](1400-1-fatemizadeh/HW4) | Assignment PDF |
| [`Project`](1400-1-fatemizadeh/Project) | Object detection plus depth estimation: YOLO with a FastDepth-style network on NYU Depth V2 (with Alireza Heshmati) — see the report |

## Datasets

The datasets are public and not stored here.

| Data | Used in | Source |
|---|---|---|
| Fashion-MNIST | 1401-2 HW2 (CNN) | [zalandoresearch/fashion-mnist](https://github.com/zalandoresearch/fashion-mnist); `torchvision.datasets.FashionMNIST` downloads it into `data/` |
| `data/CameraRGB/`, `data/CameraMask/` | 1401-2 HW2 (U-Net) | Lyft–Udacity self-driving segmentation images — [Kaggle](https://www.kaggle.com/datasets/kumaresanmanickavelu/lyft-udacity-challenge) |
| `Q1_train.csv`, `Q1_test.csv` | 1400-1 HW1 | Sign Language MNIST — [Kaggle](https://www.kaggle.com/datasets/datamunge/sign-language-mnist) (`sign_mnist_train.csv` / `sign_mnist_test.csv`) |

`1401-2-soleymani/HW2_CNN/cnn_model` is the trained CNN from HW2. Small
course-provided files (`my_test.csv`, `NVDA.csv`, `Persian_names.csv`, …) are kept
next to their notebooks.
