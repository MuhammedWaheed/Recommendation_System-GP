# Arabic Sentiment Analysis & Recommendation System

## 📋 Overview

An intelligent recommendation system that analyzes Arabic text sentiment to recommend the most positively-reviewed items. The system processes multiple input files, classifies sentiment (positive, negative, neutral), and recommends files with the highest positive-to-negative ratio.

## ✨ Key Features

- **Multi-source Arabic text analysis** from Google Maps, Twitter, and Google Play reviews
- **Advanced sentiment classification** using ML and Deep Learning models
- **Real-time Twitter scraping** for current sentiment analysis
- **Visual analytics** with pie charts showing sentiment distribution
- **Smart recommendations** based on positive/negative ratio analysis
- **Web interface** built with Streamlit for easy interaction

## 🏗️ Architecture

### Data Collection
The system aggregates Arabic text data from multiple sources:
- **Google Maps** - Location and business reviews
- **Twitter** - Real-time tweets via Twitter API
- **Google Play** - App reviews and ratings

### Data Processing Pipeline

#### 1. Preprocessing
- Text cleaning and normalization
- Arabic-specific tokenization
- Stop word removal
- Feature extraction

#### 2. Machine Learning Models
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**
- **Decision Tree**
- **Random Forest**
- **Logistic Regression**

#### 3. Deep Learning Models
- **Feedforward Neural Network**
- **Convolutional Neural Network (CNN)**

#### 4. Sequential Models
- **Recurrent Neural Network (RNN)**
- **Gated Recurrent Unit (GRU)**
- **Long Short-Term Memory (LSTM)**

#### 5. Transfer Learning
- **CAML** - Pre-trained transformer model specialized for Arabic sentiment analysis

## 🚀 Getting Started


## 📊 How It Works

1. **Input Processing**: Users can either upload files containing Arabic text or enter search terms for real-time Twitter analysis

2. **Sentiment Classification**: The system applies multiple ML/DL models to classify text into:
   - ✅ Positive
   - ❌ Negative  
   - ➖ Neutral

3. **Visualization**: Results are displayed as pie charts showing the percentage distribution of sentiments for each input

4. **Recommendation Engine**: The system calculates the positive/negative ratio for each file and recommends items with the highest ratios

## 🛠️ Technology Stack

- **Backend**: Python
- **ML/DL Frameworks**: TensorFlow/PyTorch, Scikit-learn
- **Web Framework**: Streamlit
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Plotly
- **NLP**: Transformers, NLTK
- **API Integration**: Tweepy (Twitter API)

## 📁 Project Structure

```
Recommendation_System-GP-/
├── data/
│   ├── raw/           # Original datasets
│   ├── processed/     # Preprocessed data
│   └── models/        # Trained models
├── src/
│   ├── preprocessing/ # Data preprocessing scripts
│   ├── models/        # ML/DL model implementations
│   ├── scraping/      # Twitter scraping module
│   └── utils/         # Utility functions
├── app.py             # Streamlit application
├── requirements.txt   # Project dependencies
├── config.yaml        # Configuration file
└── README.md         # Project documentation
```

## 📝 Documentation

For detailed usage instructions, please refer to our [User Guide](https://github.com/AbdelrhmanMohamed2001/Recommendation_System-GP-/blob/main/How%20to%20use%20out%20syst).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

- Abdelrhman Mohamed - [GitHub](https://github.com/AbdelrhmanMohamed2001)
- [Add other team members]

## 🙏 Acknowledgments

- CAML model developers for the pre-trained Arabic sentiment analysis model
- Arabic NLP community for datasets and resources
- [Add other acknowledgments]

## 📧 Contact

For questions or support, please open an issue or contact the maintainers.

---
⭐ Star this repository if you find it helpful!
