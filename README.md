# Text_Generation_Model
#  Shakespeare Text Generator (LSTM)

This project trains a character-level language model using an LSTM on the Tiny Shakespeare dataset. Once trained, it can generate Shakespeare-style text one character at a time.

##  How It Works
- Dataset: Tiny Shakespeare (~100k characters)
- Model: Embedding + LSTM + Dense
- Input: 100-character sequences
- Output: Next predicted character

##  Usage
1. Train the model using `train_model.py`
2. Load weights and run inference with `generate_text.py`
3. Adjust temperature and prompt for creative results

##  Requirements
See `requirements.txt`
