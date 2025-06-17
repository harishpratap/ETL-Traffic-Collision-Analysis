# ETL-Traffic-Collision-Analysis
Business Objective
Business Value
Traffic collisions pose significant risks to public safety, requiring continuous monitoring and analysis to enhance road safety measures. Government agencies, city planners and policymakers must leverage data-driven insights to improve infrastructure, optimise traffic management and implement preventive measures. In this assignment, you will analyse California traffic collision data to uncover patterns related to accident severity, location-based risks and key contributing factors. With Apache Spark’s ability to handle large datasets efficiently and AWS S3’s scalable storage, transportation authorities can process vast amounts of crash data in real time, enabling faster and more informed decision-making.


As an analyst examining traffic safety trends, your task will be to analyse historical crash data to derive actionable insights that can drive policy improvements and safety interventions. Your analysis will help identify high-risk areas, categorise accidents by severity and contributing factors and store the processed data in an AWS S3 bucket for scalable and long-term storage. By leveraging big data analytics and cloud-based storage, urban planners and traffic authorities can enhance road safety strategies, reduce accident rates and improve public transportation planning.


Assignment Tasks
Present the overall approach of the analysis in a report document. Mention the problem statement and the analysis approach briefly.


In the starter notebook, you will find headings, subheadings and checkpoints stating the tasks you need to perform. The marks associated with each checkpoint will also be mentioned in the notebook. Keep in mind not to edit the cells with marking schemes and questions. 

 

The video below will take you through the different tasks for the assignment.

Play Video5997944
You can find a brief description of the tasks below.


1. Data Preparation [5 marks]

The dataset consists of structured tables containing traffic collision data. Before conducting any analysis, it is essential to ensure that the data is properly formatted and structured for efficient processing. 

Check for data consistency and ensure all columns are correctly formatted.
Apply sampling techniques if needed to extract a representative subset for analysis.
Structure and prepare the data for further processing and analysis.
 
2. Data Cleaning [20 marks]

Fixing columns [5 Marks]
Handling missing values [10 Marks]
Handling outliers [5 Marks]
Hints:

Note that it is not necessary to replace the missing value in EDA. If you have to replace it, what should be the approach? Mention the approach.
Identify if there are outliers in the dataset. Furthermore, mention why you think it is an outlier. Again, remember that for this exercise, it is not necessary to remove any data points.
 

3. EDA: Finding Patterns [65 marks]

Data Preparation [5 Marks]
Analyse the distribution of collision severity. [5 Marks]
Examine weather conditions during collisions. [5 Marks]
Analyse the distribution of victim ages. [5 Marks]
Study the relationship between collision severity and the number of victims. [5 Marks]
Analyse the correlation between weather conditions and collision severity. [5 Marks]
Visualise the impact of lighting conditions on collision severity. [5 Marks]
Extract and analyse weekday-wise collision trends. [7 Marks]
Study spatial distribution of collisions by county. [7 Marks]
Analyse collision locations geographically.  [6 Marks]
Extract and analyse collision trends over time. Analyse yearly, monthly and hourly trends in collisions.  [10 Marks]
4. Data Querying [35 marks]

Load the processed dataset as CSV files in the S3 bucket.  [1 Marks]
Identify the top 5 counties with the highest number of collisions.  [4 Marks]
Identify the month with the highest number of collisions.  [5 Marks]
Determine the most common weather conditions during collisions.  [5 Marks]
Calculate the percentage of collisions that resulted in fatalities.  [5 Marks]
Find the most dangerous time of day for collisions.  [5 Marks]
Identify the top 5 road surface conditions with the highest collision frequency. [5 Marks]
Analyse lighting conditions that contribute to the highest number of collisions. [5 Marks]

5. Conclusion [10 marks]
The final insights and recommendations are discussed below:

Provide recommendations to improve road safety by identifying high-risk locations and peak accident times to guide infrastructure improvements and targeted enforcement.
Provide suggestions for optimising traffic management by analysing trends in collision severity, weather conditions and lighting to improve road design and traffic signal timing.
Propose data-driven policy changes to enhance pedestrian and cyclist safety based on collision trends involving vulnerable road users.
Identify potential high-risk zones for proactive intervention by examining geographic collision density and historical accident data.
Assess the impact of environmental factors such as weather, road surface conditions and lighting on accident frequency and severity.
Develop predictive models to anticipate collision hotspots and support proactive safety measures.
Points to note:

Conclude the analysis by summarising key findings and business implications.
Explain the results of univariate, segmented univariate and bivariate analyses in real-world traffic safety and policy terms.
Include visualisations and summarise the most important results in the report. You are free to choose the graphs that best explain numerical/categorical variables.
Insights should explain why each variable is important and how they can influence traffic safety policies and urban planning.
 

6. Visualisation Integration [Optional]

Enhance the project by incorporating a visualisation component that connects the processed data stored in an S3 bucket to a business intelligence tool such as Tableau or Power BI. This involves:
Setting up the connection between the S3 bucket and the chosen visualisation tool
Importing the processed dataset for analysis and visualisation
Creating interactive dashboards to explore key trends and insights
Ensuring data updates are reflected dynamically in the visualisation tool
 

In the starter notebook, attached below, you will find headings, subheadings and checkpoints stating the tasks you need to perform. The marks associated with each checkpoint will also be mentioned in the notebook. Keep in mind not to edit the cells with marking schemes and questions. 
