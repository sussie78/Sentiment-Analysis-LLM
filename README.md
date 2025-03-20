# 📝 Sentiment Analysis with DistilBERT

## 🚀 Project Overview
This project fine-tunes a **DistilBERT model** to classify customer reviews as **Positive** or **Negative**.  
It uses a preprocessed dataset and is trained using **Hugging Face Transformers**.

## 📊 Dataset
- Contains **100 labeled reviews**  
- Preprocessing: **Tokenization, stopword removal**  
- Balanced using **oversampling** to avoid class imbalance  

## ⚙️ Model Details
- **Model Used**: DistilBERT (Pretrained Transformer)
- **Accuracy**: 87%
- **Training Library**: Hugging Face `transformers`
- **Fine-tuned on**: Google Colab with GPU

## 🛠️ How to Run This Project
### **1️⃣ Install Dependencies**
```sh
pip install transformers torch scikit-learn
