NFL Franchise Stability
Head Coach and Quarterback Tenure vs Team Success (2016–2025)
Business Question

Does longer head coach tenure and starting quarterback tenure correlate with more wins in the NFL?

Stakeholders

NFL front offices

Football operations analysts

Sports media and fans

Fantasy football and betting analysts

Data Sources

wins.csv from the NFL Coaches dataset repository

nflreadr::load_player_stats() NFL player statistics

Process

The analysis followed these steps:

Imported coach and team win data

Imported quarterback weekly player statistics

Aggregated QB pass attempts by season and team

Identified the primary starting quarterback for each team-season

Calculated head coach tenure with each franchise

Calculated quarterback tenure with each franchise

Created a Franchise Stability Index

Tested the relationship between stability and team wins

Tools Used

R

tidyverse

nflreadr

ggplot2

Key Insights

Example findings include:

Teams with longer head coach tenure tend to show more consistent win totals

Quarterback continuity may contribute to offensive stability

Teams with both long-tenured coaches and quarterbacks often appear among the league's most successful franchises

Examples of historically stable teams include:

Kansas City Chiefs

Pittsburgh Steelers

Baltimore Ravens

Conclusion

This project demonstrates how organizational stability in leadership roles may influence NFL team success.

By combining coaching tenure and quarterback tenure into a single Stability Index, the analysis highlights the potential importance of continuity in high-impact leadership positions.

Author

Darrell Banks
Data Analytics Portfolio Project

# Franchise Stability vs Performance

This quadrant chart compares team success with franchise stability.

Teams in the **top-right quadrant** demonstrate both strong leadership continuity and strong performance.

![NFL Stability Quadrant](outputs/nfl_stability_quadrant.png)

# Franchise Stability Over Time

This heatmap shows how franchise stability changed across NFL teams from 2016 to 2025.  
Darker or more intense values indicate higher combined continuity between head coach tenure and primary quarterback tenure.

![NFL Stability Heatmap](outputs/nfl_stability_heatmap.png)
