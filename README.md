# IPL Data Analysis & Visualization 🏏

This project presents an exploratory data analysis (EDA) of the Indian Premier League (IPL) using Python, Pandas, and Matplotlib. The goal is to derive meaningful insights from historical IPL match data, understand team performance patterns, and visualize trends across various match situations.

## 📁 Dataset
The analysis is based on two CSV files:
- `matches.csv`: Contains match-level information (e.g., teams, winner, toss decision, venue, etc.)
- `deliveries.csv`: Contains ball-by-ball details (e.g., batsman, bowler, runs, dismissals)

## 📊 Key Analyses Performed

- **Overall match statistics**: Total matches, unique seasons, and participating teams
- **Team performance**: Most successful teams when batting first vs second
- **Toss impact**: Correlation between toss win and match win
- **Run margin analysis**: Histogram showing how often teams win by specific run margins
- **Wicket margin analysis**: Distribution of wins based on wickets (batting second)
- **Dismissal types**: Visualized breakdown of how players were dismissed (e.g., bowled, caught, run out)
- **Pie charts**: Share of wins by each team in different match scenarios

## 📌 Tools & Libraries
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 🔍 Insights
This project helps identify:
- Strategic advantages of batting first vs second
- Frequency of close matches (small margin wins)
- Common methods of player dismissals
- Team-wise win distributions

## 📎 How to Use
Clone this repository and open the notebook using Jupyter or VS Code:
```bash
git clone https://github.com/your-username/ipl-data-analysis-eda-visualization.git
cd ipl-data-analysis-eda-visualization
jupyter notebook IPL.ipynb
