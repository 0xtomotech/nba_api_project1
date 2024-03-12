
# NBA Player Data Analysis Project (#1)

This beginner project is focused on analyzing and visualizing NBA player statistics using Python. Below is a breakdown of the project files, the technologies, packages, and modules used, along with other useful considerations.

## Project Files

- `nba_players.ipynb`: A Jupyter Notebook that contains the script to fetch all active NBA player IDs using the `nba_api`. This script is essential for gathering the foundational data required for analysis and image retrieval.

- `nba_stats.csv`: A CSV file that stores basic statistics of NBA players for the current season. This file serves as input for various analysis tasks.

- `nba_player_data_analysis.ipynb`: A Jupyter Notebook dedicated to analyzing the data contained within `nba_player_data.csv`. It includes data cleaning, exploratory data analysis (EDA), and visualization sections to uncover insights about NBA players.

- `nba_player_data.csv`: A CSV file containing detailed statistics and biographical information for NBA players. This dataset is used for in-depth analysis in the `nba_player_data_analysis.ipynb` notebook.

- `nba_stats_scraping.ipynb`: A Jupyter Notebook that outlines the process of scraping NBA player statistics from the web. This notebook demonstrates how to collect additional data that might not be available through the `nba_api`.

## Technologies and Packages

- **Python**: The primary programming language used for analysis and data collection.
- **Jupyter Notebook**: An open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text.
- **nba_api**: An API client for the NBA statistics located at stats.nba.com, used to fetch player IDs and other statistical data.
- **Pandas**: A library providing high-performance, easy-to-use data structures, and data analysis tools.
- **Plotly**: Library used for creating static, animated, and interactive visualizations in Python.
- **Requests**: A simple HTTP library used for making requests to the web for scraping purposes.

## Installation

To run the notebooks and scripts, ensure you have Python installed, then install the required packages using the following command:

```bash
pip install jupyterlab nba_api pandas plotly requests
```

## Usage

To view and run the notebooks, start JupyterLab or Jupyter Notebook from the terminal:

```bash
jupyter lab
```

Or for Jupyter Notebook:

```bash
jupyter notebook
```

Navigate to the project directory and open the desired notebook file.

## Considerations

- Ensure that you comply with the terms of service for any APIs or websites from which you scrape data.
- The `nba_api` is used under the assumption that it is for personal or educational purposes; ensure your usage complies with any usage policies.
- This project is structured for educational purposes and may require modifications for commercial application.
