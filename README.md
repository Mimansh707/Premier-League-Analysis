Premier League Analysis (2023–24 vs 2024–25)
Overview

This project analyzes Premier League player and team performance across two seasons — 2023–24 and 2024–25 — using Python and visualization libraries.
It explores goal-scoring patterns, positional contributions, and performance improvements over time using statistical summaries and charts.

The analysis was conducted in Google Colab and organized with a structured folder system for data, figures, and scripts.

📂 Repository Structure
Premier-League-Analysis/
│
├── Premier_League.ipynb               # Main Jupyter Notebook with code and visualizations
│
├── premier-league-analysis/
│   ├── data/                          # Datasets used in analysis
│   │   ├── premier-player-23-24.csv
│   │   └── epl_player_stats_24_25.csv
│   │
│   └── figs/                          # All generated visualizations
│       ├── correlation_heatmap_2023_24.png
│       ├── goals_per90_by_position_2023_24.png
│       ├── goals_per90_by_position_2425.png
│       ├── position_goal_share_comparison.png
│       ├── top10_goals_2023_24.png
│       ├── top10_goals_2425.png
│       ├── top10_assists_2023_24.png
│       └── top10_assists_2425.png
│
└── notebooks/                         # (Optional future scripts)

Technologies Used
- Language: Python
- Environment: Google Colab
- Libraries: pandas, matplotlib, seaborn, numpy, os
- Visualization Type: Bar plots, box plots, correlation heatmaps, and comparative charts

Key Analyses
- Top 10 goal scorers
- Top 10 assist providers
- Player-wise goal improvement comparison
- Positional contribution to goals (forwards, midfielders, defenders, goalkeepers)
- Correlation between goals, assists, and shots on target

Run the Notebook
- You can open and run the full notebook directly in Google Colab:

Datasets
The datasets used for this project are included in the repository:
- premier-player-23-24.csv
- epl_player_stats_24_25.csv

Assists per 90 minutes

Primary position
