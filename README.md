# Cricket-Dream-Team-Analyser

# Problem Statement
A cricket dream team analyzer aims to address the challenges cricket enthusiasts face in optimizing their fantasy cricket teams for various formats of the game. The problem statement involves designing a tool that provides users with insights, statistics, and recommendations to help them strategically select players and make informed decisions when creating their dream cricket teams.

# Step 1: Setting Up Parameters
To assemble the best 11 players, our parameters focus on batting and bowling performance. Openers, middle-order, and lower-order players are evaluated based on metrics like batting average, strike rate, innings batted, boundaries, and batting position. Similarly, spinners and fast bowlers are assessed using relevant indicators such as bowling average, economy rate, and wickets taken. The objective is to create a balanced team capable of scoring an average of 180 runs while defending 150 runs with a margin of 30 runs. The selection process aims for a well-rounded composition, ensuring each player contributes effectively to the team's success.



# Step 2: Data Collection using Web Scrapping
I gathered player statistics for our cricket dream team using web scraping from ESPN. This automated approach ensures we have the latest and most accurate data on metrics like batting averages, strike rates, innings batted, boundaries, and bowling statistics. Data collected in the form of JSON.

# Step 3: Data Cleaning & Transformation
In the process of data cleaning and transformation using Python with the Pandas library, the initial step involves loading JSON data into a Pandas DataFrame. Subsequently, data cleaning is executed to handle missing values, remove duplicates, and address any anomalies or inconsistencies. Following this, data transformation takes place, incorporating operations such as creating new columns, aggregating information, or altering data types to better suit analysis requirements.
Once the data is refined and structured appropriately, it is then converted to a CSV file, providing a standardized and accessible format for further analysis in Power BI. This approach ensures that the data is not only cleaned and free of irregularities but also structured in a manner conducive to meaningful insights and downstream applications.

# Step 4: Data Transformation using Power Query
Data transformation using Power Query is an effective next step after initial cleaning and transformation with Python. Power Query, often integrated into tools like Microsoft Excel or Power BI, provides a user-friendly interface for additional data shaping and refinement.In our case,we will be integrating it with Power BI.







# Step 4: Data Modelling ans Building Parameters using DAX

