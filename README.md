# 🎸 Rolling Stones Spotify Track Analysis

This project explores the musical evolution of The Rolling Stones using their track-level Spotify data. It applies Exploratory Data Analysis (EDA), feature engineering, dimensionality reduction (PCA), and clustering (KMeans) to uncover patterns and groupings within their discography.

---

## 📂 Dataset

- **Source**: [Kaggle / Spotify API]
- **File**: `rolling_stones_spotify.csv`
- Contains audio features (e.g., tempo, energy, valence) of The Rolling Stones' tracks along with metadata like album name and release date.

---

## 📊 Key Features of Analysis

### 🧹 1. Data Cleaning & Preprocessing
- Converted date columns to datetime
- Handled missing values & duplicates
- Capped outliers using IQR method
- Extracted year/month features from release date

### 📈 2. Exploratory Data Analysis (EDA)
- Boxplots of all numerical features
- Time-series plots of feature trends across decades
- Top tracks and albums by average popularity

### 🔗 3. Feature-Popularity Correlation
- Regression analysis of features vs. popularity
- Correlation heatmap across different time periods

### 🧪 4. Principal Component Analysis (PCA)
- Reduced 11 audio features into 6 principal components
- Explained ~90% of variance using PCA

### 🤖 5. KMeans Clustering
- Clustered tracks into 3 groups based on audio profiles
- Visualized clusters in both PCA and original feature space

---

## 📌 Insights

- Popularity is influenced by features like **energy**, **valence**, and **loudness**
- Certain albums consistently outperform others in popularity
- Clear clusters of musical style are evident over time

---

## 🛠️ Tools & Libraries

- Python (Jupyter Notebook)
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn` for PCA and KMeans

---

## 🧠 Potential Extensions

- Use t-SNE or UMAP for deeper cluster visualization
- Build a track recommendation system using similarity metrics
- Compare Rolling Stones with other artists or genres

---

## 👨‍💻 Author

- **You** (Your Name / LinkedIn / GitHub)

---

## 📜 License

This project is open-source and available under the MIT License.
