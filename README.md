# Toxicity Analysis in Online Social Media Comments

## Overview
The **Toxicity Analysis in Online Social Media Comments** project aims to detect toxic comments in online social media spaces using Natural Language Processing (NLP) and Machine Learning. The project features a user-friendly GUI that allows users to input text and receive real-time feedback on the toxicity level of the comment. The model has been trained on a large dataset of over **150,000 entries** and achieves **92% accuracy** and **82% precision** in detecting various forms of toxicity, including offensive language, threats, and hate speech.

## Features
- **User-Friendly Interface**: Simple GUI for easy input of comments and display of toxicity analysis results.
- **Machine Learning Model**: A 5-layer Bidirectional LSTM model trained using PyTorch for robust prediction of toxicity.
- **NLP Preprocessing**: Utilizes NLP techniques to clean and process comment data, ensuring accurate analysis.
- **Multi-Parameter Analysis**: Analyzes comments based on 6 key parameters, ensuring nuanced detection of toxic content.
- **Real-Time Feedback**: Instantly evaluates comments and provides toxicity scores, making it suitable for integration with social media platforms.

## Tech Stack
- **Programming Language**: Python
- **Machine Learning Framework**: LSTM (Long Short-Term Memory)
- **Natural Language Processing (NLP)**: NLTK, SpaCy
- **Graphical User Interface (GUI)**: Streamlit
- **Data Handling**: Pandas, NumPy

## Dataset
The model is trained on a dataset containing over **150,000 comments**, sourced from various social media platforms. The dataset includes labeled comments with different categories of toxicity such as insults, profanity, hate speech, and threats.

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Toxicity-Analysis.git
   cd Toxicity-Analysis
