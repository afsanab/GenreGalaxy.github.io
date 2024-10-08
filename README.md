# Genre Galaxy

**Genre Galaxy** is an interactive data visualization tool designed to map and analyze the relationships between literary genres. This project utilizes a comprehensive dataset sourced from Goodreads to reveal patterns and connections between genres, providing insights for academic researchers, publishers, and literature enthusiasts.

## Features

- **Interactive Visualization**: Explore the interconnectedness of literary genres through an interactive network graph. Nodes represent genres, and edges indicate the strength of their co-occurrence.
- **Search Functionality**: Search for specific books to highlight their associated genres and discover how they relate to other genres in the dataset.
- **Dynamic Interaction**: Click on genre nodes to see all direct connections, with related genres ranked by their co-occurrence strength.

## Technologies Used

- **Python**: Core programming language used for data processing and application development.
- **Dash**: Web framework for building the interactive application.
- **Plotly**: Visualization library used to create the network graph and interactive elements.
- **Pandas**: Data manipulation library for cleaning and processing the Goodreads dataset.
- **NetworkX**: Library used to construct and analyze the network graph of genres.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/afsanab/genregalaxy.git
    cd genregalaxy
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    python create_graph.py
    ```

4. Open your browser and go to `http://127.0.0.1:8050/` to view the application.

## Data Source

The dataset used for this project was sourced from Kaggle's [Best Books 10K Multi-Genre Data](https://www.kaggle.com/datasets/ishikajohari/best-books-10k-multi-genre-data), which includes data on thousands of books from Goodreads.

## Project Structure

- **create_graph.py**: Main application file containing the Dash setup and layout and script for generating the network graph using NetworkX.
- **process_data.py**: Script for cleaning and processing the Goodreads dataset.
- **calculate_stats.py**: Script for performing statistical analysis on genre pairs.
