# Sentiment Analysis using DistilBERT – Case Study

This case study showcases the development of a lightweight, high-accuracy sentiment classification model using **DistilBERT**, optimized for CPU execution. The project focuses on training, evaluation, and optimization of a binary classifier for analyzing customer sentiments from the **Yelp Review Dataset**.

## 📌 Project Highlights

- **Model**: DistilBERT (`distilbert-base-uncased`) fine-tuned for binary sentiment classification
- **Dataset**: Yelp Reviews (1–2 stars = Negative, 4–5 stars = Positive)
- **Execution**: CPU-based training using Hugging Face Transformers
- **Preprocessing**: Text cleaning, tokenization, truncation & padding for uniform input
- **Evaluation Metrics**: Accuracy, F1 Score, Confusion Matrix
- **Tools Used**: Hugging Face Trainer API, Python, FastAPI (for deployment suggestion)
- **Optimization Suggestions**: Quantization, gradient accumulation, inference via FastAPI + Uvicorn

## 🚀 Future Enhancements

- Cloud deployment using AWS Lambda or Hugging Face Spaces
- Extended training epochs and larger datasets for generalization
- Integration of quantization-aware training for faster inference

## 🔗 Notebook Access

- [Sentiment Analysis Colab Notebook](https://colab.research.google.com/drive/1qQrJxiBuWPGEcdM65e6JXROdB9NELXdA?usp=sharing)

## 📄 Summary

This project illustrates how DistilBERT can deliver strong sentiment classification performance while being resource-efficient—ideal for real-world applications on constrained environments.

