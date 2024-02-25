# Travel Suggestion Recommendation System

The Travel Suggestion Recommendation System is a Python-based project developed in Jupyter Notebook. It utilizes machine learning algorithms and various libraries such as `sklearn`, `pandas`, and `tkinter` to recommend top travel destinations based on user input parameters like destination city, trip duration, and budget per day.

## Overview

This recommendation system aims to assist travelers in selecting their ideal destinations by considering factors such as place ratings, optimal travel times, and budget requirements. By leveraging the `TfidfVectorizer` and `cosine_similarity` algorithms, it analyzes a vast dataset of travel destinations to provide personalized recommendations tailored to the user's preferences.

## How It Works

1. **User Input**: The user provides details including the destination city, start and end dates of the trip, and the budget per day.
2. **Data Processing**: The system preprocesses and analyzes a dataset of travel destinations, extracting relevant features such as ratings, seasonal popularity, and budget estimates.
3. **Recommendation Generation**: Using machine learning algorithms, the system computes similarity scores between the user's input and each destination in the dataset.
4. **Top Recommendations**: The system selects the top 5 destinations with the highest similarity scores and presents them to the user as personalized travel recommendations.

## Installation

To run the Travel Suggestion Recommendation System locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/travel-recommendation-system.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the `Travel_Suggestion_System.ipynb` notebook and execute the cells to interact with the system.

## Usage

1. Execute the Jupyter Notebook and navigate to the `Travel_Suggestion_System.ipynb` file.
2. Follow the instructions within the notebook to input your destination city, trip dates, and budget per day.
3. The system will generate and display the top 5 recommended travel destinations based on your preferences.
