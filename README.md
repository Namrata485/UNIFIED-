# 📊 Data Analysis Projects

This repository contains three data analysis projects performed using Python, Pandas, Matplotlib, Seaborn, and Plotly. Each project explores a different dataset, performs data cleaning, and visualizes insights using various EDA techniques.

---

## 📁 Project 1: Coffee Sales Analysis

### Dataset
- `coffee_sales.csv`: Transaction data including date, time, payment type, coffee name, and amount.

### Objectives
- Clean and explore coffee shop sales data.
- Visualize sales trends and patterns based on time and coffee type.

### Key Steps
- Missing value handling (card column).
- Extracted timestamp-based features: `Hour`, `Day`, `Month`, `Date`.
- Converted date columns to datetime.

### Visualizations
- Most popular coffee types.
- Sales by hour of the day.
- Sales by day of the week.
- Total revenue by coffee type.
- Heatmap of sales by hour and day.
- Daily revenue trends.

---

## 📁 Project 2: Drug Dataset - Side Effects & Effectiveness

### Dataset
- `drugs_side_effects_drugs_com.csv`: Medical data on drugs, side effects, categories, effectiveness, and ratings.

### Objectives
- Analyze the effectiveness and risks of drugs.
- Clean messy and missing data.
- Explore and visualize trends in ratings, categories, alcohol interactions, etc.

### Key Steps
- Dropped duplicates and filled missing values with `'Unknown'`.
- Converted `rating` to numeric and handled invalid values.
- Aggregated data by drug name and class.

### Visualizations
- Top 10 highest-rated drugs.
- Drug class distribution.
- Distribution of ratings.
- Alcohol interaction count.
- Pregnancy category-wise drug count.
- CSA category analysis.
- Rx vs OTC availability.
- Most common side effects (via text processing).

---

## 📁 Project 3: Netflix Content Analysis

### Dataset
- `netflix1.csv`: Metadata of Netflix titles including type, release year, country, rating, duration, and genre.

### Objectives
- Understand content trends on Netflix.
- Analyze content distribution across years, countries, and types.

### Key Steps
- Removed duplicates.
- Extracted `year_added` and `month_added` from `date_added`.

### Visualizations
- Netflix content added by year.
- Movies vs TV shows distribution.
- Top 10 countries by content count.

---

## 🛠 Tools & Libraries
- Python 3
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Plotly

---

## 💡 Author
Namrata Mahandru  
Third Year B.Tech CSE Student  
[Unified Mentor Internship Projects]

---

## 📌 Note
All datasets are anonymized and used solely for educational and analytical purposes. Future work may include interactive dashboards or machine learning applications.

