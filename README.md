# Play Store App Analysis

##  Project Overview

This project analyzes Google Play Store app data to uncover key factors influencing app success, user engagement, and market trends. The analysis focuses on ratings, installs, reviews, pricing strategies, and category performance.

An interactive **Power BI dashboard** was built to visualize insights and support data-driven decision-making for app development and marketing strategies.

---

##  Objectives

* Identify key factors driving app success
* Analyze relationship between ratings, installs, and reviews
* Understand impact of pricing and app size
* Discover high-performing categories and opportunities

---

##  Dataset

* Source: [Kaggle - Google Play Store Apps Dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
* Records: ~10,000 apps
* Features:

  * App, Category, Rating, Reviews
  * Size, Installs, Type, Price
  * Content Rating, Genres, Last Updated

---

##  Data Cleaning & Preprocessing

* Removed duplicates and invalid rows
* Handled missing values in Rating
* Converted:

  * Installs → numeric
  * Price → numeric
  * Size → MB format
* Fixed inconsistent values (e.g., “Free” in numeric columns)
* Converted date columns to datetime format

---

##  Dashboard Features (Power BI)

### 🔹 KPIs

* ⭐ Average Rating
* 📥 Total Installs
* 📱 Total Apps
* 📝 Total Reviews
* 💰 Revenue Potential

---

###  Visualizations

* Category vs Installs (Top performing categories)
* Free vs Paid Apps Distribution
* Rating Distribution
* Size vs Installs (Scatter)
* Reviews vs Installs (Engagement analysis)
* Price vs Rating (Paid apps analysis)
* Top Apps Table

---

###  Filters (Interactive)

* Category
* Price Category (Free/Paid)
* Content Rating

---

##  Key Insights

* ⭐ Majority of apps are **free (~90%)**
* ⭐ Ratings are mostly between **4.0 – 4.5**
* ⭐ Strong relationship between **reviews and installs**
* ⭐ High installs do not always mean high ratings
* ⭐ Category plays a major role in app success
* ⭐ Large app sizes may reduce downloads

---

##  Business Recommendations

###  Developers

* Focus on user experience to improve ratings
* Keep app size optimized
* Encourage user reviews

###  Marketing Team

* Promote free apps with monetization strategies
* Focus on high-demand categories

###  Product Managers

* Target categories with **high installs but lower ratings**
* Identify gaps for improvement

---

##  Tools & Technologies

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Power BI
* Jupyter Notebook

---

##  Project Structure

```
📁 Google-Play-Store-Analysis
 ┣ 📄 cleaned_google_playstore.csv
 ┣ 📄 analysis.ipynb
 ┣ 📄 dashboard.pbix
 ┣ 📄 README.md
```

---

##  Conclusion

This project demonstrates how data analytics can be used to extract actionable insights from app data, helping businesses improve product strategy, user engagement, and revenue generation.



---
