# 🗑️ Waste Classification Smart Bin using Deep Learning

This project is a smart waste classification system that leverages a Convolutional Neural Network (CNN) built using the Keras API to automatically segregate **plastic** and **glass** waste. It aims to promote efficient recycling and environmental sustainability using AI.

---

## 🚀 Features

- Classifies waste into **plastic** and **glass** categories.
- Built with **Keras and TensorFlow**.
- Lightweight and optimized for real-time predictions.
- Can be deployed on embedded systems like Raspberry Pi for edge AI applications.

---

## 🧠 Model Architecture

The model is a CNN with the following components:
- Convolutional layers for feature extraction
- MaxPooling layers for dimensionality reduction
- Fully connected (Dense) layers for classification
- Softmax output for binary classification (Plastic vs Glass)

---

## 📁 Project Structure

```
waste-classification/
│
├── dataset/
│   ├── plastic/
│   └── glass/
│
├── model/
│   └── waste_classifier.h5
│
├── scripts/
│   ├── train.py
│   └── predict.py
│
├── utils/
│   └── preprocessing.py
│
└── README.md
```

---

## 🏁 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/waste-classification.git
cd waste-classification
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Train the model

```bash
python scripts/train.py
```

### 4. Make a prediction

```bash
python scripts/predict.py --image path_to_image.jpg
```

---

## 📊 Dataset

The dataset consists of labeled images of **plastic** and **glass** waste. You can either collect your own images or use publicly available datasets like:

- [TrashNet](https://github.com/garythung/trashnet)
- [TACO](https://tacodataset.org)

---

## 💡 Use Cases

- Smart bins for public spaces
- Automated recycling units
- Educational AI projects on sustainability

---

## 🤖 Future Improvements

- Add more waste categories (e.g., paper, metal, organic)
- Implement object detection for localization
- Deploy the model on edge devices

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements

- TensorFlow and Keras community
- Dataset contributors
- Environmental AI initiatives

---

