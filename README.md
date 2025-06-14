# 🧠 Next Word Prediction using LSTM

This project demonstrates how to build a next-word prediction model using **LSTM (Long Short-Term Memory)** neural networks. The model is trained on text data from **Sherlock Holmes stories** and predicts the next word in a sequence.

## 📌 Features

- Tokenization of large text corpus
- Sequence generation for language modelling
- Padding for uniform input dimensions
- LSTM-based architecture for word prediction
- Real-time prediction of next words
- Achieved ~75%+ accuracy on training data

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Natural Language Processing (NLP)
- Deep Learning (LSTM, Embedding)

## 📁 Dataset

The model uses raw text data from Sherlock Holmes stories, loaded from a `.txt` file containing plain English sentences.

## 📈 Model Architecture

- **Embedding Layer:** Maps 8200 unique words to 100-dimensional vectors  
- **LSTM Layer:** 200 units to capture sequential dependencies  
- **Dropout Layer:** 0.2 to prevent overfitting  
- **Dense Layer:** Final output layer with softmax over 8200 tokens  

## 📊 Training

- Optimizer: Adam  
- Loss: Categorical Crossentropy  
- Accuracy: ~75%  
- EarlyStopping based on accuracy
- Trained over 80 epochs

## 🚀 Prediction Example

**Input:**  
`you are sure that she`

**Generated Output:**  
`you are sure that she has not sent it yet`

## 🧪 How it works

1. Tokenizes and sequences the input text  
2. Pads sequences to a fixed length  
3. Trains LSTM on sequences to predict next words  
4. Uses model to iteratively generate 5 words following the input

## 📬 Contact

For any questions, suggestions, or feedback, feel free to connect:

- 💼 [LinkedIn](https://www.linkedin.com/in/nipunkumar01/)
