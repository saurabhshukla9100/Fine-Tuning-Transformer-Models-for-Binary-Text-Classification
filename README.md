# Fine-Tuning-Transformer-Models-for-Binary-Text-Classification
Fine-tuned a pre-trained BERT model using TensorFlow &amp; Hugging Face Transformers for binary text classification on IMDb reviews, achieving high accuracy with optimized preprocessing and evaluation pipelines.
# BERT Fine-Tuning for Text Classification

This project demonstrates fine-tuning of a pre-trained **BERT (Bidirectional Encoder Representations from Transformers)** model using **TensorFlow** and **Hugging Face Transformers** for **binary text classification**.  

The model is trained and evaluated on the **IMDb movie reviews dataset**, where the task is to classify reviews as **positive** or **negative**.  

---

## 🚀 Project Description
- Implemented **text preprocessing** and tokenization using Hugging Face `BertTokenizerFast`.  
- Fine-tuned **`bert-base-uncased`** model with a custom classification head for sentiment analysis.  
- Built efficient input pipelines with **`tf.data.Dataset`** for scalable training.  
- Evaluated model using **accuracy, AUC, precision, recall, and F1-score**.  
- Achieved high accuracy on a reduced IMDb dataset subset with potential to scale to full dataset.  

---

## 🛠️ Tech Stack
- **Python 3**  
- **TensorFlow 2.x**  
- **Hugging Face Transformers**  
- **scikit-learn**  
- **datasets (Hugging Face Datasets library)**  

---

## 📂 Project Structure
