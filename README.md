# ipl_auction_analysis

# IPL 2023 Auction Analysis using Pandas AI

This repository contains an analysis of the IPL 2023 Auction data using the Pandas AI library, which integrates AI-based insights into pandas DataFrame operations.

## Requirements

To run the notebook, you need the following dependencies:

- Python 3.x
- Pandas
- PandasAI
- OpenAI API key

You can install the necessary libraries by running the following commands:

```bash
pip install pandas pandasai openai

Setup
Clone this repository to your local machine.
Replace the OPENAI_API_KEY in the notebook with your own OpenAI API key.
Upload the IPL_Squad_2023_Auction_Dataset.csv dataset to the same directory as the notebook.
Notebook Overview
Steps in the Analysis:
Install and import necessary libraries: We install the required libraries such as pandasai and OpenAI.
Initialize OpenAI API: Set up the OpenAI API key to communicate with the GPT model.
Load the IPL dataset: Import the IPL Auction dataset using pandas and perform initial checks.
Data Cleaning: Remove unnecessary columns and preprocess the data for analysis.
Data Analysis with PandasAI: Use PandasAI's natural language processing abilities to perform various analysis tasks, such as:
Finding the most expensive players
Analyzing the cheapest buys and the respective teams
Drawing bar plots for money spent by teams
Listing unsold players and their base prices
Identifying the types of players that remained unsold
Visualization: Generate bar plots to show spending trends across teams.
Prompts Used for Analysis:
The notebook interacts with the PandasAI library to run natural language queries on the dataset, such as:

"Which players are the most costliest buys?"
"How many players remained unsold this season?"
"Draw a bar plot showing how much money was spent by each team."
Results
The notebook generates insights about IPL 2023 auction data, such as:

Most expensive players and their respective teams
Insights about unsold players
Money spent by each team in different categories
