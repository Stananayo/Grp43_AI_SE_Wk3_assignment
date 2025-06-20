# Overview
- This repository contains the practical submission for Group 43’s Week 3 assignment, focusing on the application of Machine Learning (ML) and Natural Language Processing (NLP) techniques to real-world datasets. The implementation leverages popular Python libraries: Scikit-learn, TensorFlow, PyTorch, and spaCy. The goal is to develop solutions, analyze results, and reflect on the ethical implications of AI models.

---

## Contents

- `Iris_data.ipynb` &mdash; Classical Machine Learning with Scikit-learn on the Iris dataset.
- `HandWritten_digit.ipynb` &mdash; Deep Learning with TensorFlow for MNIST handwritten digits.
- `mnist_handwritten.ipynb` &mdash; Advanced CNN approach to MNIST with training visualization.
- `NLP_SpaCy.ipynb` &mdash; NLP with spaCy and sentiment analysis using Amazon product reviews.
- `Report.docx` &mdash; Written report covering theory, outputs, and ethical discussion.

---

## Assignment Tasks

### 1. Classical ML with Scikit-learn: Iris Species Classification

- **Data:** Iris species dataset.
- **Steps:**
  - Data preprocessing (missing values, encoding).
  - Train a Decision Tree Classifier.
  - Evaluate using accuracy, precision, recall.
- **Deliverable:** Jupyter notebook with code and explanations.
- **See:** [`Iris_data.ipynb`](Iris_data.ipynb)

### 2. Deep Learning with TensorFlow/PyTorch: MNIST Digit Recognition

- **Data:** MNIST handwritten digits.
- **Steps:**
  - Build and train a Convolutional Neural Network (CNN).
  - Achieve >95% accuracy.
  - Visualize predictions and training metrics.
- **Deliverables:** 
  - [`HandWritten_digit.ipynb`](HandWritten_digit.ipynb): TensorFlow implementation.
  - [`mnist_handwritten.ipynb`](mnist_handwritten.ipynb): Enhanced CNN and plots.

### 3. NLP with spaCy: Amazon Reviews

- **Data:** Amazon product reviews (sample).
- **Steps:**
  - Perform Named Entity Recognition (NER) for products and brands.
  - Sentiment analysis using both TextBlob and rule-based methods.
- **Deliverable:** [`NLP_SpaCy.ipynb`](NLP_SpaCy.ipynb)

---

## Tools & Resources

- **Frameworks:** TensorFlow, PyTorch, Scikit-learn, spaCy
- **Platforms:** Google Colab, Jupyter Notebook
- **Datasets:** Iris, MNIST, Amazon Reviews (sample)

---

## How to Run

1. Clone this repository:
   ```sh
   git clone https://github.com/Stananayo/Grp43_AI_SE_Wk3_assignment.git
   cd Grp43_AI_SE_Wk3_assignment
   ```
2. Open `.ipynb` files in Jupyter or Google Colab.
3. Install required Python packages:
   ```sh
   pip install -r requirements.txt
   ```
   *(If `requirements.txt` is not present, install the following: `scikit-learn`, `tensorflow`, `torch`, `spacy`, `textblob`, `matplotlib`)*

---

## Authors & Acknowledgments

Group 43, AI & Software Engineering, 2025.

---

## License

This project is for academic use.