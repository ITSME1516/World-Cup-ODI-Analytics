# World-Cup-ODI-Analytics

## Project Overview
This project delves into the analysis of ODI World Cup data, extracting valuable insights and trends using Python and its powerful libraries. The aim is to provide a comprehensive analysis of matches, teams, and player performances throughout the history of the ODI World Cup.

## Key Highlights
- **Data Collection**: Utilized BeautifulSoup (bs4) for web scraping to gather comprehensive data on ODI World Cup matches, teams, and player statistics.

- **Data Analysis**: Leveraged pandas for data manipulation and NumPy for numerical operations to perform extensive analysis on the collected data.

- **Visualization**: Used Matplotlib and Seaborn to create detailed and informative visualizations that effectively communicate the insights.


## Project Structure
"""
├── Data/  
│   # It contails all the data from webscraping except **math information data**  
├── Team/                
|   # It has the indivitual team data by years.From (1975 - 2024)  
├── Data Cleaning/                  # Source code for Cleaning the data and cleaned data files.  
│   ├── batting_pre_cleaning.ipynb  # Script for batting data Cleaning    
│   ├── bowling_pre_cleaning.ipynb  # Script for bowling data Cleaning  
│   ├── player_statistics.ipynb     # Script for adding some required features like strike rate, avg runs,balls,etc..  
|   ├── Data/                       # This folder contains the Processed data  
├── Analysis/  
|  ├── Analysis_1.ipynb             # Script for Analysis and visulization.  
├── # There are scripts that are used to collect the data from web.  
├── README.md                       # Project README file  
"""


## Acknowledgments
A special shoutout to the robust capabilities of BeautifulSoup, pandas, NumPy, Matplotlib, and Seaborn that made this analysis possible. Excited to continue exploring the potential of data analysis in sports!

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.


## Order for collecting the data from website.
1) t20_match.ipynb                  # Sorce code for collecting all seasons link.
2) all_match_info.ipynb             # Sorce code for collecting every single match information.
3) bat_bowl_info.ipynb              # Sorce code for collecting every single match batting and bowling information.
4) ground_info.ipynb                # Sorce code for collecting every match ground information.
5) player_ino.ipynb                 # Sorce code for collecting every player information.
