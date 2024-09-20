# Zomato Restaurant Recommendation System with Sentiment Analysis

This project is a comprehensive **restaurant recommendation system** using the **Zomato dataset**. It incorporates both **content-based filtering** and **sentiment analysis** from customer reviews to provide relevant and high-quality restaurant recommendations.

## Features

- **Data Loading and Cleaning**: The dataset is cleaned to remove unnecessary columns and handle missing data.
- **Exploratory Data Analysis (EDA)**: Visualized insights like restaurant ratings, top cuisines, and cost distribution.
- **Content-Based Recommendation Engine**: Recommends restaurants based on cuisine, location, and restaurant type using **Nearest Neighbors**.
- **Sentiment Analysis**: Uses **VADER sentiment analysis** on customer reviews to classify them as positive, neutral, or negative.
- **Enhanced Recommendations**: Filters recommendations based on a **minimum rating** and **positive sentiment scores**.
- **Sentiment Distribution Visualization**: Displays the sentiment breakdown (positive, neutral, negative) for each restaurant.

## Project Workflow

1. **Data Loading**: Load and clean the Zomato dataset.
2. **Exploratory Analysis**: Visualize key statistics about restaurant features.
3. **Recommendation Engine**: Build a content-based system to recommend similar restaurants.
4. **Sentiment Analysis**: Analyze reviews to generate sentiment scores for each restaurant.
5. **Visualization**: Plot sentiment distribution for individual restaurants and enhance recommendations using sentiment data.

## Requirements

- Python 3.x
- Libraries: 
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `vaderSentiment`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/zomato-recommendation.git
    ```
2. Navigate to the project directory:
    ```bash
    cd zomato-recommendation
    ```
3. Create and activate a virtual environment:
    ```bash
    python -m venv myenv
    source myenv/bin/activate  # For Windows use: myenv\Scripts\activate
    ```
4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Jupyter Notebook or Python script to execute the recommendation system.
2. Input a restaurant name to get similar recommendations filtered by sentiment and ratings.
3. Visualize the sentiment distribution for any restaurant.

## Future Work

- Real-time sentiment analysis updates.
- Sentiment trends over time.
- Restaurant comparison based on various metrics.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
