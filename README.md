# Movie Genre Analysis with Python

## Overview

This project is a simple machine learning exercise focused on analyzing movies across various genres, such as **Comedy**, **Sci-Fi**, **Animation**, and **Romance**. The primary goal is to explore genre-specific trends, visualize data distributions, and gain insights into different movie genres using basic data analysis techniques.

The project is written in Python, leveraging popular data science libraries such as `pandas`, `numpy`, and `matplotlib`.

## Features

- **Genre Analysis**: Gain insights into key metrics across multiple movie genres.
- **Data Visualization**: Use charts and plots to visualize trends and distributions.
- **Data Cleaning**: Handle missing values and preprocess data to improve analysis accuracy.

## Dataset

The dataset consists of movie information, including genres, release dates, ratings, and other metadata relevant for genre-based analysis. Ensure the dataset file is in the project directory or specify the path in the script.

> **Note**: You can source a dataset from [IMDb](https://www.imdb.com/interfaces/) or other movie databases.


### Libraries Used

- **pandas**: For data manipulation and analysis
- **numpy**: For numerical operations
- **matplotlib**: For data visualization

## Usage

1. Ensure that your dataset (e.g., `movies.csv`) is in the project directory.
2. Run the analysis script:
    ```bash
    python analyze_movies.py
    ```
3. The script will generate visualizations and print summary statistics to help you understand genre-specific movie trends.

## Project Structure

- `film_finder.ipynb`: Main script that contains data loading, processing, analysis, and visualization steps.
- `README.md`: Project documentation.

## Example Outputs

The script generates several CSV files that contain sorted movie information in descending order of rating. Each file includes details such as duration, genre, and title. The output files are:

- `action_final.csv`: Contains top-rated action movies with information on duration, genre, and title.
- `animation_final.csv`: Contains top-rated animation movies with relevant details.
- `comedy_final.csv`: Contains top-rated comedy movies.
- `Romance_Comedy_final.csv`: Contains top-rated romance and comedy movies.
- `Scifi_final.csv`: Contains top-rated science fiction movies.

Each file is generated in the project directory and can be loaded for further analysis or visualization.
## Future Improvements

- Add more genres and metadata for richer analysis.
- Implement a machine learning model to classify movies by genre based on metadata.
- Experiment with other visualization libraries like `seaborn` or `plotly`.

## Contributing

Feel free to submit pull requests if you’d like to improve the project or add new features. Please create an issue for any major changes you wish to propose.

---

Happy analyzing! 📊
