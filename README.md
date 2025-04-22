# Quantum Transformers for Natural Language Processing

Would the transformer architecture — the backbone of large language models (LLMs) like ChatGPT — still work if we replaced its neural networks with quantum unitary operations?

The answer is __yes__!

This repository contains two Quantum Transformer (QT) models in separate Jupyter notebooks that show how it works. For a detailed explanation, please refer to the code block descriptions in the attached Jupyter Notebooks or see [my blog post](https://medium.com/@arunsehrawat2/quantum-transformers-for-natural-language-processing-3045eb2b2b34) on this work. While early results on the tiny Shakespeare dataset are modest, the structure is promising.


### 1. Interferometric Transformer (IT) Model
Replaces classical linear layers with **interferometric networks**—phase shifters + beamsplitters (Fourier transforms).  


### 2. Rotational Transformer (RT) Model
Replaces classical linear layers with **qubit‐rotation networks**—only single‐qubit Ry rotations.  

<img width="1294" alt="QT Model" src="https://github.com/user-attachments/assets/7f8d4354-a0ad-463b-a72a-28e2ea89c0f4" />



