# LSTM-RNN-GRU-RNN-MODEL

# Next Word Prediction Using LSTM and GRU 

## 📌 Project Overview
This project implements a **Next Word Prediction** system using **Long Short-Term Memory (LSTM)** networks. The model predicts the most probable next word for a given sequence of words. LSTMs are particularly effective for this task due to their ability to capture long-term dependencies in sequential data.

The project uses **Shakespeare’s *Hamlet*** as the training dataset, providing rich linguistic patterns and complex sentence structures for learning.

---

## 🚀 Features
- Deep learning–based next word prediction
- Uses **LSTM** for sequence modeling
- Text preprocessing with tokenization and padding
- Early stopping to prevent overfitting
- Interactive **Streamlit web application** for real-time predictions

---

## 🧠 Model Architecture
The neural network consists of:
- **Embedding Layer** – Converts words into dense vector representations
- **Two LSTM Layers** – Captures contextual and sequential dependencies
- **Dense Output Layer (Softmax)** – Predicts probability distribution over the vocabulary

---

## 🗂️ Dataset
- **Source:** Shakespeare’s *Hamlet*
- **Type:** Plain text corpus
- **Reason:** Rich vocabulary and complex sentence structure make it ideal for NLP tasks

---

## ⚙️ Project Workflow
1. **Data Collection**
   - Text data extracted from *Hamlet*

2. **Data Preprocessing**
   - Text cleaning
   - Tokenization
   - Sequence generation
   - Padding for uniform sequence length
   - Train-test split

3. **Model Building**
   - Embedding + LSTM-based architecture
   - Softmax output for next word prediction

4. **Model Training**
   - Optimized using categorical cross-entropy
   - Early stopping based on validation loss

5. **Model Evaluation**
   - Tested on sample input sentences
   - Evaluates model’s ability to predict contextually correct next words

6. **Deployment**
   - Deployed as a **Streamlit web app**
   - Users can input a phrase and get the predicted next word instantly

---

## 🖥️ Streamlit Application
The Streamlit app allows:
- User input of a word sequence
- Real-time next word prediction
- Interactive and user-friendly interface

---

## 🛠️ Tech Stack
- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **NLTK / Tokenizer**
- **Streamlit**

---
