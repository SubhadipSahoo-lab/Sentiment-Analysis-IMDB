This project focuses on Sentiment Analysis of the IMDB movie review dataset, where reviews are classified as positive or negative. To determine the best accuracy, implement and compare multiple deep learning architectures, including LSTM, GRU, Encoder-Decoder, and Transformer models.

**Dataset**: IMDB Movie Reviews Dataset
Get the Dataset - https://drive.google.com/file/d/12IBWO0HjGEuCAzmV5GBdqjdl6KTRaC_g/view?usp=drive_link
Size: 50,000 movie reviews
Features:
**X (Input)**: Sequences of tokenized words representing reviews (shape: (50000, 50))
**y (Output)**: Sentiment labels (shape: (50000, 2), where [1,0] = Negative, [0,1] = Positive)


**Results & Conclusion:**

1. The Transformer model achieved the best performance due to self-attention mechanisms.
2. GRU performed slightly better than LSTM due to its efficient gating mechanism.
3. The Encoder-Decoder model worked well but required careful tuning.
4. Overall, attention-based models (Transformer) provided the most accurate sentiment classification.
