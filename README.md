League of Legends Data Analysis

This project contains a comprehensive analysis of League of Legends match data from Kaggle.

Dataset Information

Source: https://www.kaggle.com/datasets/prestonrobertson7/league-of-legends-data-9292022
Dataset Name: League Of Legends Data (9292022)
Files Included:
    - Sep-09-2022_10000matches.csv (10,000 matches)
    - Sep-29-2022_500matches.csv (500 matches)
    - Legends.ipynb (Jupyter notebook with analysis)

Project Overview

This Jupyter notebook provides an in-depth analysis of League of Legends match data, including:
    - Game mode distribution
    - Champion performance statistics
    - Position analysis
    - Performance metrics (KDA, damage, gold, etc.)
    - Win rate analysis
    - Correlation analysis
    - Game duration patterns
    - Surrender statistics
    - Damage type breakdowns


Project Structure

The notebook is organized into the following sections:

1. Load the Data
   Loads and combines both CSV files into a single dataframe

2. Data Overview and Information
   Provides basic statistics, column information, and data types

3. Game Mode Analysis
   Analyzes the distribution of different game modes (ARAM, CLASSIC, etc.)

4. Champion Analysis
   - Most played champions
   - Champion win rates
   - Performance statistics by champion

5. Position Analysis
   - Position distribution (TOP, JUNGLE, MIDDLE, BOTTOM, UTILITY)
   - Win rates by position
   - Performance metrics by position

6. Performance Metrics Analysis
   - Distribution of key metrics (kills, deaths, assists, gold, damage, etc.)
   - KDA calculation
   - Win vs Loss performance comparison

7. Correlation Analysis
   - Features most correlated with winning
   - Correlation heatmaps for key metrics

8. Game Duration Analysis
   - Average game duration
   - Duration by game mode
   - Duration distribution

9. Surrender Analysis
   - Surrender statistics
   - Game duration comparison for surrendered vs non-surrendered games

10. Advanced Analysis: Damage Types
    - Physical damage analysis
    - Magic damage analysis
    - True damage analysis
    - Damage type distributions

11. Summary and Insights
    - Comprehensive summary report
    - Key findings and statistics

Key Features

The analysis includes:
    - Data visualization with matplotlib and seaborn
    - Statistical summaries
    - Performance metric calculations
    - Win rate analysis
    - Correlation analysis
    - Comprehensive reporting

Data Columns

The dataset includes 69 columns covering:
    - Match information (GameID, GameMode, win)
    - Champion data (championName, champLevel, champExperience)
    - Performance metrics (kills, deaths, assists, KDA)
    - Economic data (goldEarned, goldSpent)
    - Damage statistics (physical, magic, true damage)
    - Position and lane information
    - Vision and objective control
    - Item builds
    - Spell usage
    - And many more detailed statistics

Usage Notes

- The notebook combines both CSV files automatically
- All visualizations are generated inline
- The analysis filters champions with at least 50 games for win rate statistics
- KDA is calculated as (kills + assists) / deaths, with special handling for perfect games (0 deaths)
- Game duration is converted from seconds to minutes for readability

Output

The notebook generates:
    - Statistical summaries
    - Data visualizations (bar charts, histograms, heatmaps, box plots)
    - Performance comparisons
    - Correlation matrices
    - Summary reports

Dataset created by prestonrobertson7 on Kaggle
Analysis notebook created for educational and analytical purposes

