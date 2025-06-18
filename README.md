# Sentence-Embeddings-Using-N-Gram-Features-and-Contrastive-Learning-for-Multilingual-Datasets

This project explores a novel approach to generating sentence embeddings by leveraging **N-gram features** combined with **contrastive learning**. It aims to improve semantic representation across **multilingual datasets**, especially for low-resource languages.

---

## 🚀 Features

- Sentence embeddings using character and word N-grams  
- Contrastive learning framework to align similar sentences  
- Works across multilingual and domain-diverse datasets  
- Evaluation using cosine similarity and clustering visualization

---

## 📁 Datasets Used

- `Harry Potter and The Half-Blood Prince.txt` – Fictional narrative
- `bible.txt` – Multilingual structured text
- `Dataset25.txt` – Custom multilingual dataset

---

## 🛠️ Setup & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/MS134340/Sentence-Embeddings-Using-N-Gram-Features-and-Contrastive-Learning-for-Multilingual-Datasets.git
   cd Sentence-Embeddings-Using-N-Gram-Features-and-Contrastive-Learning-for-Multilingual-Datasets

## Install required libraries
pip install numpy pandas scikit-learn matplotlib seaborn

## Run the notebook
Open and execute the .ipynb file in Jupyter or Google Colab.

## 📊 Results Summary
Outperformed simple TF-IDF and averaging methods.
Embeddings better captured sentence-level semantic similarity.
Contrastive loss improved clustering of similar meanings.

🧠 Techniques Used
N-gram Feature Engineering
Sentence Vector Aggregation
Supervised Contrastive Loss
Cosine Similarity Evaluation

📂 Project Structure
├── Dataset/
│   ├── Dataset25.txt
│   ├── bible.txt
│   └── Harry Potter and The Half-Blood Prince.txt
├── Sentence-Embeddings-Using-N-Gram-Features.ipynb
└── README.md
