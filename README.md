# Anime Data Analysis 📊

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on an anime dataset using Python. The analysis explores anime ratings, types, studios, release years, episode counts, and tags to identify meaningful trends and patterns.

The project uses Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, analysis, and visualization.

## 🎯 Objective

The main objective of this project is to analyze an anime dataset and discover useful insights related to:

* Anime ratings
* Anime types
* Number of episodes
* Anime studios
* Release years
* Anime tags
* Relationships between numerical features

## 📂 Dataset

The dataset contains information about **18,495 anime records** and **17 columns**.

Important columns include:

* Rank
* Name
* Japanese Name
* Type
* Episodes
* Studio
* Release Season
* Tags
* Rating
* Release Year
* End Year
* Description
* Content Warning
* Related Manga
* Related Anime
* Voice Actors
* Staff

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🔍 Data Analysis Performed

### 1. Data Loading

The dataset is loaded using Pandas.

```python
df = pd.read_csv("Anime.csv")
```

### 2. Data Exploration

The project examines:

* Dataset shape
* Column names
* Data types
* Statistical summary
* Missing values
* Duplicate records

### 3. Data Cleaning

The project checks for missing values and duplicate records before performing the analysis.

### 4. Rating Distribution

A histogram is used to understand the distribution of anime ratings.

**Observation:**
Most anime ratings are concentrated around the middle-to-high rating range.

### 5. Anime Type Distribution

A count plot is used to compare different anime types such as:

* TV
* Movie
* OVA
* Special
* ONA

**Observation:**
TV anime represents the largest category in the dataset.

### 6. Top 10 Highest-Rated Anime

The project identifies the ten highest-rated anime using their rating values.

### 7. Episode Distribution

A histogram is used to analyze the distribution of anime episode counts.

**Observation:**
Most anime have relatively fewer episodes, while a smaller number of long-running anime have significantly more episodes.

### 8. Correlation Analysis

A correlation heatmap is used to examine relationships between numerical variables.

### 9. Top Anime Studios

The project identifies studios with the highest number of anime entries.

### 10. Anime Release Trends

The number of anime released across different years is analyzed to understand production trends over time.

### 11. Anime Tags

Anime tags are extracted and analyzed to identify frequently occurring tags.

## 📊 Key Insights

1. TV is the most common anime type.
2. Most anime ratings are concentrated around the 7–8 range.
3. Anime production increased significantly after 2000.
4. A relatively small number of studios contribute a large number of anime.
5. Most anime have fewer than 30 episodes.
6. Action, Comedy, Fantasy, and Drama are among the frequently occurring tags.

## 📈 Visualizations

The project includes visualizations such as:

* Anime Rating Distribution
* Anime Type Distribution
* Top 10 Highest-Rated Anime
* Episode Distribution
* Correlation Heatmap
* Top Anime Studios
* Anime Release Trend
* Top Anime Tags

## 🚀 How to Run the Project

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the project folder

```bash
cd Anime-Data-Analysis
```

### Step 3: Install the required libraries

```bash
pip install -r requirements.txt
```

### Step 4: Start Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the notebook

Open:

```text
Anime_Data_Analysis.ipynb
```

Make sure `Anime.csv` is present in the project directory.

## 📁 Project Structure

```text
Anime-Data-Analysis/
│
├── README.md
├── Anime_Data_Analysis.ipynb
├── Anime.csv
├── requirements.txt
├── .gitignore
│
└── images/
    ├── rating_distribution.png
    ├── anime_types.png
    ├── top_10_anime.png
    ├── episodes_distribution.png
    ├── correlation_heatmap.png
    ├── top_studios.png
    ├── release_trend.png
    └── top_tags.png
```

## 🔮 Future Scope

Possible future improvements include:

* Building an Anime Recommendation System
* Predicting anime ratings using Machine Learning
* Creating an interactive dashboard using Streamlit
* Creating a Power BI dashboard
* Performing deeper genre and tag analysis

## 👨‍💻 Author

**Mohd Sarfaraz**

Computer Science and Engineering Student

---

⭐ If you find this project useful, consider giving the repository a star.
