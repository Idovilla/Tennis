
# Tennis Match Analysis Project

## Overview
This project aims to analyze tennis matches to predict which factors are most important for winning a game. The analysis utilizes a comprehensive dataset that includes detailed attributes from various tournaments.

## Project Goal
The primary objective is to identify key predictors that contribute significantly to a player's success in a match. By understanding these factors, strategies can be optimized for player performance and match outcomes.



## Dataset Description
The dataset, stored in `all_matches_final.csv`, comprises a wide range of data points, including:

- **tourney_id**: A unique identifier for each tournament. Format: YYYY-XXX, where YYYY is the year.
- **tourney_name**: The name of the tournament.
- **surface**: The playing surface (e.g., Hard, Clay, Grass).
- **draw_size**: The number of players in the draw, often rounded to the nearest power of 2.
- **tourney_level**: Indicates the category of the tournament (e.g., 'G' for Grand Slams, 'M' for Masters 1000s).
- **tourney_date**: Date of the tournament in YYYYMMDD format.
- **match_num**: A unique identifier for each match.
- **winner_id**, **loser_id**: Unique identifiers for the winner and loser of the match.
- **winner_seed**, **loser_seed**: Seeding of the players.
- **winner_entry**, **loser_entry**: How the player entered the tournament (e.g., 'WC' for wild card).
- **winner_name**, **loser_name**: Names of the players.
- **winner_hand**, **loser_hand**: Dominant hand of the players ('R' for right, 'L' for left, 'U' for unknown).
- **winner_ht**, **loser_ht**: Height of the players in centimeters.
- **winner_ioc**, **loser_ioc**: Three-character country codes.
- **winner_age**, **loser_age**: Age of the players at the time of the tournament.
- **score**: Match score.
- **best_of**: Maximum number of sets in the match (3 or 5).
- **round**: Stage of the tournament.
- **minutes**: Duration of the match.
- **w_ace**, **l_ace**: Number of aces by the winner and loser.
- **w_df**, **l_df**: Number of double faults by the winner and loser.
- **w_svpt**, **l_svpt**: Total serve points played by winner and loser.
- **w_1stIn**, **l_1stIn**: First serves in by winner and loser.
- **w_1stWon**, **l_1stWon**: First serve points won by winner and loser.
- **w_2ndWon**, **l_2ndWon**: Second serve points won by winner and loser.
- **w_SvGms**, **l_SvGms**: Serve games played by winner and loser.
- **w_bpSaved**, **l_bpSaved**: Break points saved by winner and loser.
- **w_bpFaced**, **l_bpFaced**: Break points faced by winner and loser.
- **winner_rank**, **loser_rank**: ATP or WTA rank of the players.
- **winner_rank_points**, **loser_rank_points**: Ranking points of the players.

## Code Description
The Jupyter notebook `Tennis_code.ipynb` includes:
- Data preprocessing to clean and organize the dataset.
- Exploratory data analysis to understand trends.
- Predictive modeling to determine the outcome influences.
- Application of SHAP (SHapley Additive exPlanations) to identify the most important features influencing match outcomes.

## How to Run the Code
1. Install Jupyter notebook or use JupyterLab.
2. Open `Tennis_code.ipynb`.
3. Execute the cells sequentially to reproduce the analysis and results.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, shap

## License
This project is licensed under the MIT License - see the LICENSE file for details.



