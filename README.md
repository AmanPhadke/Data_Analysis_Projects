# 📊 Google Play Store Analytics Dashboard

Interactive data analysis dashboard exploring 10,000+ apps from the Google Play Store with live visualizations and machine learning insights.

🔗 **[Live Dashboard](https://amanphadke.github.io/Data_Analysis_Projects/)**

---

## 🎯 Features

- **16 Interactive Visualizations** - Explore app trends, ratings, and revenue
- **6 Live Charts** - Time-sensitive graphs that activate at specific hours (IST)
- **Insights** - Detialed Insights for each analysis
- **Responsive Design** - Works on desktop, tablet, and mobile

---

## 🛠️ Tech Stack

**Analysis**: Python, Pandas, NumPy
**Visualization**: Plotly (Express & GO)  
**ML/NLP**: Scikit-learn, NLTK VADER  
**Frontend**: HTML5, CSS3, JavaScript  
**Deployment**: GitHub Pages  

---

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/AmanPhadke/Data_Analysis_Projects.git
cd Data_Analysis_Projects

# Install dependencies
pip install pandas numpy plotly scikit-learn nltk

# Download NLTK data
python -c "import nltk; nltk.download('vader_lexicon')"

# Run notebook
jupyter notebook Data_Analysis_Project.ipynb
```

---

## 📈 Key Insights

- **Family & Lifestyle** apps generate the highest revenue
- **Games** dominate installations despite larger sizes
- **More than 90%** of the apps are free
- Strong correlation between sentiment scores and ratings

---

## ⚡ Live Chart System

The dashboard features time-based interactive charts:
- **Top 10 Categories: Rating vs Reviews** - Live 3-5 PM IST
- **Global Installs - Top 5 Categories** - Live 6-8 PM IST
- **Average Installs and Total Revenue Comparison - Free vs Paid Apps** - Live 1-2 PM IST
- **Total Installs Trend with more than 20% Growth Highlighted** - Live 6-9 PM IST
- **App Size vs Average Rating per number of Installs** - Live 5-7 PM IST
- **Total Installs over time by Category** - Live 4-6 PM IST

Charts automatically activate/deactivate based on current IST time with real-time badge updates(live/not live)

---

## 📁 Project Structure

```
├── Data_Analysis_Project.ipynb
├── index.html
├── README.md
└── *.html (visualization files)
```

---

## 🎨 Visualizations Include

✅ Category distribution & rankings  
✅ Revenue analysis by category  
✅ Install patterns and trends  
✅ App size vs. rating correlation  
✅ Sentiment analysis results  
✅ Time series with growth highlights  
✅ Geographic distribution maps  
✅ Paid vs. Free comparisons  

---

## 🔧 Customization

**Change live chart times:**
```python
register_live_plot(
    'filename.html',
    'Title',
    15, 17  # Start and end hours (24hr format)
)
```

**Modify styling:** Edit Cell 108 in the notebook (dashboard_html template)

---

## 📊 Data Source

Dataset: Google Play Store apps + user reviews  
apps data file - [https://www.kaggle.com/code/bansodesandeep/eda-google-play-store-apps/input](https://www.kaggle.com/code/bansodesandeep/eda-google-play-store-apps/input?select=googleplaystore.csv)
user_reviews file - [https://www.kaggle.com/code/bansodesandeep/eda-google-play-store-apps/input?select=googleplaystore_user_reviews.csv](https://www.kaggle.com/code/bansodesandeep/eda-google-play-store-apps/input?select=googleplaystore_user_reviews.csv)

---

## 🌐 Deployment

Hosted on GitHub with automatic updates on push to main branch.

---

## 📧 Contact

**Aman Phadke**  
GitHub: [@AmanPhadke](https://github.com/AmanPhadke)

---

## 📄 License

MIT License - feel free to use and modify!

---

<div align="center">

**⭐ Star this repo if you found it useful!**

Made with ❤️ and Python by Aman

</div>
