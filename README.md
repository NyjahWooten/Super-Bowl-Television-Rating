This dataset contains historical data on Super Bowl broadcasts from 1967 to recent years, with a focus on understanding and predicting television viewership. The dataset includes both numerical and categorical features related to game characteristics, entertainment elements, and audience metrics.

column features 
super_bowl_number – Order of the Super Bowl (I, II, III, etc.)

average_us_viewers – Number of average U.S. viewers in millions (target variable for prediction)

super_bowl_host_city – City where the Super Bowl was held

network – TV network broadcasting the game

total_us_viewers – Total U.S. viewers (may include streaming or all platforms)

total_ads – Number of commercials shown during the broadcast

super_bowl_winner / super_bowl_loser – Teams playing and the game outcome

halftime_show_performer – Headlining performer(s) during halftime

Purpose of Dataset
To analyze which factors most influence Super Bowl viewership, and to use these insights to predict future audience sizes.

Data Preprocessing Steps Taken
Removed unnecessary characters and whitespace

Converted string-based numerical values to floats (e.g., "114.4M" → 114.4)

Handled null values (e.g., missing halftime performers)

Applied feature scaling for machine learning models

Performed train-test split for model evaluation

Use Case
This dataset supports modeling efforts to forecast how many people will watch a future Super Bowl, which is valuable for:

TV networks and advertisers

Marketing strategy planning

Event management and entertainment programming
