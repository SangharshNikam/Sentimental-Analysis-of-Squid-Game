# Sentiment Analysis of Netflix's Squid Game Tweets 🎯

## 📌 Goal
To analyze public sentiment towards Netflix's *Squid Game* using deep learning models (LSTM, GRU, SimpleRNN, Bi-LSTM) on over 80,000 tweets.  
The aim is to help understand audience opinions and extract insights that could guide content strategy.

---

## 📊 Dataset
- **Source:** [Kaggle - Squid Game Netflix Twitter Data](https://www.kaggle.com/deepcontractor/squid-game-netflix-twitter-data)  
- **Size:** 80,000+ tweets, 12 columns  
- **Features:** Tweets, hashtags, timestamps, and metadata  
- **Preprocessing:** Stopword removal, tokenization, padding, sentiment label encoding

---

## 🛠 Installation
```bash
git clone https://github.com/SangharshNikam/Sentimental-Analysis-of-Squid-Game.git
cd Sentimental-Analysis-of-Squid-Game
pip install -r requirements.txt
```

---

## 📚 Libraries Used
- **TensorFlow / Keras** – For building, training, and evaluating deep learning models like LSTM, GRU, SimpleRNN, and Bi-LSTM.  
- **NLTK** – For natural language preprocessing such as tokenization, stopword removal, and text cleaning.  
- **Pandas** – For loading, cleaning, and managing the dataset.  
- **NumPy** – For numerical computations and array operations.  
- **Matplotlib & Seaborn** – For creating plots and visualizing data trends and model performance.  
- **WordCloud** – For generating word cloud visualizations of frequent terms in tweets.  
- **Scikit-learn** – For evaluation metrics (accuracy, precision, recall, F1-score) and data preprocessing helpers.

---

## 🚀 Usage
1. Download dataset from Kaggle and place it in the project folder.  
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook Sentiment_Analysis_Netflix_Squid_Game.ipynb
   ```
3. Run all cells to:
   - Preprocess data  
   - Train models (LSTM, GRU, SimpleRNN, Bi-LSTM)  
   - Compare accuracy and performance  

---

## 📈 Results
- **Best Model:** *[Insert best performing model here]*  
- **Metrics:** Accuracy, Precision, Recall, F1-score  
- **Visuals:** Word Clouds for sentiments, training curves for each model

---

## 📌 Future Work
- Implement BERT or transformer-based models  
- Create a real-time sentiment analysis dashboard  

---

## 📄 License
MIT License © 2025 **Sangharsh Anil Nikam**

---

## 👤 Author
**Sangharsh Anil Nikam**  
GitHub: [SangharshNikam](https://github.com/SangharshNikam)  
Repository: [Sentimental-Analysis-of-Squid-Game](https://github.com/SangharshNikam/Sentimental-Analysis-of-Squid-Game)
