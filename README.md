# LSTM-vs-GRU-for-given-tweet-is-about-a-real-disaster-or-not

## LSTM Training Accuracy
![螢幕擷取畫面 2025-04-13 205857](https://github.com/user-attachments/assets/91898fd1-7985-4cb1-af1e-924a02bd0b79)

## GRU Training Accuracy
![螢幕擷取畫面 2025-04-13 205931](https://github.com/user-attachments/assets/7ee7fbeb-5af1-418b-aac1-dbfdda08d1fd)

The GRU model slightly outperformed LSTM in terms of training efficiency and resource usage. GRU achieved a lower final training loss (0.1870 vs. 0.2383) and a marginally higher peak validation accuracy of 83.32%, compared to 83.19% for LSTM. It also used less GPU memory (around 2380MB vs. 2440MB). However, LSTM showed more stable validation accuracy across epochs, making it more reliable for consistent performance. Training speed was nearly identical for both models. In summary, GRU is more efficient, while LSTM offers greater stability.

