# Data Sourcing Challenge
## Module 6 Challenge


# Overview

This Python script retrieves movie reviews from The New York Times API based on specified criteria, extracts relevant information, and enriches it with additional data from The Movie Database API. The resulting data is stored in a CSV file for further analysis.

## Dependencies

- `requests`: For making HTTP requests.
- `time`: For adding delays between API requests.
- `dotenv`: For loading environment variables from a `.env` file.
- `os`: For accessing environment variables.
- `pandas`: For data manipulation and analysis.
- `json`: For working with JSON data.

## Setup

1. **Environment Variables**:
   - Obtain API keys for The New York Times (NYT) and The Movie Database (TMDB) APIs.
   - Create a `.env` file in the project directory.
   - Add your NYT API key as `NYT_API_KEY` and TMDB API key as `TMDB_API_KEY` in the `.env` file.

2. **Installation**:
   - Install the required Python packages using `pip install -r requirements.txt`.

## Usage

1. **Running the Script**:
   - Execute the script `retrieve_movie_data.ipynb`.
   - The script will fetch movie reviews from NYT API, enrich them with data from TMDB API, and store the results in a CSV file named `merged_data.csv`.

2. **Customization**:
   - Modify the script to adjust search criteria (e.g., date range, keyword) in the `filter_query`, `begin_date`, `end_date`, and other relevant variables.

## Output

- The script generates a CSV file (`merged_data.csv`) containing merged data from NYT and TMDB APIs.
- The CSV file includes information such as movie titles, review details, production details, and more.

## Notes

- The script includes rate limiting to prevent exceeding API rate limits.
- Ensure proper API key management and adherence to API usage policies.

## Contributors
This code was written by [Richard Lankford](https://github.com/rwlankford/data-sourcing-challenge) with assistance and review from **Rimi Sharma** and **Tyler B. Shubert**

