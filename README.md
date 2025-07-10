🎬 Netflix Original Films & IMDb Scores - EDA
This project provides an in-depth Exploratory Data Analysis (EDA) of Netflix Original Films and their corresponding IMDb scores. The analysis aims to uncover trends, popular genres, language distributions, and the relationship between runtime and IMDb ratings for Netflix's original content.

🌟 Project Overview
This project focuses on analyzing a dataset of Netflix original films, documentaries, and specials released as of June 1st, 2021. The primary goals include:

Understanding Content Landscape: Examining the distribution of films by genre, language, and release year.

Performance Analysis: Investigating the relationship between film attributes (runtime, genre, language) and IMDb scores.

Visualization: Creating insightful visualizations to present key findings.

📊 Dataset
The dataset was web-scraped from a Wikipedia page and integrated with IMDb scores. It is available on Kaggle.

The dataset consists of the following attributes:

Title: The name of the Netflix original film.

Genre: The genre classification of the film.

Premiere: The release date of the film.

Runtime: The duration of the film in minutes.

IMDB Score: The IMDb rating of the film, based on community reviews.

Language: The primary language(s) in which the film was created.

🚀 Analysis Questions
This Colab notebook addresses a variety of analytical questions, including:

Language of Long-Running Films: Identifying the languages of films with longer runtimes and visualizing the distribution.

Documentary IMDb Scores (2019-2020): Analyzing and visualizing IMDb scores for documentaries released between January 2019 and June 2020.

Highest IMDb Rated English Genre: Determining which genre has the highest IMDb rating among movies shot in English.

Average Runtime of Hindi Movies: Calculating the average runtime for movies produced in Hindi.

Genre Category Analysis: Counting and visualizing the different categories within the 'Genre' column.

Most Used Languages: Identifying the top 3 most frequently used languages in the dataset.

Top 10 Movies by IMDb Rating: Listing the top 10 movies based on their IMDb scores.

Runtime vs. IMDb Score Correlation: Examining and visualizing the correlation between IMDb score and film runtime.

Top 10 Genres by IMDb Score: Identifying the top 10 genres based on their average IMDb scores.

Top 10 Movies by Runtime: Visualizing the top 10 movies with the highest runtimes.

Most Movies Released Year: Identifying and visualizing the year with the highest number of movie releases.

Lowest Average IMDb Rating Language: Visualizing which language movies have the lowest average IMDb rating.

Greatest Total Runtime Year: Determining the year with the greatest total runtime across all films.

Most Used Genre per Language: Identifying the most prevalent genre for each language.

Outlier Data Detection: Analyzing the dataset for any outlier data and providing explanations.

🛠️ Technologies & Libraries
Python: The primary programming language for data analysis.

Jupyter Notebook / Google Colab: For interactive development, code execution, and documentation.

Pandas: Essential for data loading, manipulation, and analysis.

Matplotlib: For creating static, high-quality visualizations.

Seaborn: For statistical data visualization, building on Matplotlib.

Plotly Express: For creating interactive and visually appealing plots.

💡 How to Run
To explore this analysis:

Access the Notebook: Open the Netflix_Originals.ipynb notebook in Google Colab or a local Jupyter environment.

Load Data: Ensure the NetflixOriginals.csv dataset is accessible. If running locally, place it in the same directory as the notebook or update the file path in the code.

Run Cells: Execute the cells sequentially to perform the EDA, generate visualizations, and see the answers to the analysis questions.
