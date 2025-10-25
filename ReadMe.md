# Video Games Sales Analysis

A comprehensive analysis of video game sales data using Python, Pandas, and NumPy to explore gaming market trends, regional preferences, and publisher performance.

## 📊 Dataset Overview

- **Source**: [Video Games Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales)
- **Dataset**: `vgsales.csv`
- **Records**: 16,598 video games
- **Columns**: Rank, Name, Platform, Year, Genre, Publisher, NA_Sales, EU_Sales, JP_Sales, Other_Sales, Global_Sales
- **Sales Units**: Millions of copies sold

## 🎯 Analysis Questions

This project answers 7 key questions about the video game industry:

1. **Top 5 Games by Global Sales** - Which games sold the most and what do they have in common?
2. **Genre Performance** - Which genre generates the most revenue globally?
3. **Platform Analysis** - Which platforms have the highest average sales per game?
4. **Publisher Performance** - Which publisher releases the most games vs. highest total sales?
5. **Regional Preferences (Post-2010)** - Which genre dominated each region in recent years?
6. **Regional Contribution** - What percentage of global sales does each region contribute?
7. **Japanese vs North American Sales** - Games where Japanese sales exceed North American sales

## 🚀 Stretch Goal

**Genre-Region Heatmap**: A normalized heatmap showing genre preferences across regions, revealing cultural gaming preferences.

## 📁 Project Structure

```
week3-vgsales/
├── activity.ipynb          # Main analysis notebook
├── vgsales.csv            # Dataset
└── README.md              # This file
```

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development

## 📈 Key Insights

### Top Performing Games
- Wii Sports leads with 82.74 million copies sold globally
- Nintendo dominates the top 5 with family-friendly games
- Sports and platform games are most successful

### Market Analysis
- **Most Profitable Genre**: Action games generate the highest revenue
- **Regional Preferences**: Different genres dominate in different regions
- **Publisher Strategy**: Quantity vs. quality in game releases

### Regional Distribution
- North America typically contributes the highest percentage of global sales
- Japan shows unique preferences for certain genres
- Europe and other regions have distinct gaming cultures

## 🔍 Analysis Features

- **Statistical Analysis**: Comprehensive sales statistics and trends
- **Data Visualization**: Charts, graphs, and heatmaps
- **Pattern Recognition**: Common characteristics of successful games
- **Regional Analysis**: Cultural preferences in gaming
- **Publisher Performance**: Business intelligence insights

## 📊 Visualizations

- Bar charts for genre and platform performance
- Pie charts for regional sales distribution
- Heatmaps for genre-region preferences
- Statistical summaries and comparisons

## 🎮 Business Applications

This analysis provides valuable insights for:
- **Game Developers**: Understanding market preferences
- **Publishers**: Strategic planning and market entry
- **Investors**: Gaming industry trends and opportunities
- **Researchers**: Academic studies on gaming culture

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/bamsby/Video-Games-Sales-Analysis.git
   cd Video-Games-Sales-Analysis
   ```

2. **Install dependencies**:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Run the analysis**:
   ```bash
   jupyter notebook activity.ipynb
   ```

## 📋 Requirements

- Python 3.7+
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements or additional analysis.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

For questions or suggestions, please open an issue in this repository.

---

**Note**: This analysis is based on historical video game sales data and provides insights into gaming market trends and regional preferences.
```

## How to Create the README File

Since you're in ask mode, you'll need to create this file manually. Here are the steps:

1. **Create a new file** called `README.md` in your project directory
2. **Copy the entire markdown content** above into the file
3. **Save the file**

Then you can add it to git:

```bash
git add README.md
git commit -m "Add comprehensive README.md"
git push origin master
```