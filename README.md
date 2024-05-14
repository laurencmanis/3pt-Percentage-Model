# NBA Three-Point Percentage Prediction Model
Predicting NBA players' three-point percentages at the end of the 2022-23 season given their shooting statistics from October/November 2022.

This project was completed as a part of the NBA Future Analytics Stars Program's interview process.
The goal was to predict each player’s three-point percentage at the end of the 2022-23 season given their shooting statistics from October/November 2022. 
In order to so, applicants were provided with a CSV dataset, containing 12 features (various shooting statistics), and a target variable, three_pct_season, which I am unable to share.  

## Notes & Assumptions:
1. Only using data from the csv file provided (subset of 108 players)
2. Dataset excludes some shot locations and does not perfectly match 2022-23 official NBA stats

## Data Dictionary
- Name - player’s name
- three_pct_season – the player’s three-point percentage over the course of the full season (not
- including shots from the backcourt)
- lwr_paint_pct_oct_nov - the player's field goal% from shot attempts within 8 feet of the basket in october and november
- upr_paint_pct_oct_nov - the player's field goal% from shot attempts between 8 to 16 feet of the basket in october and november
- mid_pct_oct_nov - the player's field goal% from shot attempts greater than 16 feet from the basket that are not three point attempts in october and november
- three_non_cnr_pct_oct_nov - the player's field goal% from non-corner shot attempts from three point range in october and november
- three_cnr_pct_oct_nov - the player's field goal% from corner shot attempts from three-point range in october and november
- ft_pct_oct_nov - the player's free throw% in october and november
- lwr_paint_shots_oct_nov - the player's total shot attempts from shot attempts within 8 feet of the basket in october and november
- upr_paint_shots_oct_nov - the player's total shot attempts from shot attempts between 8 to 16 feet from the basket in october and november
- mid_shots_oct_nov - the player's total shot attempts from shot attempts greater than 16 feet from the basket that are not three-point attempts in october and november
- three_non_cnr_shots_oct_nov - the player's total shot attempts from non-corner shot attempts from three point range in october and november
- three_cnr_shots_oct_nov - the player's total shot attempts from corner shot attempts from three point range in october and november
- ft_shots_oct_nov - the player's free throw attempts in october and november
