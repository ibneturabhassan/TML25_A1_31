# TML25_A1_31


# Shadow Models for Membership Inference Attack (MIA)

This project demonstrates how to perform a Membership Inference Attack (MIA) using shadow models. It utilizes deep feature extraction from a ResNet18 model and evaluates membership status based on output patterns. The notebook includes feature extraction, shadow model training, and attack model development using logistic regression.

## 📂 Contents

- `TaskDataset`, `MembershipDataset` classes for data loading and preprocessing
- Deep feature extraction using a pre-trained ResNet18 (modified)
- Training of shadow models to simulate target model behavior
- Logistic regression-based attack model to infer membership
- Metrics computation: AUC, TPR at low FPR

## 🧰 Requirements

- Python 3.8+
- PyTorch
- torchvision
- scikit-learn
- pandas
- tqdm
- wandb (optional, for logging)
- Google Colab or GPU-enabled runtime recommended

Install dependencies:

```bash
pip install torch torchvision scikit-learn pandas tqdm wandb
