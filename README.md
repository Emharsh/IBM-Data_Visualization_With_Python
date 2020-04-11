# IBM-Data_Visualization_With_Python
Data Visualisation with Python Project

1.
A survey was conducted to gauge an audience interest in different data science topics, namely:

Big Data (Spark / Hadoop)
Data Analysis / Statistics
Data Journalism
Data Visualization
Deep Learning
Machine Learning
The participants had three options for each topic: Very Interested, Somewhat interested, and Not interested. 2,233 respondents completed the survey.

The survey results have been saved in a csv file and can be accessed through this link: https://cocl.us/datascience_survey_data.

If you examine the csv file, you will find that the first column represents the data science topics and the first row represents the choices for each topic.

In order to read the data into a dataframe like the above, one way to do that is to use the index_col parameter in order to load the first column as the index of the dataframe. Here is the documentation on the pandas read_csv method: https://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_csv.html

Once you have succeeded in creating the above dataframe, please upload a screenshot of your dataframe with the actual numbers.

2.
Use the artist layer of Matplotlib to replicate the bar chart below to visualize the percentage of the respondents' interest in the different data science topics surveyed.

To create this bar chart, you can follow the following steps:

Sort the dataframe in descending order of Very interested. Convert the numbers into percentages of the total number of respondents. Recall that 2,233 respondents completed the survey. Round percentages to 2 decimal places. As for the chart: use a figure size of (20, 8), bar width of 0.8, use color #5cb85c for the Very interested bars, color #5bc0de for the Somewhat interested bars, and color #d9534f for the Not interested bars, use font size 14 for the bar labels, percentages, and legend, use font size 16 for the title, and, display the percentages above the bars as shown above, and remove the left, top, and right borders.

3.
Based on the San Francisco crime dataset, you will find that San Francisco consists of 10 main neighborhoods, namely:

Central, Southern, Bayview, Mission, Park, Richmond, Ingleside, Taraval, Northern, and, Tenderloin. Convert the San Francisco dataset, which you can also find here, https://cocl.us/sanfran_crime_dataset, into a pandas dataframe, like the one shown below, that represents the total number of crimes in each neighborhood.

4.
GeoJSON file that marks the boundaries of the different neighborhoods in San Francisco. In order to save you the hassle of looking for the right file, I already downloaded it for you and I am making it available via this link: https://cocl.us/sanfran_geojson.

For the map, make sure that:

1.it is centred around San Francisco, 2.you use a zoom level of 12, 3.you use fill_color = 'YlOrRd', 4.you define fill_opacity = 0.7, 5.you define line_opacity=0.2, and, 6.you define a legend and use the default threshold scale.

For this, we have to install folium
