# AIM-Task2
# 🧠 Pokémon Data Exploration and Visualization

## 🎯 Objective
To understand the Pokémon dataset using **statistics** and **visualizations**.

## 🛠️ Tools Used
- **Pandas** – for data manipulation and summary statistics  
- **Matplotlib & Seaborn** – for basic and statistical visualizations  
- **Plotly** – for interactive exploration  

---

## 📊 Step-by-Step Breakdown

### 1️⃣ Summary Statistics
We used `df.describe()` to generate:
- Mean, Median, Standard Deviation
- Min, Max, and Quartiles

This helped us understand the spread and central tendencies of numeric features like `HP`, `Attack`, `Defense`, etc.

---

### 2️⃣ Distribution Analysis

#### ✅ **Histogram**
We created histograms (e.g., for `HP`) to visualize the frequency distribution of numerical values.

#### ✅ **Boxplot**
Boxplots for key features (`HP`, `Attack`, `Defense`, `Speed`) revealed:
- Range
- Median
- Outliers
- Skewness

---

### 3️⃣ Relationship Between Features

#### ✅ **Pairplot (Seaborn)**
Pairplot helped us understand pairwise relationships among numeric stats.  
For example: the relationship between `Attack` and `Defense`.

#### ✅ **Correlation Heatmap**
We used a heatmap to visualize:
- How strongly features correlate
- E.g., `Attack` and `Speed` may not always correlate, while `Sp. Atk` and `Sp. Def` might

---

### 4️⃣ Trend & Pattern Discovery

#### ✅ **Plotly Interactive Scatter Plot**
We extracted the `attack` and `defense` values from the nested `Stats` column and plotted them:

- X-axis: `Attack`  
- Y-axis: `Defense`  
- Color: `Type`  
- Hover: Pokémon `Name`

This allowed us to:
- Detect clusters of Pokémon with similar stats
- Notice extremes (very high Attack or very low Defense)
- Compare Pokémon types

---

### 5️⃣ Inferences from Visuals

From the plots, we can infer:
- Some types (like Dragon or Fighting) are skewed toward high `Attack`
- Outliers exist with unusually high `Defense` or `Speed`
- A few Pokémon balance both `Attack` and `Defense`, while others trade one off for the other

---

## ✅ Conclusion

We successfully:
- Explored the dataset statistically
- Visualized distributions and relationships
- Identified patterns and potential anomalies
- Gained insights from visual storytelling

---



