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
| *Diagram: PyTorch ecosystem* | <img width="1024" height="572" alt="PyTorch ecosystem" src="https://github.com/user-attachments/assets/f4549e50-b131-4ba0-8540-dce8e387989a" /> |
| **2. Tensors**: creation, shape and dtype, broadcasting, reshaping | ⬜ |
| *Diagram: Tensor dimensions* | <img width="1024" height="572" alt="Tensor dimensions" src="https://github.com/user-attachments/assets/76dae6b9-a107-4222-af29-28938e29a0c6" /> |
| **3. Autograd**: `requires_grad`, computational graph, `backward()` | ⬜ |
| *Diagram: Forward and backward pass* | <img width="1024" height="572" alt="Autograd graph" src="https://github.com/user-attachments/assets/5cf791c3-74da-4714-997e-a57b7911b998" />|
| **4. Training Pipeline**: loss, optimizer, `zero_grad()`, epochs | ⬜ |
| *Diagram: Training loop* | <img width="1024" height="572" alt="Training loop"  src="https://github.com/user-attachments/assets/e48bb665-b629-4ea3-9c95-99fcd98eef93" /> |
| **5. NN Module**: `nn.Module`, `nn.Linear`, `nn.Sequential`, `state_dict` | ⬜ |
| *Diagram: nn.Module anatomy* | <img width="1024" height="572" alt="nn.Module anatomy"  src="https://github.com/user-attachments/assets/8bec9dca-534f-4d86-9c8f-68bbd223ca64" /> |
| **6. Dataset & DataLoader**: custom Dataset, batching, transforms | ⬜ |
| *Diagram: Data pipeline* | <img width="1024" height="572" alt="Data pipeline"  src="https://github.com/user-attachments/assets/d0c397d4-2df1-4705-be5b-aee48d313ebb" /> |

# ANN

| Topic / Concept | Status |
| :--- | :---: |
| **7. Building an ANN**: layers, activations, train and eval loop | ⬜ |
| *Diagram: ANN architecture* | <img width="1024" height="572" alt="ANN architecture"  src="https://github.com/user-attachments/assets/5bae5ea9-a703-4922-9d82-78409da88ed9" /> |
| **8. Training on GPU**: CUDA check, `.to(device)` | ⬜ |
| *Diagram: CPU ↔ GPU data flow* | <img width="1024" height="572" alt="GPU training"  src="https://github.com/user-attachments/assets/8eac1ed7-0909-47f6-990b-1677a9f9ffe2" /> |
| **9. Optimizing the Network**: dropout, weight decay, batch norm, optimizers | ⬜ |
| *Diagram: Optimization techniques* | <img width="1024" height="572" alt="Optimization techniques" src="https://github.com/user-attachments/assets/cd00b7d0-cf81-4c25-b1cc-742157e9a251" /> |
| **10. Hyperparameter Tuning**: Optuna study, trial, search space | ⬜ |
| *Diagram: Optuna workflow* | <img width="1024" height="572" alt="Optuna workflow" src="https://github.com/user-attachments/assets/459ad85a-3552-44d1-b8fb-7f83c8f0c963" /> |

# CNN

| Topic / Concept | Status |
| :--- | :---: |
| **11. Building a CNN**: convolution, stride, padding, pooling | ⬜ |
| *Diagram: CNN architecture* | <img width="1024" height="572" alt="CNN architecture"  src="https://github.com/user-attachments/assets/b29af9e8-8b46-4a8d-be95-4cdd27358987" /> |
| **12. Transfer Learning**: pretrained models, freezing, fine-tuning | ⬜ |
| *Diagram: Frozen base + new head* | <img width="1024" height="572" alt="Transfer learning"  src="https://github.com/user-attachments/assets/9c87b5ef-62e8-47b0-bebe-fe8370171231" /> |

# RNN & LSTM

| Topic / Concept | Status |
| :--- | :---: |
| **13. RNN**: embeddings, `nn.RNN`, hidden state | ⬜ |
| *Diagram: RNN unrolled through time* | <img width="1024" height="572" alt="RNN unrolled"  src="https://github.com/user-attachments/assets/63d7b6e0-2d59-4dcf-aecc-94888f6a6c91" /> |
| Project: Question Answering System | ⬜ |
| *Diagram: QA pipeline* | <img width="1024" height="572" alt="QA pipeline" src="https://github.com/user-attachments/assets/35771625-8ec6-441d-9c9c-b5479826c168" /> |
| **14. LSTM**: vanishing gradient, gates, cell state, `nn.LSTM` | ⬜ |
| *Diagram: LSTM cell* | <img width="1024" height="572" alt="LSTM cell" src="https://github.com/user-attachments/assets/e5ac785f-4003-476e-9123-ee8a7347b416" /> |
| Project: Next Word Predictor | ⬜ |
| *Diagram: Next word pipeline* | <img width="1024" height="572" alt="Next word pipeline"  src="https://github.com/user-attachments/assets/4e1076dd-79bb-4ce7-8aa1-2f8f45881f66" /> |

---

<div align="center">

<img src="assets/pytorch_training.gif" width="640" alt="A neural network learning: forward pass, backward pass, loss going down" />

*Forward pass → loss → backward pass → update. Repeat.*

</div>
