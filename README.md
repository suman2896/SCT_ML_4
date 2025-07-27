# 🤚 Hand Gesture Recognition using PyTorch

A deep learning-based system to recognize hand gestures using image data. The model is trained using PyTorch and evaluated with UMAP visualizations and classification metrics. This project can be used in HCI systems, accessibility tools, or sign language recognition.

---

## 🧠 Key Features

- Deep Neural Network built with PyTorch
- UMAP-based latent space visualization
- Training and evaluation using sklearn metrics
- Clear data preprocessing and augmentation
- Image classification for static hand signs

---

## 📦 Installation

Create a virtual environment (optional):

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/hand-gesture-recognition.git
cd hand-gesture-recognition
```

2. Download the dataset.

3. Open the notebook and run:

```bash
jupyter notebook hand-gesture-recognition.ipynb
```

---

## 🔗 Dataset Link

You can download the dataset used for training from:

[📥 Hand Gesture Dataset (Kaggle)](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)

---

## 🧮 Algorithm

1. **Data Loading**:
   - Load images, apply grayscale or RGB conversions
   - Resize images, normalize, and encode labels

2. **Model Definition**:
   - Custom Deep Neural Network using `nn.Sequential`
   - ReLU activations, dropout layers for regularization

3. **Training Loop**:
   - Mini-batch gradient descent
   - CrossEntropy loss
   - Accuracy tracking with tqdm progress

4. **Visualization**:
   - UMAP plots of hidden layer embeddings
   - Confusion matrix using `seaborn` heatmap

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 🔮 Future Scope

- Extend to dynamic hand gestures (video frames)
- Real-time webcam-based prediction
- Integrate with sign language translation tools
- Deploy as a web or mobile application

---

## ✅ Final Thought

This project demonstrates the power of combining deep learning with dimensionality reduction techniques like UMAP to build interpretable gesture recognition models. It provides a great starting point for researchers or developers aiming to build human-centered AI interfaces.
