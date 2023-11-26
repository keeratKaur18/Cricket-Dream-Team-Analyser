# Cricket-Dream-Team-Analyser

# Problem Statement
A cricket dream team analyzer aims to address the challenges cricket enthusiasts face in optimizing their fantasy cricket teams for various formats of the game. The problem statement involves designing a tool that provides users with insights, statistics, and recommendations to help them strategically select players and make informed decisions when creating their dream cricket teams.


## Step 1: Setting Up Parameters
To assemble the best 11 players, our parameters focus on batting and bowling performance. Openers, middle-order, and lower-order players are evaluated based on metrics like batting average, strike rate, innings batted, boundaries, and batting position. Similarly, spinners and fast bowlers are assessed using relevant indicators such as bowling average, economy rate, and wickets taken. 

The objective is to create a balanced team capable of scoring an average of 180 runs while defending 150 runs with a margin of 30 runs. The selection process aims for a well-rounded composition, ensuring each player contributes effectively to the team's success.



###
<img width="695" alt="Screenshot 2023-11-26 at 7 00 55 AM" src="https://github.com/keeratKaur18/Cricket-Dream-Team-Analyser/assets/98026175/b06909b0-9aa2-402a-9287-085ae157e002">

###
<img width="695" alt="Screenshot 2023-11-26 at 7 01 03 AM" src="https://github.com/keeratKaur18/Cricket-Dream-Team-Analyser/assets/98026175/050d66cd-5b19-4b6c-b33d-0cfc5c96195f">


###
<img width="695" alt="Screenshot 2023-11-26 at 7 01 12 AM" src="https://github.com/keeratKaur18/Cricket-Dream-Team-Analyser/assets/98026175/5d31986a-6c15-4c9d-bf69-1ac46a0b663e">

###
<img width="697" alt="Screenshot 2023-11-26 at 7 01 21 AM" src="https://github.com/keeratKaur18/Cricket-Dream-Team-Analyser/assets/98026175/db3856c6-0da9-4282-ad74-03efe0abd926">


###
<img width="696" alt="Screenshot 2023-11-26 at 7 01 31 AM" src="https://github.com/keeratKaur18/Cricket-Dream-Team-Analyser/assets/98026175/56a26377-c6c4-4357-a238-e494c82e531f">

## Step 2: Data Collection using Web Scrapping
I gathered player statistics for our cricket dream team using web scrapping from ESPN. This automated approach ensures we have the latest and most accurate data on metrics like batting averages, strike rates, innings batted, boundaries, and bowling statistics. Data collected in the form of JSON.


## Step 3: Data Cleaning & Transformation
In the process of data cleaning and transformation using Python with the Pandas library, the initial step involves loading JSON data into a Pandas DataFrame. Subsequently, data cleaning is executed to handle missing values, remove duplicates, and address any anomalies or inconsistencies.
Once the data is refined and structured appropriately, it is then converted to a CSV file, providing a standardized and accessible format for further analysis in Power BI. This approach ensures that the data is not only cleaned and free of irregularities but also structured in a manner conducive to meaningful insights and downstream applications.


## Step 4: Data Transformation using Power Query
Data transformation using Power Query is an effective next step. Power Query, often integrated into tools like Microsoft Excel or Power BI, provides a user-friendly interface for additional data shaping and refinement. In our case,we will be integrating it with Power BI.


## Step 5: Data Modelling ans Building Parameters using DAX
The next step involves data modeling and parameterization using Data Analysis Expressions (DAX). DAX is utilized to create measures, implement time intelligence, and build dynamic parameters for analysis. Optimization ensures performance, and testing validates accuracy. This integration enhances the data model, providing a foundation for insightful reporting and decision-making.


## Step 6: 
Post DAX modeling, visualize data in Power BI. Create, customize visuals, and build dashboards. Power BI provides an intuitive platform for impactful data representation.


## Visualization :
<img width="1200" alt="Screenshot 2023-11-26 at 6 48 51 AM" src="https://github.com/keeratKaur18/Cricket-Dream-Team-Analyser/assets/98026175/7064146b-e001-4e5f-9243-4451a9cece58">
<img width="1199" alt="Screenshot 2023-11-26 at 6 49 03 AM" src="https://github.com/keeratKaur18/Cricket-Dream-Team-Analyser/assets/98026175/764a5ee4-2115-4312-bc02-1a9165215f66">
<img width="1198" alt="Screenshot 2023-11-26 at 6 49 13 AM" src="https://github.com/keeratKaur18/Cricket-Dream-Team-Analyser/assets/98026175/214413f1-a96a-451b-a075-52aa88515147">


## Video Demo :
https://drive.google.com/file/d/10582zH6INMr3pW59qnTvaNcWyCcxHdLZ/view?usp=sharing
