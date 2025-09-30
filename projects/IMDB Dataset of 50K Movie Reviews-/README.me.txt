Advanced Sentiment Analysis using LSTM (Deep Learning NLP)

 Project Goal
To build and evaluate a **Deep Learning** model for classifying 50,000 IMDB movie reviews as either positive or negative. The project serves as a crucial transition to advanced sequential modeling and MLOps practices in the NLP domain.

Key Skills Demonstrated
- **Deep Learning NLP:** Implemented and trained a **Long Short-Term Memory (LSTM) Recurrent Neural Network** using **TensorFlow/Keras** for sequence modeling.
- **Text Preprocessing Pipeline:** Utilized **NLTK** for critical text cleaning, including stemming, stop words removal, and standardizing text.
- **Sequence Modeling & Encoding:** Applied **Keras Tokenizer** and **Sequence Padding** to transform variable-length text into fixed-length numerical inputs for the neural network.
- **Word Embeddings:** Utilized the built-in **Embedding Layer** to create semantic vector representations of words, enhancing the model's understanding of meaning and context.
- **MLOps Integration:** Integrated **MLflow** to track all experimental runs, model hyperparameters (MAX_WORDS, MAX_LEN, EMBEDDING_DIM, epochs), and performance metrics, ensuring full reproducibility.

 Performance Results (LSTM Baseline)
The LSTM model established a strong baseline for sentiment classification, confirming the effectiveness of the deep learning approach:

| Metric | Value (Confirmed in our previous analysis) |
| :--- | :--- |
| **Final Accuracy** | 0.8615 |
| **Final Loss** | 0.3377 |
| **Primary Model** | LSTM Recurrent Neural Network |

Technologies & Tools
- Python, Pandas, NumPy
- **TensorFlow / Keras** (Sequential Model, LSTM, Embedding)
- **NLTK** (Natural Language Toolkit)
- **Scikit-learn** (train_test_split)
- **MLflow** (Experiment Tracking)