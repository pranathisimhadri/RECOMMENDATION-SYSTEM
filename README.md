# RECOMMENDATION-SYSTEM


COMPANY : CODTECH IT SOLUTIONS

NAME : Simhadri Pranathi 
INTERN ID : CT04DM549

DOMAIN : MACHINE LEARNING

DURATION : 4 WEEEKS

MENTOR : NEELA SANTOSH



## 🎬 Movie Recommendation System in Python

This project showcases a simple yet effective **Movie Recommendation System** built using Python. It leverages either **collaborative filtering**, **content-based filtering**, or a hybrid of both to suggest movies based on user preferences or movie similarity.

Implemented in a **Jupyter Notebook**, the project is beginner-friendly and focuses on core concepts of **recommendation engines** using libraries like **pandas**, **scikit-learn**, and optionally **surprise** or **cosine similarity** from `sklearn`.

---

## 📌 Problem Statement

With the explosion of online content, helping users find relevant items—like movies—is critical. This project aims to recommend movies to users based on either:

* What they've liked before (collaborative filtering)
* Similar features between movies (content-based)
* A hybrid approach using both user and item similarity

This implementation avoids heavy deep learning frameworks and demonstrates how classical ML + math can build efficient recommenders.

---

## 🧠 Workflow Overview

### 1. **Data Loading and Exploration**

* The dataset (e.g., MovieLens or custom CSV) is loaded using `pandas`.
* It includes movie titles, genres, ratings, and optionally user IDs.
* Exploratory Data Analysis (EDA) includes:

  * Rating distribution
  * Most popular movies
  * User activity

### 2. **Preprocessing**

* Cleaning the data: handling missing values, duplicates
* Feature engineering: genre encoding, tag parsing (if content-based)
* Creating a **user-item matrix** or **TF-IDF** vector for movie features

### 3. **Recommendation Engine**

Based on the approach, one or more of the following is implemented:

#### 🔁 Collaborative Filtering

* Based on user ratings
* Uses similarity metrics (cosine similarity, Pearson correlation)
* Can be user-based or item-based

#### 🧠 Content-Based Filtering

* Uses movie features like genre, description, tags
* Computes movie similarity using TF-IDF or count vectorization + cosine similarity

#### ⚖️ Hybrid (Optional)

* Combines both approaches for more robust suggestions

### 4. **Making Predictions**

* Recommends a list of similar or top-rated movies for a given:

  * User ID (collaborative)
  * Movie title (content-based)

* The output is ranked by relevance or similarity scores.

---

## ⚙️ Requirements

Install the required packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Optionally, for advanced collaborative filtering:

```bash
pip install scikit-surprise
```

---

## 🚀 How to Run

1. Download or clone the repository.
2. Open the notebook (`movie recommendation.ipynb`) in **Jupyter**.
3. Run each cell in sequence:

   * Load and explore the dataset
   * Preprocess and vectorize
   * Build the recommendation logic
   * Try custom movie/user queries

---

## 📦 Applications

* Personalized content recommendations (Netflix-style)
* E-commerce product suggestion systems
* News or book recommendation engines

output

![Image](https://github.com/user-attachments/assets/179d1542-d96f-46d4-9048-e465a7487581)
