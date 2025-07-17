# Anime-rating
Dataset
•	anime.csv: Contains metadata for various anime, including:
o	MAL_ID, Name, Score, Genres, Type, Episodes, Aired date, English/Japanese name, and detailed user score breakdowns.
•	rating.csv.xlsx: Contains user ratings for anime:
o	user_id, anime_id, rating (-1 means "not rated").
Main Steps
1.	Data Import
Downloads the dataset using kagglehub and loads CSV/Excel files into pandas DataFrames.
2.	Data Exploration
o	Displays the first few rows of the anime and rating datasets.
o	Shows dataset shape and column information.
3.	Visualization Utilities
o	Functions for:
	Plotting per-column distributions.
	Plotting correlation matrices.
	Plotting scatter/density matrices.
4.	Sample Analysis
o	Reads and previews a subset of the anime data.
o	Prepares for further visualization and analysis.
Requirements
•	Python 3.x
•	Jupyter Notebook (or Google Colab)
•	Required libraries:
pandas, numpy, matplotlib, scikit-learn, kagglehub, openpyxl (for Excel reading)
