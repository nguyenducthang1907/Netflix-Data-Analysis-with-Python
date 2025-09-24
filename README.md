# 📊 Netflix Data Analysis with Python

This project demonstrates **end-to-end data analysis** of the Netflix dataset using **Python**.  
Libraries used: **pandas, matplotlib, seaborn**.  

The workflow covers: **data loading, cleaning, exploratory data analysis (EDA), visualization, insights, and recommendations**.

---

## 🚀 Workflow

### 1. Data Loading & Inspection
- Loaded dataset with `pandas`
- Explored shape, columns, missing values
- Previewed first 20 rows

### 2. Data Cleaning
- Converted `date_added` → `datetime`
- Extracted numeric values + units from `duration`
- Handled missing values in `director`, `cast`, `country` (filled with `"Unknown"`)
- Added `main_country` column for the first listed country

### 3. Exploratory Data Analysis (EDA)
We focused on 5 main perspectives:
1. Content distribution (Movies vs TV Shows)  
2. Trends over time (titles added per year)  
3. Content by country (top producers)  
4. Genre distribution (most common categories)  
5. Duration by rating (movie lengths vs audience category)  

---

## 📈 Visualizations & Commentary

### 1. Distribution of Movies vs TV Shows
![Movies vs TV Shows](2.png)  

- **Observation:** ~70% of titles are Movies, ~30% are TV Shows.  
- **Insight:** Netflix’s library is heavily skewed toward Movies, but TV Shows are still a significant part of its offering.  
- **Commentary:** This aligns with Netflix’s strategy — while Movies help expand catalog volume, TV Shows drive long-term viewer engagement.  

---

### 2. Content Growth Over Time
![Content Added per Year](4.png)  

- **Observation:** Content growth was slow until ~2015, then skyrocketed and peaked in 2019 (~2000 titles). Slight decline after 2020.  
- **Insight:** The rapid growth period corresponds with Netflix’s global expansion strategy. The drop post-2020 may be linked to the COVID-19 pandemic disrupting production.  
- **Commentary:** This chart clearly shows Netflix’s “hockey stick” growth phase and recent stabilization.  

---

### 3. Top 10 Countries by Content
![Top Countries](1.png)  

- **Observation:** The US dominates (>2700 titles), followed by India (~1000) and the UK (~400).  
- **Insight:** Netflix still relies heavily on US content but is diversifying into India and Europe. The rise of Korea and Japan is also visible.  
- **Commentary:** This reflects Netflix’s dual approach: maintain US dominance while investing in international/regional content.  

---

### 4. Top 10 Genres on Netflix
![Top Genres](3.png)  

- **Observation:** International Movies, Dramas, and Comedies lead the platform. Documentaries and Action also strong.  
- **Insight:** Netflix caters to broad tastes but particularly invests in dramas and international content.  
- **Commentary:** This genre mix shows Netflix balancing global appeal (International Movies) with audience favorites (Dramas & Comedies).  

---

### 5. Movie Duration by Rating
![Movie Duration by Rating](5.png)  

- **Observation:** Most movies fall in the 80–120 min range across ratings. Ratings PG-13 and TV-14 show the widest spread.  
- **Insight:** Regardless of audience rating, Netflix movies tend to have consistent lengths. Outliers exist but cluster tightly around 90–100 minutes.  
- **Commentary:** This boxplot suggests Netflix optimizes movie length to keep attention span, with only minor variation across age groups.  

---

## 💡 Key Insights
- **Movies dominate** Netflix’s catalog (~70%) compared to TV Shows.  
- **The US is the biggest content provider**, but India, the UK, and Asian countries are emerging strongly.  
- **Content exploded after 2015**, peaking in 2019, then stabilizing post-2020.  
- **Top genres** are International Movies, Dramas, and Comedies.  
- **Movie durations are consistent**, typically ~90–120 minutes regardless of rating.  

---

## ✅ Recommendations
- **Expand regional production** (India, Korea, Japan) to capture fast-growing audiences.  
- **Balance catalog** with more TV Shows for long-term viewer engagement.  
- **Double down on dramas, comedies, and international titles**, while exploring niche categories (independent, documentaries) for differentiation.  
- **Maintain movie durations** in the sweet spot (~90–120 minutes), ensuring audience engagement.  

---
