# NFL-Big-Data-Bowl-2023

Welcome to my repository for the 2023 NFL Big Data Bowl competition, where I participated in generating novel and actionable stats using the Next Gen Stats player tracking data. This year's competition theme focused on the hardest workers in football: linemen on pass plays. The offensive line plays a crucial role in protecting the passer, while the defensive line tries to disrupt their path. The competition challenged us to examine the data behind these important plays and create new metrics and stats using the NFL's Next Gen Stats data and Pro Football Focus (PFF) scouting data.

Throughout this repository, I will showcase my approach and methodology to the competition, including how I used data visualization, innovation, accuracy, relevance, and clarity to come up with new metrics and analysis for the NFL teams to evaluate their offensive and defensive lines. I'm excited to share my work and hopefully contribute to the advancement of football analytics.

# Method
In my method, I would summarize every combination of offensive personnel and defensive personnel and count their times. For each combination, I would also add the index to reflect if the QB gets pressure in the play. Then I can build a league average on each personnel combination with QB getting pressure or not. The league average can be used to compare different teams' OL and DL to see if their performance is above average or not and provide insight into the linemen's performance. Finally, the tracking data for the play can show the status on the ground and provide more interesting points for the lineman's performance. I list my workflow in the following:

1. Create the pressure index in the scouting data (1 means QB gets at least one hit, hurry, or sack in the play, 0 means none)
2. Put the pressure index into plays data and create the personnel combination table with the pressure index
3. Calculate the percentage of each combination as the league average
4. Select any individual team and process the same calculation
5. Compare team's result with the league average
6. The difference is the metric I use to evaluate linemen performance
7. Use tracking data to get more ideas about teams' good and awful personnel

# Features of this method
- Quantify the performance of the linemen
- Suitable for both offensive and defensive line
- Eliminate other factors but focus on linemen
- Team-based and work on each team
- Understand more details about the performance with tracking data
