**👗 Fashion Recommendation System**

This project implements a basic Fashion Recommendation System that ranks and displays products based on their ratings, price, and categories. It also provides interactive exploration with visualizations such as WordCloud and dropdown category filters.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**🧠 Problem Statement**

With thousands of fashion products available online, users often struggle to pick the best options based on brand, price, and quality.
This project aims to:

Rank products using a scoring formula (ratings + price factor).

Visualize brand popularity.

Allow interactive filtering by categories.
------------------------------------------------------------------------------------------------------------------------------------------------------------
**🛠️ Technologies Used**

Python

Pandas, NumPy → Data cleaning & manipulation

Matplotlib → Visualizations

WordCloud → Brand popularity visualization

NLTK → Stopwords removal for text processing

Scikit-learn (cosine similarity - reserved for future extension)

IPython Widgets → Interactive dropdown menus in Jupyter/Colab
----------------------------------------------------------------------------------------------------------------------------------------------------
**🔍 Workflow**

Data Loading → Upload dataset (CSV of fashion products).

Data Cleaning → Handle missing values and ensure numeric formats for ratings & prices.

Visualization → Generate a WordCloud showing most popular brands.

Scoring System → Rank products based on:

Score
=
(
0.7
×
Rating
)
+
(
0.3
×
(
1
−
Price
Max Price
)
)
Score=(0.7×Rating)+(0.3×(1−
Max Price
Price
	​

))

Higher rating = better.

Lower price = better.

Top Product Display → Show best products with brand, price, and score.

Interactive Exploration → Dropdown filter to explore top 10 products by category with clickable product links.
-------------------------------------------------------------------------------------------------------------------------------------------------------
**📊 Results & Observations**

Brand WordCloud → Visualizes which brands are most frequent in dataset.
<img width="1182" height="601" alt="WorldCloud" src="https://github.com/user-attachments/assets/cc2a39e5-27c5-42eb-ad24-1338a16e9ef0" />

Top Products Table → Displays highly rated & affordable products.
<img width="1491" height="838" alt="top_items" src="https://github.com/user-attachments/assets/14d6594e-4254-4a24-8d22-82918e79d684" />

Category Dropdown → Allows quick filtering of products (e.g., shirts, shoes, dresses).
<img width="1480" height="811" alt="explorer" src="https://github.com/user-attachments/assets/301e15c7-2632-4dcf-b778-4eebcb633781" />

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
**🚀 Future Enhancements**

Use TF-IDF + Cosine Similarity for NLP-based content recommendation (find similar products by name/description).

Include image-based recommendations using deep learning (CNN).

Improve scoring function by considering discount offers and popularity.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
📎 Dataset

Source: Myntra Fashion Clothing Dataset (Kaggle)
