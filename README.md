# CNN Image Classification on CIFAR-10

This project implements and compares multiple Convolutional Neural Network (CNN) architectures on the CIFAR-10 dataset using TensorFlow. The goal is to evaluate how different architectural choices impact classification accuracy.

---

## Dataset

- **CIFAR-10**: A dataset of 60,000 32x32 color images in 10 classes, with 6,000 images per class.

---

## Architectures Implemented

1. **Basic CNN**
2. **CNN with Dropout**
3. **CNN with Batch Normalization**
4. **Deeper CNN**
5. **CNN with Different Filter Sizes**
6. **CNN with Residual Blocks**

Each model is trained and evaluated on the CIFAR-10 dataset with performance tracking.

---

## Tools & Technologies

- Python 3.8+
- TensorFlow 2.x
- Matplotlib
- NumPy

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Pranavisree/cnn-image-classification.git
   cd cnn-image-classification

2. Navigate to the project directory:

bash
Copy
Edit
cd cnn-image-classification
3. Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
4. Place your dataset in the appropriate directories (train/ and test/).

5. Run the training script:

bash
Copy
Edit
python train_model.py

