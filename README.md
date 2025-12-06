Next Word Predictor using LSTM (Mini Project)

A simple deep-learning mini project that predicts the next word in a sentence using an LSTM neural network.
This project is ideal for beginners exploring NLP, recurrent neural networks, and text generation.

🔥 Project Overview

This project trains an LSTM model on a text corpus (e.g., Alice in Wonderland or TED conversations) to learn word dependencies and predict the next word.

Pipeline:

Load & clean text

Tokenize

Create word sequences

Train LSTM model

Predict next word for custom input

📁 Dataset

Recommended medium-sized datasets

🧠 Model Architecture

Embedding Layer

LSTM (150 units)

Dense Layer (softmax output)

🚀 How to Run
1. Clone the repository
git clone https://github.com/madhulika789/word_predictor_mini.git
cd word_predictor_mini

2. Install dependencies
pip install -r requirements.txt

3. Run the Notebook
jupyter notebook word_predictor_mini.ipynb
