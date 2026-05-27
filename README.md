# PIZZA_SUSHI_STEAK_PREDICTOR

A deep learning image classification project that predicts whether a food image belongs to **Pizza, Sushi, or Steak** using a pretrained **EfficientNet-B0** model built with PyTorch.

## Project Overview

This project explores **Computer Vision** and **Transfer Learning** by fine-tuning a pretrained EfficientNet-B0 model for a custom food classification task.

Rather than training a neural network from scratch, transfer learning is used to leverage existing learned features and adapt them to classify food images into three categories:

- Pizza
- Sushi
- Steak

---

## Technologies Used

- Python
- PyTorch
- TorchVision
- EfficientNet-B0
- TensorBoard
- Matplotlib
- Jupyter Notebook / Google Colab

---

## Project Structure

```bash
PIZZA_SUSHI_STEAK_PREDICTOR/
│── Milestone_Project.ipynb
│── data/
│── models/
│── README.md
```

---

## Model Details

| Component | Details |
|------------|----------|
| Model | EfficientNet-B0 |
| Framework | PyTorch |
| Approach | Transfer Learning |
| Image Size | 224 × 224 |
| Optimizer | Adam |
| Loss Function | CrossEntropyLoss |

---

## Features

- Food Image Classification
- Transfer Learning using EfficientNet-B0
- Data Preprocessing and Augmentation
- Model Training and Evaluation
- Experiment Tracking with TensorBoard

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/PIZZA_SUSHI_STEAK_PREDICTOR.git
```

### Install Dependencies

```bash
pip install torch torchvision matplotlib tensorboard torchinfo
```

### Run the Project

Open the notebook:

```bash
Milestone_Project.ipynb
```

Run all cells to train, evaluate, and test the model.

---

## Example Prediction

Input Image → Predicted Class

- Pizza Image → Pizza
- Sushi Image → Sushi
- Steak Image → Steak

---

## Future Improvements

Potential improvements for the project:

- Build a Streamlit web application
- Deploy the model online
- Improve model accuracy
- Add more food categories
- Experiment with different architectures

---

## Author

**Arshpreet Walia**  
GitHub: https://github.com/arshpreetw11
