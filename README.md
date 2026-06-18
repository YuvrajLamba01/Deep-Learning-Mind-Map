# Deep-Learning-Mind-Map


<div align="center">

# 🧠 Deep Learning 

> A structured walkthrough of Deep Learning from perceptrons to Transformers  
> Based on a full course covering ANN · CNN · RNN · LSTM · GRU · Attention · Transformers · LLMs

<br/>

<br/>
<br/>

![Topics](https://img.shields.io/badge/Topics-60%2B-7F77DD?style=flat-square)
![Architectures](https://img.shields.io/badge/Architectures-ANN%20%7C%20CNN%20%7C%20RNN%20%7C%20Transformer-1D9E75?style=flat-square)
![Level](https://img.shields.io/badge/Level-Beginner%20→%20Advanced-D85A30?style=flat-square)

</div>

---

## 📌 What's Covered

| Section | Topics |
|---|---|
| **Fundamentals** | Perceptron, MLP, activation functions, non-linearity |
| **Training** | Forward prop, backpropagation, vanishing gradient, optimizers |
| **Regularisation** | Dropout, L1/L2, batch norm, early stopping, data augmentation |
| **Architectures** | ANN, CNN, RNN — with backprop for each |
| **LSTM & GRU** | Gates, cell state, hidden state, LSTM vs GRU |
| **LLMs & Attention** | Seq2Seq, Bahdanau/Luong attention, Transformers |
| **Transformer Deep Dive** | Encoder, Decoder, self-attention, multi-head, positional encoding |

---

## 🗂️ Sections

### 1. Fundamentals
- What is Deep Learning vs Machine Learning
- Representation learning
- Perceptron — geometry, trick, loss functions (hinge loss, binary cross entropy)
- Why non-linearity is essential
- MLP notation and intuition
- Activation functions: Sigmoid, Tanh, ReLU, Leaky ReLU, ELU, SELU

### 2. Training
- Forward propagation
- Backpropagation (what, how, why)
- Vanishing & exploding gradient problem
- Memoization in backprop (DP approach)
- Gradient Descent variants: Batch, Stochastic, Mini-Batch
- Optimizers: SGD → Momentum → NAG → AdaGrad → RMSProp → **Adam**

### 3. Regularisation & Improving Performance
- Early stopping
- Dropout (ensemble intuition)
- L1 / L2 regularisation (weight decay)
- Batch Normalisation
- Data Augmentation
- Data / Feature Scaling
- Weight Initialisation: Xavier/Glorot, He

### 4. CNN — Convolutional Neural Networks
- Convolution operation, filters/kernels
- Padding (valid vs same)
- Stride — strided convolution
- Pooling layers (MaxPooling, AvgPooling)
- LeNet-5 architecture
- CNN vs ANN — learnable parameters
- Backpropagation through Conv, Pooling, Flatten
- Transfer learning & pretrained models (ImageNet, ILSVRC)
- Feature map visualisation

### 5. RNN — Recurrent Neural Networks
- Why RNNs over ANNs for sequences
- Architecture & forward propagation
- Many-to-one, One-to-many, Many-to-many
- Backpropagation Through Time (BPTT)
- Problems: vanishing gradient in RNNs

### 6. LSTM & GRU
- LSTM: Forget gate · Input gate · Output gate
- Cell state (LTM) vs Hidden state (STM)
- GRU: Update gate · Reset gate
- LSTM vs GRU comparison
- Deep (Stacked) RNNs
- Bidirectional RNN / BiLSTM

### 7. LLMs & Transformers
- History: LSTM → Attention → Transformer → LLMs
- Encoder-Decoder (Seq2Seq) architecture
- Teacher forcing
- Attention mechanism (Bahdanau, Luong)
- Self-attention & why it's called "self"
- Scaled dot-product attention
- Multi-head attention
- Positional encoding
- Layer normalisation vs Batch norm
- Transformer Encoder & Decoder architecture
- Masked self-attention
- Cross-attention
- Inference — autoregressive decoding

---

## 🔗 Useful Resources

| Resource | Link |
|---|---|
| TensorFlow Playground | [playground.tensorflow.org](https://playground.tensorflow.org) |
| Backprop Visualiser | [ML Crash Course](https://developers-dot-devsite-v2-prod.appspot.com/machine-learning/crash-course/backprop-scroll) |
| ImageNet | [image-net.org](https://www.image-net.org/) |
| CNN Filter Visualiser | [deeplizard.com](https://deeplizard.com/resource/pavq7noze2) |
| Attention is All You Need | [arxiv.org/abs/1706.03762](https://arxiv.org/abs/1706.03762) |
| Seq2Seq Paper | [arxiv.org/abs/1409.3215](https://arxiv.org/abs/1409.3215) |

<br/>

<br/>
<div align="center">

Made with focus and backpropagation ✦

</div>

# Deep Learning Mind Map

```mermaid
mindmap
  root((Deep Learning))
    Introduction to DL
      Deep Learning vs Machine Learning
      Representation Learning
      Interpretability
      Data Generation Growth
      Pretrained Models
    Perceptron
      Geometric Intuition
      Step Activation Function
      Perceptron Trick
      Loss Functions
        Hinge Loss
        Binary Cross Entropy
        Mean Squared Error
      Problems
        Linearly separable only
        Cannot learn XOR
        Without non-linearity
    MLP and ANN
      Forward Propagation
      Backpropagation
        Chain Rule
        Memoization
      Activation Functions
        Sigmoid
        Tanh
        ReLU
        Variants
      Loss Functions
        MSE for Regression
        Binary Cross Entropy for Classification
      Optimization
        Gradient Descent
        Optimizers
        Learning Rate Scheduling
      Regularization
        Dropout
        L1 and L2 Regularization
        Data Augmentation
        Early Stopping
      Initialization
        Xavier Glorot
        He Initialization
      Batch Normalization
    CNN
      Convolution Operation
        Filters and Kernels
        Padding and Stride
      Pooling Layers
        Max Pooling
      Architectures
        LeNet
        AlexNet
        VGG
        ResNet
      Transfer Learning
        Feature Extraction
        Fine Tuning
      Visualization
    RNN
      Sequential Data
      Hidden State Recurrence
      Backpropagation Through Time
      Types
        One-to-Many
        Many-to-One
        Many-to-Many
      Problems
        Vanishing Gradient
        Exploding Gradient
    LSTM
      Gating Mechanism
      Cell State
      Hidden State
      Gates
        Forget Gate
        Input Gate
        Output Gate
    GRU
      Simplified LSTM
      Update Gate
      Reset Gate
      Fewer Parameters
    Advanced RNN
      Deep Stacked RNNs
      Bidirectional RNNs
        BiLSTM
        BiGRU
    Transformers and LLMs
      History
      Encoder-Decoder
      Attention Mechanism
        Bahdanau Attention
        Luong Attention
      Self-Attention
        Queries Keys Values
        Scaled Dot-Product
        Multi-Head Attention
        Masks
      Transformer Architecture
        Encoder
        Decoder
        Positional Encoding
      Normalization
        LayerNorm
      Inference
      Transfer Learning
        Pretraining
        Fine-tuning
      Large Language Models
