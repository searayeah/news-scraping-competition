# news-scraping-competition

- [Предсказание новостных тематик \| Kaggle](https://www.kaggle.com/competitions/news-scraping-competition)
- A text classification competition focused on Russian news agency texts.
- The goal was to predict the news category of each text.
- The challenge was designed to reward parsing the test set to achieve 100% accuracy.
- Instead of parsing, I focused on leveraging pre-trained BERT models trained on publicly available datasets.
- Achieved 13th place with a 91% accuracy score, without any test set parsing.
- Approach: Used cointegrated/rubert-tiny2 with the following parameters:
  - Batch size: 32
  - Number of epochs: 3
  - Tokenizer max length: 256
