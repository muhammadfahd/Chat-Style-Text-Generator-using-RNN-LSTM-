# 💬 Chat-Style Text Generator using RNN (LSTM)

This project demonstrates how to train a **Recurrent Neural Network (RNN)** using **LSTM (Long Short-Term Memory)** layers to generate **chat-style text**.  
By learning from short conversational sentences, the model predicts and generates the next possible words — mimicking a simple chatbot-like response generator.

- [💬 Chat-Style Text Generator using RNN (LSTM)](#-chat-style-text-generator-using-rnn-lstm)
  - [Project Overview](#project-overview)
  - [Features](#features)
  - [Project Structure](#project-structure)
  - [Technologies \& Dataset  Used](#technologies--dataset--used)
  - [Future Improvements](#future-improvements)
  - [Connect with me:](#connect-with-me)


---

## Project Overview

Traditional text generation models often struggle to capture sequence dependencies.  
**Recurrent Neural Networks (RNNs)**, especially **LSTMs**, are designed to remember previous context, making them ideal for sequential data like conversations or text messages.

In this project, we:
1. Collected and cleaned short conversational data (from Kaggle dataset).  
2. Tokenized and encoded the text into numerical sequences.  
3. Trained an **LSTM-based RNN model** to predict the next word in a sequence.  
4. Used the trained model to **generate realistic chat-style text**.  

---

## Features

- Implements **LSTM architecture** for sequential text modeling  
- Includes **data cleaning, tokenization, and padding** steps  
- Generates chat-style text using a seed phrase  
- Built and trained entirely on **Kaggle Notebook environment**  
- Comes with a markdown guide (`RNN_Concept.md`) and visual explanations inside the **`images/`** folder  

---

## Project Structure
├── Chat-Style-Text-Generator-using-RNN-LSTM/
├── Chat_Text_Generator.ipynb # Main Kaggle notebook
├── RNN_Concept.md # Markdown explanation of RNN and LSTM
├── images/ # Visuals explaining RNN and its working

## Technologies & Dataset  Used

| Tool / Library | Purpose |
|----------------|----------|
| Python | Programming language |
| TensorFlow / Keras | Deep learning model (LSTM) |
| NumPy | Numerical operations |
| Pandas | Data manipulation |
| Kaggle | Dataset & notebook environment |

The dataset was taken from **Kaggle named [Cornell Movie-Dialogs Edition](https://www.kaggle.com/datasets/rajathmc/cornell-moviedialog-corpus)**


## Future Improvements
Train with more conversational data
Add Bidirectional LSTMs or Stacked LSTMs
Experiment with temperature sampling to increase creativity
Deploy model as a web app (Gradio / Streamlit)

## Connect with me:
* [LinkedIn](https://www.linkedin.com/in/mfahadbashir/)
* [GitHub](https://github.com/muhammadfahd)
* [Kaggle](https://www.kaggle.com/muhammadfahadbashir)
