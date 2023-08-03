# Liga1PlayerDataExploration
Data Exploration of Liga 1 Indonesia 2023-2024 Player

I worked on this project based on my passion for data analysis and my hobbies and interest in football, especially on my local league called Liga 1 Indonesia.
It is quite hard when i try to find the ready data to do the analytics, so I started to collecting and gathering the player data from several resources and validate the registered player in the official website of Liga Indonesisa Baru.

## In this project, I have worked on it in several steps:
- Data collecting: collecting and gathering data from several resources and put them together in one csv file.
- Data validating: validating the data with data from the official website of Liga Indonesia, because there are often some changes even though player registration has closed.
- Data preparation and cleaning: convert data type, create new feature, handling missing values, handling duplicate data
- Basic data exploration: basic information and statistical details
- Getting insight: getting several facts and insights from the data
- Data Visualization: some data visualization to getting insight

## File Description
- Data Exploration of Liga 1 Indonesia Player.ipnyb : the jupyter notebook file to perform data analysis
- player_data.csv : csv data of player registered for Liga 1 Indonesia 2023-2024
    - kit_number : player jersey number
    - player_name : name of the player
    - position : position of the player in the game
    - Date of birth / Age : birth date of the player and player age in this year
    - nationality : nationality of the player
    - height : height of the player in meter
    - foot : strongest foot of the player
    - joined : player joined date to the current club
    - signed_from : previous club
    - contract : player contract
    - market_value : player market value in 1K Euro
    - club_name : current club of the player

 ## Dependencies
 - Python 3.11.4
 - numpy 1.25.1
 - pandas 2.0.3
 - matplotlib 3.7.2
 - seaborn 0.12.2
 - pycountry_convert 0.7.2
