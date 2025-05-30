# 🎬 Amazon Prime TV Shows and Movies – Exploratory Data Analysis (EDA)

This project explores and analyzes the metadata of Amazon Prime Video titles using **Exploratory Data Analysis (EDA)** techniques. It provides insights into content distribution, genre popularity, rating trends, production country dominance, and the involvement of actors and directors over the years.

---

## 📁 Dataset Overview

The project is based on two datasets:

- **`titles.csv`** – Metadata of each title including type, release year, genre, IMDb/TMDb scores, certifications, and more.
- **`credits.csv`** – Names and roles of individuals (actors/directors) involved in each title.

---

## 🛠️ Technologies & Libraries Used

| Tool         | Purpose                          |
|--------------|----------------------------------|
| `pandas`     | Data loading and manipulation    |
| `numpy`      | Numerical operations             |
| `matplotlib` | Data visualization               |
| `seaborn`    | Statistical plotting             |
| `collections`| Frequency counting (Counter)     |
| `ast`        | Safe string-to-list conversion   |

---

## 🎯 Project Objectives

- Understand the distribution of content by type.
- Discover temporal trends in content releases.
- Identify popular genres.
- Compare IMDb and TMDb ratings.
- Visualize correlation between numerical attributes.
- Explore country-wise production statistics.
- Examine rating trends across age certifications.
- Highlight the most frequent actors and directors.

---

## 🔍 Visualizations (In Chronological Order)

### 1️⃣ Distribution of Movies and Shows
Analyzes how content is split between movies and TV shows.

![Distribution of Movies and Shows](https://github.com/PruthyirajM26/Amazon_Prime_TV_Shows_and_Movies_Exploratory_Data_Analysis/blob/e3538986933038dd5dc4843425bbb97d56fa5d27/Image/Distribution%20of%20Movies%20and%20Shows.png)

---

### 2️⃣ Number of Titles Released Over Years
Shows the frequency of content release over time, helping identify spikes or trends in production.

![Number of Titles Released Over the Years](https://github.com/PruthyirajM26/Amazon_Prime_TV_Shows_and_Movies_Exploratory_Data_Analysis/blob/be400cd0c9c923b87d8100cc12fb69b52a258388/Image/Number%20of%20Titles%20Released%20Over%20the%20Years.png)

---

### 3️⃣ Top 10 Genres
Highlights the most common genres available on Amazon Prime.

![Top 10 Genres](https://github.com/PruthyirajM26/Amazon_Prime_TV_Shows_and_Movies_Exploratory_Data_Analysis/blob/4dbef5cc38ec9f8a0343ab8740550c65d84a9d9b/Image/Top%2010%20Genres.png)

---

### 4️⃣ IMDB vs TMDB Scores by Content Type
Compares scores from two popular rating platforms and how they differ by content type.

![IMDB vs TMDB Scores by Content Type](https://github.com/PruthyirajM26/Amazon_Prime_TV_Shows_and_Movies_Exploratory_Data_Analysis/blob/be400cd0c9c923b87d8100cc12fb69b52a258388/Image/IMDB%20vs%20TMDB%20Scores%20by%20Content%20Type.png)

---

### 5️⃣ Correlation Heatmap
Visual correlation matrix of numerical features to find relationships among them.

![Correlation Heatmap](https://github.com/PruthyirajM26/Amazon_Prime_TV_Shows_and_Movies_Exploratory_Data_Analysis/blob/be400cd0c9c923b87d8100cc12fb69b52a258388/Image/Correlation%20Heatmap.png)

---

### 6️⃣ Top 10 Production Countries
Displays countries that produce the most content available on Amazon Prime.

![Top 10 Production Countries](https://github.com/PruthyirajM26/Amazon_Prime_TV_Shows_and_Movies_Exploratory_Data_Analysis/blob/6e2c71d652a39271bc8e3b04b80fb47171260a81/Image/Top%2010%20Production%20Countries.png)

---

### 7️⃣ IMDB Rating Distribution by Age Certification
Explores how IMDb scores vary across different age ratings using a box plot.

![IMDB Rating Distribution by Age Certification](https://github.com/PruthyirajM26/Amazon_Prime_TV_Shows_and_Movies_Exploratory_Data_Analysis/blob/5ec3c2f582e17ff32315b38cce9050d905df48e3/Image/IMDB%20Rating%20Distribution%20by%20Age%20Certification.png)

---

### 8️⃣ Content Trend by Year
Shows how production trends (TV vs Movie) change over time.

![Content Trend by Year](https://github.com/PruthyirajM26/Amazon_Prime_TV_Shows_and_Movies_Exploratory_Data_Analysis/blob/5ec3c2f582e17ff32315b38cce9050d905df48e3/Image/Content%20Trend%20by%20Year.png)

---

### 9️⃣ Top Actors and Directors by Frequency

#### 🧑‍🎤 Top 10 Actors by Frequency
Identifies actors who appear most frequently in the dataset.

![Top 10 Actors by Frequency](https://github.com/PruthyirajM26/Amazon_Prime_TV_Shows_and_Movies_Exploratory_Data_Analysis/blob/5ec3c2f582e17ff32315b38cce9050d905df48e3/Image/Top%2010%20Actors%20by%20Frequency.png)

#### 🎬 Top 10 Directors by Frequency
Identifies directors with the highest involvement in Prime titles.

![Top 10 Directors by Frequency](https://github.com/PruthyirajM26/Amazon_Prime_TV_Shows_and_Movies_Exploratory_Data_Analysis/blob/5ec3c2f582e17ff32315b38cce9050d905df48e3/Image/Top%2010%20Directors%20by%20Frequency.png)

---

## 📝 How to Use This Project

### Prerequisites

- Python 3.x
- Jupyter Notebook (optional, but recommended)
