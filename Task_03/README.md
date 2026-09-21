# 📱 Unveiling the Android App Market — Google Play Store Analysis

## 📌 Project Overview

This project analyzes the **Google Play Store ecosystem** to uncover patterns in app categories, ratings, installs, pricing, estimated revenue, and user sentiment.

The analysis focuses on transforming messy real-world app data into meaningful insights that can help developers understand market competition, user preferences, and potential opportunities when planning a new app.

This project was completed as part of the **OIBSIP / AICTE Internship – Task** 3

---

## 🎯 Objectives

* Clean and preprocess Google Play Store datasets
* Analyze app distribution across categories
* Identify highly saturated app categories
* Explore app ratings and category-level rating patterns
* Analyze app size and number of installs
* Compare free and paid applications
* Analyze pricing patterns of paid apps
* Estimate potential revenue by category
* Perform sentiment analysis on user reviews
* Explore positive, negative, and neutral sentiments
* Analyze sentiment patterns across app categories
* Create an interactive visualization using Plotly
* Generate data-driven insights for app developers

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Plotly**
* **TextBlob / Sentiment Analysis**
* **Jupyter Notebook**

---

## 📂 Datasets

### 1. Google Play Store Apps Dataset

Contains information about Android applications, including:

* App
* Category
* Rating
* Reviews
* Size
* Installs
* Type
* Price
* Content Rating
* Genres
* Last Updated
* Current Version
* Android Version

### 2. Google Play Store User Reviews Dataset

Contains user review information including:

* App
* Translated Review
* Sentiment
* Polarity
* Subjectivity

---

## 🧹 Data Cleaning & Preprocessing

The datasets contained several real-world data quality issues. The following preprocessing steps were performed:

* Handled missing values
* Removed duplicate records
* Converted numerical columns to appropriate data types
* Cleaned the `Installs` column by removing characters such as `+` and commas
* Converted `Price` into numeric format
* Converted `Reviews` into numeric format
* Processed app size information
* Prepared review text for sentiment analysis
* Created additional variables required for analysis

---

## 📊 Exploratory Data Analysis

### 📱 Category Analysis

Analyzed the distribution of applications across different categories to identify highly populated and competitive areas of the Play Store.

### ⭐ Ratings Analysis

Explored:

* Overall rating distribution
* Average rating across categories
* Rating patterns among applications

### 📥 Size & Installs Analysis

Investigated the relationship between application size and number of installs using scatter plots and correlation analysis.

### 💰 Pricing Analysis

Analyzed:

* Free vs. paid applications
* Distribution of paid app prices
* Estimated revenue across categories

Estimated revenue was calculated using:

**Estimated Revenue = Installs × Price**

The estimate is intended for comparative analysis rather than actual reported earnings.

---

## 💬 Sentiment Analysis

User reviews were analyzed to classify feedback into:

* **Positive**
* **Negative**
* **Neutral**

Sentiment analysis was performed using review-level polarity and subjectivity measures.

The analysis also explored sentiment patterns across application categories to understand how users respond to different types of apps.

---


## 📈 Interactive Visualization — Plotly

  Both interactive category-level visualization was created using Plotly to explore:

 **1) App count VS Average app rating by category**

 * The interactive chart allows users to hover over categories
* Explore the app count and average rating dynamically.

**2) Number of Reviews vs. App Rating**

The visualization allows users to:

* Hover over individual applications
* Explore app-level details
* Zoom into the data
* Compare categories interactively

---

## 19. Final Conclusion

### Key Insights

1. **Saturation Insight:**
   FAMILY has the largest number of apps (1,832), indicating strong competition in this category.

2. **Rating Insight:**
   EVENTS has the highest average rating among categories with available ratings (4.44/5).

3. **Revenue Insight:**
   FAMILY has the highest estimated revenue among paid apps ($113.68M), calculated using installs × price.

4. **Developer Takeaway:**
   Category selection should consider **competition, user ratings, monetization potential, and review sentiment** together rather than relying on popularity alone.

### Key Questions Answered

* Which categories are most saturated?
* What does the rating distribution look like?
* Does app size appear related to installs?
* Are most apps free or paid?
* How are paid-app prices distributed?
* Which categories have the highest estimated revenue?
* What is the overall user sentiment?
* Which categories have the most positive and negative sentiment?

### Final Recommendation

A new developer should evaluate **competition, average ratings, estimated revenue, and user sentiment** before selecting an app category. Categories with user demand, manageable competition, and clear problems identified through reviews may provide useful opportunities for new apps.


---

## 👩‍💻 Author

**Mehwish Iqbal**

Aspiring Data Analyst 

Linkdin:  www.linkedin.com/in/mehwish-iqbal-2584b3395

GitHub:   https://github.com/mehwish-Iqbal/data-analyst-portfolio/blob/05c7fd9b95188471fe8306926de7fda077e619eb/README.md

---

## 🎓 Internship Experience

**OIBSIP / AICTE Internship — Final Project (Task 3)**

This project marks the completion of my internship project work and provided practical experience in working with a real-world dataset using **Python**.

Through this project, I strengthened my skills in **data cleaning, exploratory data analysis, data visualization, sentiment analysis, and deriving business-oriented insights** from data.

The internship provided valuable hands-on exposure to the **end-to-end data analysis workflow**, from raw data preprocessing to visualization and insight generation.

### 📌 Completion Note

Successfully completed the final project of the internship, applying practical data analysis techniques to uncover meaningful insights from the **Google Play Store ecosystem**.

 **Thanks**
