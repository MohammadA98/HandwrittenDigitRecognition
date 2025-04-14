## Final Project: Handwritten Digit Recognition from Text-Based Images (SVM vs. CNN)

**Project Status:** [Active]

---

### 🧠 Introduction

This project explores how well machine learning models can recognize handwritten digits extracted from a text-based dataset. Each digit is represented as a 32×32 binary image encoded as strings. We compare two different approaches:

- **Support Vector Machine (SVM)**: Trained on flattened binary pixel vectors.
- **Convolutional Neural Network (CNN)**: Trained on reshaped grayscale images using Keras.

The ultimate goal is to preprocess and train models that can potentially generalize to **real-world digit images** by applying computer vision techniques and data augmentation.

---

### ⚙️ Installation & Setup

To run this project:

1. **Clone the repo:**
```bash
git clone https://github.com/MohammadA98/HandwrittenDigitRecognition.git
```

2. **Set up the environment (Python 3.9+ recommended):**
Make sure your virtual environment is activated.

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

4. **Run the notebook:**
```bash
jupyter notebook
```
Open the main notebook (e.g. `main.ipynb`) and run all cells.

---

### 🎯 Project Objectives

This project focuses on:

✔ Parsing and visualizing a text-based digit dataset  
✔ Reshaping and normalizing data for ML use  
✔ Training and evaluating two types of models: SVM and CNN  
✔ Using data augmentation to mimic real-world image imperfections  
✔ Comparing generalization capabilities for CV tasks

---

### 📁 Dataset Information



### 🧪 Methods Used

- Text-to-image parsing
- NumPy array reshaping & normalization
- Train/test split
- Model building: SVM and CNN
- Data Augmentation (rotation, shift, zoom)
- Model evaluation: Accuracy, Confusion Matrix

---

### 🔧 Technologies & Tools

- Python
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-learn (SVM)
- TensorFlow / Keras (CNN)
- Jupyter Notebook

---

### 👥 Contributors

- **Mohammad Alhabli**  
  GitHub: [@MohammadA98](https://github.com/MohammadA98)  
  LinkedIn: [Mohammad Alhabli](https://linkedin.com/in/MohammadA98)

- **Ramesh Dhanasekaran**  
  GitHub: [@rdhanase](https://github.com/rdhanase)  
  LinkedIn: [Ramesh Dhanasekaran](https://www.linkedin.com/in/ramesh-dhanasekaran-a428b444/)



