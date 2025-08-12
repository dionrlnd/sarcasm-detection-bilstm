# Sarcasm Detection with BiLSTM

This project implements a sarcasm detection model using Bidirectional LSTM (BiLSTM) in TensorFlow/Keras.  
The dataset contains news headlines labeled as sarcastic or not, sourced from the [Sarcasm Detection dataset](https://storage.googleapis.com/tensorflow-1-public/course3/sarcasm.json).

## Dataset
- **Source**: TensorFlow public dataset
- **Format**: JSON
- **Fields**:
  - `headline`: News headline text
  - `is_sarcastic`: 1 if sarcastic, 0 if not
  - `article_link`: URL to the full article

## Requirements
- Python 3.8+
- TensorFlow
- Pandas
- NumPy
- Matplotlib

You can install dependencies using:
```bash
pip install -r requirements.txt