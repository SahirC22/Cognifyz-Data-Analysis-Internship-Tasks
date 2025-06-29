# Cognifyz-Data-Analysis-Internship-Tasks
This repository contains the complete implementation of Level 2 &amp; Level 3 tasks from my Data Analysis Internship at Cognifyz Technologies.

# 📊 Level 2 - Data Analysis Internship @ Cognifyz Technologies


## ✅ Tasks Covered

### **Task 1:** Restaurant Ratings Analysis
- Distribution of aggregate ratings
- Most common rating ranges
- Average number of votes and statistical overview

### **Task 2:** Cuisine Combination Analysis
- Identification of most frequent cuisine combinations
- Comparison of ratings between single and combination cuisines

### **Task 3:** Geographic Analysis
- Visualization of restaurant locations using latitude and longitude
- Geographic clustering of restaurants using KMeans
- Top cities by restaurant count

### **Task 4:** Restaurant Chains Analysis
- Identifying potential restaurant chains by name
- Rating and vote comparison: Chains vs. Independent restaurants
- City distribution and performance of top chains

# 📊 Level 3 - Data Analysis Internship @ Cognifyz Technologies


## ✅ Tasks Covered

  
### **Task 1:** Restaurant Reviews Analysis
Since dataset doesn't have actual review text, I've created both:
- **Actual Analysis**: Works with the 'Rating text' column in your dataset
- **Simulated Analysis**: Shows how to analyze actual review text if available

**Features:**
- Analysis of rating text categories (Excellent, Very Good, Good, etc.)
- Relationship between rating text and numerical ratings
- Simulated positive/negative keyword extraction
- Review length vs rating correlation analysis
- Statistical significance testing

### **Task 2:** Votes Analysis
**Comprehensive votes analysis including:**
- **Highest voted restaurants**: Top 10 with detailed information
- **Lowest voted restaurants**: Bottom 10 (excluding zero votes)
- **Correlation analysis**: Pearson and Spearman correlations between votes and ratings
- **Statistical significance**: P-value testing
- **Distribution analysis**: Votes patterns and quartile analysis
- **City-wise analysis**: Highest votes by city

### **Task 3:** Price Range vs Online Delivery & Table Booking
**Detailed relationship analysis:**
- **Service availability by price range**: Percentages for each price tier
- **Statistical testing**: Chi-square tests for significance
- **Combined services analysis**: Restaurants with both services
- **Cost analysis**: Average cost comparisons by service availability
- **Correlation analysis**: Price range correlations with services
- **Heatmap visualization**: Service availability matrix

### **Key Statistical Features:**
- **Pearson & Spearman correlations**
- **Chi-square independence tests**
- **P-value significance testing**
- **Quartile analysis**
- **Confidence intervals**

### **Visualizations Include:**
- Distribution plots and histograms
- Scatter plots with correlation lines
- Box plots for comparisons
- Bar charts for categorical analysis
- Heatmaps for relationship matrices
- Statistical summary tables

**Download NLTK data (run once):**
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('vader_lexicon')
```

## **Important Notes:**

- **Task 1**: If you have actual review text data, replace the simulated section with real text analysis
- **All tasks**: Include comprehensive statistical analysis with significance testing
- **Professional output**: Detailed insights and conclusions for each analysis
- **Flexible code**: Handles missing data and different data types gracefully


## 📦 Technologies Used
- Python
- pandas, numpy (Data manipulation)
- matplotlib, seaborn (Visualizations)
- folium, folium.plugins.MarkerCluster (Mapping)
- scikit-learn (KMeans clustering)

## 📁 Project Files
- `Cognifyz_Data_Analysis_Internship_Level2.ipynb` – Jupyter notebook with full analysis
- `Cognifyz_Data_Analysis_Internship_Level3.ipynb` – Jupyter notebook with full analysis
- `Dataset.csv` – Restaurant dataset (excluded here for privacy)

## 📌 Outcome
Successfully completed **Level 2** &amp; **Level 3** of the internship, gaining experience with exploratory data analysis, visualization, and geographic insights using real-world datasets.

---

### 💡 Author
**By**: Abdus Sahir Choudhury

**Internship Domain**: Data Analysis  

**Organization**: Cognifyz Technologies  

