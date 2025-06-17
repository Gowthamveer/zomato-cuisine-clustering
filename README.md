# Zomato Cuisine Clustering for Recommendations 🍽️

This project applies unsupervised learning using **K‑Means Clustering** to categorize restaurants and cuisines based on user reviews and ratings. It aims to enhance Zomato's recommendation engine by discovering customer preference patterns and grouping similar cuisines together.

## 📌 Objective
Uncover meaningful patterns in restaurant data and suggest personalized dining recommendations by grouping similar cuisines.

## 🧠 Techniques Used
- **TF‑IDF Vectorization** for transforming cuisine strings into numerical features  
- **K‑Means Clustering** to group restaurants/cuisines  
- **Elbow & Silhouette Methods** to determine optimal number of clusters  

## 📊 Dataset
File: `zomato.csv` (ISO‑8859‑1 encoded) – contains restaurant names, cuisines, ratings, votes, etc.

## 🛠️ Technologies
| Component          | Description                     |
|--------------------|---------------------------------|
| Language           | Python                          |
| Libraries          | Pandas, Scikit‑learn, Matplotlib|
| Feature Extraction | TF‑IDF Vectorizer               |
| Clustering         | K‑Means (Unsupervised Learning) |

## 🧪 How to Run
```bash
# clone your repo & cd into it
pip install -r requirements.txt
jupyter notebook zomato_clustering.ipynb
```

## ✅ Status
**Completed** – ready for submission.
