# Hit Prediction Model for Spotify Tracks

## Project Overview

This project aims to develop a machine learning model capable of predicting whether a song will be a hit. The prediction model utilizes a range of metrics from various sources, including Spotify Popularity Scores, Music Top Charts data, and YouTube view performance. The objective is to analyze tracks from top artists (who have historically produced hit tracks) as well as newer, lesser-known releases that might become hits.

## Data Sets

### X DataSet

The X DataSet comprises tracks from top artists provided by ChartMetrics. This dataset includes tracks that have achieved hit status and others that have not, providing a robust basis for training our predictive model.

**Run File:**
Final - Alisha - Nico - Consolidate And CleanUp Data For ML.ipynb

### Y DataSet

The Y DataSet includes new releases sourced from ChartMetrics that were less known at the time of discovery. This dataset consists of new artists and obscure artists, making it ideal for testing the model's ability to predict potential hits.

**Run File:**
Final - Alisha - Danny Group 9 - New Releases To Predict If It Is Hit From Spotify.ipynb

### Data Consolidation and Standardization

After thorough data analysis, we standardized the dataset to include fields that consistently provided reliable indicators of a song's potential to be a hit. These fields were selected based on their reliability across all tracks and their contribution to the model's accuracy.

**Fields used:**
- `cm_track_id`
- `isrc`
- `name`
- `IsHit`
- `cm_artist`
- `artist_names`
- `spotify_popularity`
- `score`
- `track_genre`
- `image_url`
- `artist_images`
- `spotify_artist_ids`
- `explicit`
- `region_codes`

**Run File:**
Final - Alisha - ML Model Train And Optimization.ipynb

## Model Performance

The machine learning model demonstrated robust performance with the following metrics:
- **Precision:** 0.9397715472481828
- **Recall:** 0.8792098445595855
- **F1 Score:** 0.9084825163125314
- **Accuracy:** 0.8989283074648928

These results indicate a high level of accuracy in predicting hits, reinforcing the effectiveness of the chosen features and model architecture.

## Conclusion

The predictions from our model are saved in 'Final_PredictedNewHits.csv', providing insights into which new tracks might become future hits. This project not only highlights the potential of machine learning in the music industry but also offers a valuable tool for artists, producers, and labels to forecast track success.

**Visualiatzations**

![image](https://github.com/Project2andTeam9/Team_9/assets/154397635/0b513399-c450-4218-98ec-d1b8c914b57b)

![image (1)](https://github.com/Project2andTeam9/Team_9/assets/154397635/7ef3d716-748d-4dce-a76a-a9bace2babd3)

![image (2)](https://github.com/Project2andTeam9/Team_9/assets/154397635/153c0a0f-2aae-4bcb-9c54-b955afbe0047)

![image (3)](https://github.com/Project2andTeam9/Team_9/assets/154397635/4c93fa92-1537-4ea9-b741-f525c1cde4cb)

![image (4)](https://github.com/Project2andTeam9/Team_9/assets/154397635/11f00ab7-6969-4f3e-81b0-453283da31f0)

![image (5)](https://github.com/Project2andTeam9/Team_9/assets/154397635/c3f8d3e5-4d2c-4804-92ea-560df132dbc4)

![image (6)](https://github.com/Project2andTeam9/Team_9/assets/154397635/7166ab9d-8417-4a1d-a455-c9fc538d4eb6)

![NumberOfBigHitsandLowHits](https://github.com/Project2andTeam9/Team_9/assets/154397635/7e17fe2f-e1e7-4b36-a6dd-374b6a1fddcc)

![TrackAppearanceFrequencies](https://github.com/Project2andTeam9/Team_9/assets/154397635/b19d93ab-bdbf-4b95-9b52-1d09352cbd15)

