# IS-590-Data-Visualization-Final-Project
# 1.	What is your dataset?<br/>
The project used two datasets of Chicago and New York City criminal accidents that have common data about time, types, and locations of the crimes.<br/>
•	The size of your dataset<br/>
Chicago dataset is 1.5 Gb and New York dataset is 1.8 Gb that in total is 3.2 Gb which meets the data size requirement of the project.<br/>
•	What are your variables?<br/>
Since the data is large, and is not distributed appropriately, I used only 2015 data by filtering it, and created “ny_2015” and “ch_2015” variables. Original variables are called “ny_crimes” and “ch_crimes”. <br/>
•	Why did you decide to choose that dataset?<br/>
Because I was looking for the datasets that have location information (latitiude/longitude), and the only dataset that meets data size requirement is the one I found. <br/>
# 2.	A visual of your data visualization development<br/>
•	How will you store your data?<br/>
The data is stored in csv files on my computer.<br/>
•	How will you access your stored data?<br/>
Through pandas pd.read_csv function, and then by assigning variables for necessary columns.<br/>  
•	What languages/frameworks will you use?<br/>
I used Python 3, and pandas, matplotlib, and Bokeh. Also, I showed my geo-visualizations I made in the past using Hadoop, Apache Pig, and Apache Spark. <br/>
•	Why did you choose this storage mechanisms, and languages/frameworks?<br/>
Because I didn’t use very large (100s of Gb) dataset, and Bokeh has beautiful interactive visualization tools like Hover Tool. I did not use Hadoop, Apache Pig, and Apache Spark because I did not know if it is possible to create interactive visualizations using them.   <br/>
# 3.	Explain your exploratory data analysis process<br/>
There was not so much exploratory data analysis, Firstly I checked the number of rows in both datasets, which was very similar, but then I found that distribution by time is inappropriate, and year of 2015 was chosen because it looked more consistent than other years. <br/>
•	What are you trying to highlight from your data?<br/>
The distribution of the crimes and their types along both cities.<br/> 
•	What are your overall goals with this visualization?<br/>
To show that just numbers can mislead, and geo-visualization shows how it is distributed on places.<br/> 
# 4.	Troubles/Issues/Concerns with your data visualization<br/>
•	What did you find easy about development?<br/>
Creating geo-visualization (using Bokeh) and graphs.<br/>
•	What did you find difficult about development?<br/>
Data cleaning. Firstly I needed to convert my date format for Python (pandas) for which I spent most of the time. Overall, the data was totally unusable. I needed to reassign the columns to their names, by replacing semi-colon to colons. Some years were written as“1015” instead of “2015”.<br/>
•	What would you have liked to change about your visualization?<br/>
I wouldn’t change my map, instead I would add more interactivity by adding slider, buttons, etc. I would order my bar chart by ascending order, which looks better. <br/>
•	Did you find any evidence of bias in your dataset?<br/>
No, I did not. The data distributed all over the New York and Chicago borders, and the data make sense, and presents logical evidence. 
