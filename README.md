<div align="center">

# PyTorch for Deep Learning

A concise, diagram-first revision guide: from tensors and autograd to ANN, CNN, RNN and LSTM.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Progress](https://img.shields.io/badge/Progress-0%2F14-4DD0E1?style=flat)

Theory and Keras notebooks: [100 Days of Deep Learning](https://github.com/<your-username>/<100-days-repo>)

</div>

---

## Progress

| Section | Lectures | Status |
| :--- | :---: | :---: |
| Fundamentals | 1–6 | ⬜ |
| ANN | 7–10 | ⬜ |
| CNN | 11–12 | ⬜ |
| RNN & LSTM | 13–14 | ⬜ |

✅ done · ⬜ pending

---

# Fundamentals

| Topic / Concept | Status |
| :--- | :---: |
| **1. Introduction to PyTorch**: why PyTorch, core components | ⬜ |
| *Diagram: PyTorch ecosystem* | <img width="1024" height="572" alt="PyTorch ecosystem" src="assets/01_pytorch_ecosystem.png" /> |
| **2. Tensors**: creation, shape and dtype, broadcasting, reshaping | ⬜ |
| *Diagram: Tensor dimensions* | <img width="1024" height="572" alt="Tensor dimensions" src="assets/02_tensors.png" /> |
| **3. Autograd**: `requires_grad`, computational graph, `backward()` | ⬜ |
| *Diagram: Forward and backward pass* | <img width="1024" height="572" alt="Autograd graph" src="assets/03_autograd.png" /> |
| **4. Training Pipeline**: loss, optimizer, `zero_grad()`, epochs | ⬜ |
| *Diagram: Training loop* | <img width="1024" height="572" alt="Training loop" src="assets/04_training_pipeline.png" /> |
| **5. NN Module**: `nn.Module`, `nn.Linear`, `nn.Sequential`, `state_dict` | ⬜ |
| *Diagram: nn.Module anatomy* | <img width="1024" height="572" alt="nn.Module anatomy" src="assets/05_nn_module.png" /> |
| **6. Dataset & DataLoader**: custom Dataset, batching, transforms | ⬜ |
| *Diagram: Data pipeline* | <img width="1024" height="572" alt="Data pipeline" src="assets/06_dataset_dataloader.png" /> |

# ANN

| Topic / Concept | Status |
| :--- | :---: |
| **7. Building an ANN**: layers, activations, train and eval loop | ⬜ |
| *Diagram: ANN architecture* | <img width="1024" height="572" alt="ANN architecture" src="assets/07_ann.png" /> |
| **8. Training on GPU**: CUDA check, `.to(device)` | ⬜ |
| *Diagram: CPU ↔ GPU data flow* | <img width="1024" height="572" alt="GPU training" src="assets/08_gpu_training.png" /> |
| **9. Optimizing the Network**: dropout, weight decay, batch norm, optimizers | ⬜ |
| *Diagram: Optimization techniques* | <img width="1024" height="572" alt="Optimization techniques" src="assets/09_optimization.png" /> |
| **10. Hyperparameter Tuning**: Optuna study, trial, search space | ⬜ |
| *Diagram: Optuna workflow* | <img width="1024" height="572" alt="Optuna workflow" src="assets/10_optuna.png" /> |

# CNN

| Topic / Concept | Status |
| :--- | :---: |
| **11. Building a CNN**: convolution, stride, padding, pooling | ⬜ |
| *Diagram: CNN architecture* | <img width="1024" height="572" alt="CNN architecture" src="assets/11_cnn.png" /> |
| **12. Transfer Learning**: pretrained models, freezing, fine-tuning | ⬜ |
| *Diagram: Frozen base + new head* | <img width="1024" height="572" alt="Transfer learning" src="assets/12_transfer_learning.png" /> |

# RNN & LSTM

| Topic / Concept | Status |
| :--- | :---: |
| **13. RNN**: embeddings, `nn.RNN`, hidden state | ⬜ |
| *Diagram: RNN unrolled through time* | <img width="1024" height="572" alt="RNN unrolled" src="assets/13_rnn_unrolled.png" /> |
| Project: Question Answering System | ⬜ |
| *Diagram: QA pipeline* | <img width="1024" height="572" alt="QA pipeline" src="assets/13_qa_pipeline.png" /> |
| **14. LSTM**: vanishing gradient, gates, cell state, `nn.LSTM` | ⬜ |
| *Diagram: LSTM cell* | <img width="1024" height="572" alt="LSTM cell" src="assets/14_lstm_cell.png" /> |
| Project: Next Word Predictor | ⬜ |
| *Diagram: Next word pipeline* | <img width="1024" height="572" alt="Next word pipeline" src="assets/14_next_word.png" /> |

---

<div align="center">

<img src="assets/pytorch_training.gif" width="640" alt="A neural network learning: forward pass, backward pass, loss going down" />

*Forward pass → loss → backward pass → update. Repeat.*

</div>
