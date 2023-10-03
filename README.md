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

1. **Clone or Download the Notebook**: Clone this GitHub repository or download the Jupyter Notebook (`Movies_Dataset.ipynb`) to your local machine.

2. **Open the Notebook**: Launch Jupyter Notebook and open the `Movies_Dataset.ipynb` file.

3. **Enter Your API Key**: Replace `'YOUR_API_KEY'` in the notebook with your actual TMDB API key.

4. **Run the Notebook**: Execute the notebook cell by cell by clicking on each cell and pressing Shift+Enter. The notebook will guide you through the process of making API requests, processing the data, and displaying the results.

5. The data will be saved to a CSV file named `movies_data.csv`.

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

The data will be saved in a CSV file for further analysis or use.

## Contributing
If you would like to contribute to this project, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and test them.
- Create a pull request with a clear description of your changes.

## Support

If you have any questions, encounter issues, or need assistance, you can contact at saurav.sabu9@gmail.com. I am here to help you with any inquiries or problems you may have.

