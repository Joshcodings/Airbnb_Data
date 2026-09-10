# 🏠 Airbnb NYC 2019 Data Analysis

📊 This project analyzes Airbnb listings in New York City using the 2019 dataset. It explores trends in availability , pricing, reviews, and location to generate insights for travelers, hosts, and data enthusiasts.

---

## 🚀 Project Highlights

✅ Geographic analysis:  
- Listings by borough and neighbourhood.
- Heatmaps of latitude & longitude.
- Areas with highest prices or availability.

✅ Supply & demand:
- Distribution of room types (entire home, private room, shared)
- Average price by room type and location
- Most reviewed areas (demand proxy)

✅ Availability:
- Availability across room types
- Flag listings with <30 days availability (seasonal/long-term)

✅ Estimated revenue:
- Calculated based on price × minimum nights × reviews per month × 12

✅ Visualizations:
- Bar plots, boxplots, scatter plots, heatmaps
- Pie charts of reviews by month or day

---

## 💾 Dataset
- Source: Inside Airbnb ([link](http://insideairbnb.com/get-the-data.html))
- File used: `AB_NYC_2019.csv`

---

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🚀 How to Run
Clone the repo and open the notebook:

```bash
git clone https://github.com/Joshcodings/AB_NYC_2019.git
cd AB_NYC_2019
jupyter notebook
