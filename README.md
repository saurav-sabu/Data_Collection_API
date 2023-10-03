# TMDB Top Rated Movies Data Collection using API - Jupyter Notebook

This Jupyter Notebook allows you to collect data on the top-rated movies from The Movie Database (TMDB) using TMDB's API. You can fetch information about the highest-rated movies, such as their titles, ratings, and release years. Use this notebook for data analysis, research, or any other purposes related to TMDB's top-rated movies.

## Requirements

Before you begin, ensure you have the following prerequisites:

- **Jupyter Notebook**: You should have Jupyter Notebook installed on your local machine or a cloud-based environment.

- **TMDB API Key**: To access TMDB's API, you'll need an API key. Obtain one by registering on the [TMDB API website](https://www.themoviedb.org/documentation/api). Keep your API key handy, as you'll use it in this notebook.

- **Python Libraries**: Install the necessary Python libraries for making HTTP requests and working with JSON data. You can use libraries like `requests` for making API calls and `pandas` for data manipulation. Install them using:

    ```shell
    !pip install requests pandas
    ```

## Getting Started

Follow these steps to collect data on the top-rated TMDB movies using this Jupyter Notebook:

1. **Clone or Download the Notebook**: Clone this GitHub repository or download the Jupyter Notebook (`tmdb_top_rated_movies.ipynb`) to your local machine.

2. **Open the Notebook**: Launch Jupyter Notebook and open the `tmdb_top_rated_movies.ipynb` file.

3. **Enter Your API Key**: Replace `'YOUR_API_KEY'` in the notebook with your actual TMDB API key.

4. **Run the Notebook**: Execute the notebook cell by cell by clicking on each cell and pressing Shift+Enter. The notebook will guide you through the process of making API requests, processing the data, and displaying the results.

5. **Explore the Data**: Once the notebook is run, you'll have access to the top-rated movies' data. You can explore and analyze the data using Python and visualization libraries like `matplotlib` or `seaborn`.

## Data Collected

This notebook collects the following data for TMDB's top-rated movies:

- adult
- backdrop_path
- genre_ids
- id
- original_language
- original_title
- overview
- popularity
- poster_path
- release_date
- title
- video
- vote_average
- vote_count

You can easily customize the notebook to collect additional data or perform more complex analyses as needed.

## Support

If you have any questions, encounter issues, or need assistance, you can contact at saurav.sabu9@gmail.com. I am here to help you with any inquiries or problems you may have.

