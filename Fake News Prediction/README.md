# Fake News Prediction

This project predicts whether a piece of news is real or fake using natural language processing (NLP) and machine learning.

## Project Overview
The project leverages a dataset of news articles, processes the text using NLP techniques like stemming and TF-IDF vectorization, and trains a Logistic Regression model to classify news as real or fake.

## Repository Structure
```
Fake-News-Prediction/
├── src/
│   └── Fake_News_Prediction.ipynb   # Main notebook for the project
├── data/
│   └── train.csv                    # Dataset used for training the model
├── tests/
│   └── test_fake_news.py            # Unit tests for the project
├── docs/
│   └── README.md                    # Additional documentation
├── .gitignore                       # Ignored files/folders
├── LICENSE                          # Project license
├── README.md                        # Project overview (this file)
├── requirements.txt                 # Python dependencies
└── setup.py                         # Project installation setup
```

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Fake-News-Prediction.git
   cd Fake-News-Prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open and run the notebook:
   ```bash
   jupyter notebook src/Fake_News_Prediction.ipynb
   ```

## Dataset
The dataset `train.csv` contains news articles and their labels:
- `0`: Real news
- `1`: Fake news

It is located in the `data/` directory.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing
Contributions are welcome! Please read the `CONTRIBUTING.md` for guidelines.

## Acknowledgments
- The dataset source: [Kaggle](https://www.kaggle.com/c/fake-news)
