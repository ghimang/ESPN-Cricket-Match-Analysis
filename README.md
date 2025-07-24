# ESPN-Cricket-Match-Analysis

This Power BI dashboard presents a comprehensive analysis of individual player statistics across Batting, Bowling, and Fielding using data inspired by ESPN match scorecards. The purpose of this project is to visualize and interpret cricketing performance in a clean and interactive layout.

## 📌 Objective
To design a dynamic and intuitive Power BI dashboard that:

Highlights player-wise performance metrics

Segregates data by skill type: Batting, Bowling, and Fielding

Enables selection of specific players to analyze their historical data

Creates a visual story using ESPN-style statcards and performance summaries

### 📂 Dataset Overview
The project uses structured data grouped into the following Power BI tables:

Table Name	Description
Batting	Contains all batting metrics (e.g., runs, strike rate, 4s, 6s, innings)
Bowling	Bowling performance stats like wickets, economy, overs, and averages
Fielding	Fielding records including catches, stumpings, and dismissals
Strike Rate Table	Supporting table used for custom strike rate classifications or ranges

Each table contains player-specific data over a span of multiple years (e.g., 1992–2006).

📊 Dashboard Views
🔹 Batting Data Analysis

Key KPIs: Runs, Matches, Innings, Strike Rate, Highest Score, 4s, 6s, Centuries

Includes: Not Outs, Ducks (Zeros), and Batting Average

Player dropdown to switch views across different players

🔹 Bowling Data Analysis

KPIs: Wickets, Strike Rate, Runs Conceded, Overs, Economy, Bowling Average

Best Bowling Innings displayed (e.g., 2/47)

Includes: Maiden Overs, 4-wicket hauls, 5-wicket hauls

🔹 Fielding Data Analysis

Focused on dismissals, catches (as keeper or fielder), and match days

Dismissals per innings calculated

Provides player fielding span and total matches played

🛠️ Tools Used
Power BI Desktop

Power Query for data transformation

DAX for calculated measures and KPIs

Buttons and bookmarks for sheet navigation

Custom card visuals for stat presentation

🎯 Features
🧍 Player-wise selection using slicers

⚡ Fast visual feedback using pre-aggregated KPIs

🧮 Statistical calculations like averages, strike rates, and conversion ratios

✨ Aesthetic layout with stylized visuals resembling ESPN and Cricinfo cards

🚀 How to Use
Clone the repo or download the .pbix file.

Open in Power BI Desktop.

Select a player from the slicer to view their stats.

Navigate between tabs: Batting, Bowling, Fielding for insights.

📈 Future Enhancements
Add match-wise drill-down (year-wise performance trends)

Integrate live data scraping via ESPN/Cricbuzz APIs

Include comparison between two players side by side

Build a player ranking engine using weighted metrics

🧑‍💻 Author
Himangsha Goyari
Data Analytics | Power BI Developer | Sports Analytics Enthusiast
