# 📚 Audible Insights: Intelligent Book Recommendations

Welcome to **Audible Insights**, an intelligent book recommendation system designed to personalize the reading (or listening!) experience using powerful machine learning, NLP, and clustering techniques. This end-to-end project retrieves, processes, analyzes, and serves book suggestions through a user-friendly Streamlit web app deployed on AWS. 🚀

---

## 🎯 Project Goals

Design a recommendation system that:
- Retrieves and processes book data
- Cleans and merges datasets
- Applies NLP and clustering techniques
- Deploys a user-friendly application via Streamlit on AWS

---

## 🧠 Skills You'll Gain

- Python Scripting 🐍  
- Data Cleaning & Preprocessing 🧹  
- Exploratory Data Analysis (EDA) 📊  
- Machine Learning & NLP 🤖  
- Streamlit Web App Development 🖥️  
- AWS Deployment ☁️

---

## 🌍 Domain

**Recommendation Systems** – Empowering readers, authors, libraries, and retailers with intelligent book suggestions.

---

## 💼 Business Use Cases

- **📖 Personalized Reading Experience:** Tailor book suggestions to user preferences.
- **🏢 Enhanced Library Systems:** Boost engagement in libraries and bookstores.
- **🖋️ Publisher Insights:** Help publishers and authors understand market trends.
- **📈 Reader Engagement:** Encourage deeper user interaction through personalized discovery.

---

## 🧭 Approach

### 1. **Data Preparation**
- Use two datasets containing book metadata and ratings.
- Merge based on shared attributes like title and author.

### 2. **Data Cleaning**
- Handle missing, inconsistent, or duplicate records.
- Standardize formats (e.g., genres, ratings).

### 3. **Exploratory Data Analysis (EDA)**
- Analyze genre trends, rating distributions, and publication patterns.
- Visualize top-rated books, most common genres, and more.

### 4. **NLP and Clustering**
- Apply NLP on book titles/descriptions to extract features.
- Use clustering (K-Means, DBSCAN) to group similar books.

### 5. **Recommendation Models**
- Build and evaluate:
  - Content-Based Filtering
  - Clustering-Based Recommendations
  - Hybrid Models
    
### 6. **Application Development**
- Build a user interface with **Streamlit** to:
  - Accept user preferences
  - Show recommendations
  - Display insights from EDA

### 7. **Deployment**
- Deploy the Streamlit app on **AWS EC2** or **Elastic Beanstalk** for scalability and public access.

---

## 🔁 Data Flow & Architecture

```text
Datasets → Data Cleaning → Feature Engineering → Model Training 
         → Streamlit Interface → AWS Deployment
```

- 📦 **Data Storage:** Local or AWS S3
- 🛠️ **Libraries:** pandas, scikit-learn, nltk, Streamlit, Surprise
- ☁️ **Deployment:** AWS EC2 / Elastic Beanstalk

---

## 📂 Datasets Used

### Dataset 1: `Audible_Catalog.csv`
Includes:
- Book Title
- Author
- Rating & Review Count
- Price
- Description & Listening Time
- Genre & Rank

### Dataset 2: `Audible_Catalog_Advanced_Features.csv`
Includes:
- Book Title
- Author
- Rating & Review Count
- Price

---

## 🔎 Exploratory Data Analysis (EDA)

**Key Questions Answered:**
- What are the most popular genres?
- Which authors have the highest-rated books?
- Are there publication year trends?
- How do review counts affect ratings?

**Key Visualizations:**
- 📊 Bar Charts for genre frequency
- 🌡️ Heatmaps for rating correlations
- 📈 Line Charts for publication trends

---

## 🤔 Sample Analytical Scenarios

### Easy:
- Top-rated authors?
- Most common genres?
- Average book rating?

### Medium:
- How does genre similarity impact recommendations?
- Which feature combinations boost model accuracy?

### Scenario-Based:
- Recommend top 5 books for a science fiction fan
- Recommend thrillers based on past preferences
- Identify "hidden gem" books with high ratings but low visibility

---

## ✅ Results

By the end of this project, you’ll have:
- ✔️ A fully merged, cleaned, and analyzed dataset
- ✔️ NLP-enhanced, clustered feature sets
- ✔️ A deployed web app via Streamlit on AWS

---

## 🧪 Deliverables & Evaluation

| Component              | Evaluation Criteria                                      |
|------------------------|----------------------------------------------------------|
| Data Preparation       | Completeness, consistency, accuracy                      |
| NLP & Clustering       | Quality of text features and cluster separation          |
| Streamlit App          | Usability, responsiveness                                |
| AWS Deployment         | Accessibility, scalability, uptime                       |

---

## 🏷️ Technical Tags

**Python**, **Machine Learning**, **NLP**, **Clustering**, **Streamlit**, **AWS**, **Recommendation Systems**

---

## 🚀 Ready to Explore?

Clone the repository and start discovering your next favorite book today!

```bash
git clone https://github.com/SSaranya19/Audible-Insights-Intelligent-Book-Recommendations.git
cd Audible-Insights-Intelligent-Book-Recommendations
streamlit run book_recommendation_app.py
```
