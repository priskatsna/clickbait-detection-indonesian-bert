# Clickbait Classification on Indonesian News Headlines using BERT

## Project Summary
This project aims to classify Indonesian news headlines into two categories: **clickbait** or **non-clickbait**. We fine-tuned a pre-trained **BERT model** on labeled headline data to build a text classification system. This work explores how modern language models can be adapted to help detect potentially manipulative or misleading content in digital media.

### ⭐ Situation  
News platforms and content aggregators in Indonesia often face a challenge with **clickbait headlines**, which aim to attract attention but may mislead readers. Detecting such headlines manually is inefficient and subjective.

### ⭐ Task  
As part of a research project, I aimed to **develop an automated solution** that could identify clickbait headlines in Indonesian using a **fine-tuned transformer-based model (BERT)**.

### ⭐ Action  
- Collected and preprocessed a dataset of 12,000+ Indonesian news headlines labeled as clickbait or non-clickbait.  
- Utilized the **HuggingFace Transformers** library and fine-tuned the **Multilingual BERT (bert-base-multilingual-uncased)** model.  
- Implemented text tokenization, attention masking, and label encoding using PyTorch and Transformers.
- Trained and evaluated the model on Google Colab.

### ⭐ Result  
- Achieved an **accuracy of 75.4%** and an **Validation Accuracy of 81.7%** on the test set.  
- The model effectively captured patterns in clickbait language, especially emotional and curiosity-driven wording.
- This project demonstrates the capability of multilingual BERT to handle Indonesian-language NLP tasks with minimal customization.
