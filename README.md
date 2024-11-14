# DSA4266 Group 5 - Malware Classification
## Introduction

This project explores machine learning approaches for classifying malware using the Microsoft Malware Classification Challenge dataset. We implemented and evaluated several models, including traditional tree-based models like XGBoost, as well as neural network architectures: CNN, MLP, RNN, and a Combined Neural Network Model. The combined model, utilizing both ASM and bytes features, achieved the best performance, showcasing the benefits of integrating multiple feature types. XGBoost, when trained with ASM features alone, also performed very well, demonstrating the robustness of tree-based models in this context. Our findings indicate that combining ASM and bytes data enhances class separability, which we further visualize through t-SNE plots of output embeddings to improve model interpretability.

This repository includes the full codebase, data preprocessing steps, and model implementations.
## Repo Structure
- src/
    - "Feature Engineering"/
        - "Feature Engineering Code"/
        - "Processed Features"/
    - "Kaggle Dataset"/
    - "Model"/
        - "Model Code"/
        - "Trained Model"/
- README.md

## Link to Submission Materials
[DSA4266 Group 5 Final Submission](https://drive.google.com/drive/folders/1ulTA6HubY_LSpWAriNVhpa8a8lXuRGGp?usp=sharing)
