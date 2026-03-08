NFL Franchise Stability: Head Coach and Quarterback Tenure vs Team Success (2016–2025)
Business question
Does longer head coach tenure and starting quarterback tenure correlate with more wins in the NFL?
Stakeholders
•	NFL front offices
•	football operations analysts
•	sports media / fans
•	fantasy / betting analysts
Data sources
•	wins.csv from your NFL coaches repo
•	nflreadr::load_player_stats()
Process
•	imported coach/team win data
•	imported QB weekly player stats
•	aggregated QB pass attempts by season/team
•	identified primary QB per team-season
•	calculated coach tenure
•	calculated QB tenure
•	built a franchise stability index
•	tested relationship with wins
Tools Used
•	R
•	tidyverse
•	nflreadr
•	ggplot2
Key Insights
Example findings may include:
•	Teams with longer coach tenure tend to show more consistent win totals
•	Quarterback continuity may contribute to offensive stability
•	Teams with both long-tenured coaches and quarterbacks often appear among the league's most successful franchises
Examples of historically stable teams include:
•	Kansas City Chiefs
•	Pittsburgh Steelers
•	Baltimore Ravens

Conclusion
This project demonstrates how organizational stability in leadership roles may influence NFL team success.
By combining coaching tenure and quarterback tenure into a single stability index, the analysis highlights the potential importance of continuity in high-impact leadership positions.
________________________________________
Author
Darrell Banks
Data Analytics Portfolio Project

