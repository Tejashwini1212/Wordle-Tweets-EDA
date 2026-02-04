An Exploration of Wordle Tweets

This project performs an Exploratory Data Analysis (EDA) on Twitter data related to the daily word game Wordle. Using Python and data visualization libraries, we analyze how players share their Wordle results and identify patterns in guesses, attempts, and emoji usage.



-> Overview
- Parse Wordle emoji grids (🟩🟨⬛) from tweets  
- Analyze number of attempts per Wordle puzzle  
- Study difficulty trends across Wordle IDs  
- Visualize guess accuracy and player behavior  



-> Dataset
- Source: Wordle Tweets (Kaggle)
- Format: CSV
- Contains tweet text, dates, Wordle IDs, number of attempts, and emoji-based guesses  
- Note: Actual Wordle answers are not included



->Tools Used
Python, pandas, numpy, matplotlib, seaborn, regex



->Analysis Highlights
- Daily Wordle tweet volume  
- Distribution of attempts (2–6)  
- Attempts vs Wordle ID difficulty  
- Average correct, misplaced, and incorrect letters per guess

📊 Visualizations Included

- Wordle Tweets by Day
- Attempts by Wordle ID
- Distribution of Number of Attempts
- Average Guess Accuracy by Guess Number

->How to Run
```bash
pip install pandas numpy matplotlib seaborn
