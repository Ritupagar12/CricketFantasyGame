# 🏏 Cricket Fantasy Game
![Python](https://img.shields.io/badge/Python-3.6%2B-blue)  
![PyQt5](https://img.shields.io/badge/PyQt5-GUI-green)  
![SQLite](https://img.shields.io/badge/Databse-SQLite-yellow)  

A Python-based Fantasy Cricket game with an interactive GUI, allowing users to create and manage fantasy cricket teams and calculate points based on real match performance.

## 📝 Features
- Create a fantasy cricket team with Batsmen, Bowlers, All-Rounders, and Wicketkeepers.
- Points system based on runs, boundaries, wickets, strike rate, economy, and fielding.
- Save and load teams using SQLite database.
- Evaluate team scores for different matches.
- Interactive GUI built using PyQt5.
- Error handling for invalid selections and exhausted points.

## 🚀 Installation
1. Clone the repository:
```bash
git clone https://github.com/Ritupagar12/CricketFantasyGame.git
```
2. Install dependencies:
```bash
   pip install PyQt5
```
3. Run the application:
```bash
python dream.py
```
## ◻️ Database
- fantasy.db contains the following tables:
  - stats → Player stats for matches
  - teams → Saved fantasy teams
  - Match1, Match2, … → Match-specific performance data
- To customize, modify player stats or add new matches in the database.
  
