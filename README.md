**🏀 NBA Schedule Analysis (Data Science Project)**
**📖 Project Overview**

This project analyzes NBA schedules to understand how game density, rest days, and travel affect team performance. Using Python (Anaconda, JupyterLab) and official NBA datasets, I recreated a real-world workflow similar to what data scientists inside NBA teams might perform.

**The analysis is based on four datasets:**

schedule.csv – full league schedule (2014–2024)

schedule_24_partial.csv – draft 2024–25 schedule (OKC, DEN only, 80 games each)

locations.csv – NBA team locations (for travel analysis)

team_game_data.csv – team-level game stats (2014–2024)

**🔍 Key Questions Answered**

How many times do the Thunder play 4 games in 6 nights in the 2024–25 draft schedule?

What is the league average number of 4-in-6 stretches per team since 2014?

Which NBA team has had the most vs least 4-in-6 stretches (2014–2024)?

Is the difference likely due to chance or real structural differences?

What was BKN’s defensive eFG% in 2023–24 overall vs when opponents were on a back-to-back?

What scheduling trends have changed over the last decade?

How can we visualize a team’s full season schedule (travel, rest, density)?

What are the best and worst stretches of OKC’s 2024–25 draft schedule?

How many wins each team gained/lost due to schedule factors (2019–2024)?

**📊 Results (Highlights)**

OKC 2024–25 Draft: X 4-in-6 stretches.

League Average: Y 4-in-6 stretches (per 82 games).

Most Burdened (2014–24): TEAM1 (Z.X avg)

Least Burdened (2014–24): TEAM2 (Z.X avg)

BKN 2023–24 Defensive eFG%: A% overall | B% vs B2B opponents

Schedule Winners (2019–24): TEAM3 (+W wins)

Schedule Losers (2019–24): TEAM4 (−W wins)

**📌 Full detailed answers are in the Jupyter Notebook & exported HTML report.**

**🛠 Tech Stack**

Python: pandas, numpy, matplotlib, seaborn, scikit-learn

Environment: Anaconda, JupyterLab

Data Format: CSV → Analysis in Jupyter → Exported to HTML

**📂 Project Structure**

nba-schedule-analysis/
│
├── data/
│   ├── schedule.csv
│   ├── schedule_24_partial.csv
│   ├── locations.csv
│   └── team_game_data.csv
│
├── analysis_notebook.ipynb   # Jupyter Notebook with all code & answers
├── answer_key.html           # Final HTML report with answers
├── README.md                 # Project description (this file)

**🚀 How to Run**

Install Anaconda.

Open Anaconda Navigator → JupyterLab.

Launch the notebook:

jupyter lab


**Open analysis_notebook.ipynb.**

Run all cells to reproduce results.

Export answers to HTML:

jupyter nbconvert --to html analysis_notebook.ipynb

**📖 Lessons Learned**

Scheduling density has decreased over the last decade (fewer back-to-backs).

Even small schedule differences can swing several wins per team.

Travel and rest are measurable, and their impact is often underestimated.

Reproducible workflows (Jupyter + Anaconda) make analysis professional and sharable.

👤 Author

Alexander O. Ayeni

LinkedIn | GitHub
https://www.linkedin.com/in/datawithdata | https://github.com/datawithalexander
