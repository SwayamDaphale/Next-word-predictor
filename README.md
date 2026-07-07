# Next-word-predictor
# 🧠 Next Word Predictor using LSTM

A Deep Learning project that predicts the **next word** in a sentence using a Long Short-Term Memory (LSTM) neural network. The application is built with **TensorFlow/Keras** and deployed using **Streamlit** for an interactive user interface.

---

## 📖 Project Overview

Next Word Prediction is one of the fundamental Natural Language Processing (NLP) tasks. It is widely used in applications such as:

* Mobile keyboard suggestions
* Search query auto-completion
* AI writing assistants
* Email composition
* Chatbots and virtual assistants

This project trains an LSTM model on Shakespeare's **Hamlet** dataset and predicts the most probable next word based on the user's input sequence.

---

## 🚀 Features

* Predicts the next word from an input sentence.
* Interactive Streamlit web application.
* Trained using TensorFlow/Keras.
* Uses a saved tokenizer for text preprocessing.
* Uses a pre-trained LSTM model for inference.
* Simple and beginner-friendly project structure.

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Deep Learning Framework

* TensorFlow / Keras

### Libraries

* NumPy
* Pandas
* Scikit-Learn
* Streamlit
* Matplotlib

### Model

* Long Short-Term Memory (LSTM)

---

## 📂 Project Structure

```text
Next-word-predictor/
│
├── app.py
├── experiemnts.ipynb
├── requirements.txt
├── hamlet.txt
├── tokenizer.pickle
├── next_word_lstm.h5
├── next_word_lstm_model_with_early_stopping.h5
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/SwayamDaphale/Next-word-predictor.git
```

### 2. Move into the project

```bash
cd Next-word-predictor
```

### 3. Create a virtual environment

Linux/macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will automatically open in your browser.

---

## 🧠 Model Workflow

```text
Hamlet Dataset
       │
       ▼
Text Preprocessing
       │
       ▼
Tokenizer Creation
       │
       ▼
Sequence Generation
       │
       ▼
Padding
       │
       ▼
LSTM Model Training
       │
       ▼
Model Saved (.h5)
       │
       ▼
Streamlit Application
       │
       ▼
User Input
       │
       ▼
Predicted Next Word
```

---

## 📊 Training Process

The model training includes:

* Text preprocessing
* Tokenization
* Sequence generation
* Padding sequences
* LSTM model architecture
* Early Stopping to reduce overfitting
* Model serialization
* Tokenizer serialization

---

## 💻 Example

**Input**

```text
To be or not to
```

**Output**

```text
be
```

*(Prediction may vary depending on the trained model.)*

---

## 📦 Dependencies

Major dependencies include:

* TensorFlow
* Streamlit
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib

Install all required packages using:

```bash
pip install -r requirements.txt
```

---

## 🔮 Future Improvements

* Support Transformer-based models
* Train on larger datasets
* Display Top-K predictions
* Add prediction probabilities
* Improve UI/UX
* Deploy on Streamlit Community Cloud
* Dockerize the application
* Add unit tests

---

## 📚 Learning Outcomes

Through this project, I learned:

* Text preprocessing for NLP
* Tokenization techniques
* Sequence generation
* Padding sequences
* Building LSTM networks
* Model training using TensorFlow/Keras
* Saving and loading trained models
* Deploying machine learning applications using Streamlit
* Version control using Git and GitHub

---

## 👨‍💻 Author

**Swayam Daphale**

Artificial Intelligence & Machine Learning Engineering Student

GitHub: https://github.com/SwayamDaphale

---

## ⭐ If you found this project useful

If you like this project, consider giving it a ⭐ on GitHub. It helps others discover the project and motivates me to build more AI and Machine Learning applications.
