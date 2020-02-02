Original graphic from The Economist (https://www.economist.com/briefing/2020/01/18/back-pain-is-a-massive-problem-which-is-badly-treated)

![image](https://user-images.githubusercontent.com/59805738/73603477-56412980-4551-11ea-8c60-86bf61092698.png)


Referenced data source: 
http://ghdx.healthdata.org/record/ihme-data/gbd-2017-incidence-prevalence-and-ylds-1990-2017

I choose this visualization because I am very interested in health policy and would like to explore how health can influence labor and employment. Because people with back pain are commonly classified as having a disability, this graph can be useful to explain how health trends can have a direct impact on employment trends. The accompanying article made a great point about the effectiveness of long term care and conditioning but rarely do people follow through with these instructions and often choose one-time “fixes” like surgery. The visualization is informative, but one would have to look longer than necessary to understand the trend and here is my attempt to make it better.

Two criteria from the critique method helped me think about how to improve the graph: completeness and intuitiveness. The graph doesn’t seem very complete, in fact, it offers more information than necessary and lacks information at the same time. Comparing years lived per 100,000 people is confusing and the graph should provide something for the audience to anchor or determine what is “normal”. The graph also is not intuitive. The y-axis is on the right and the scale makes it hard to read. I want to redesign the graph focusing on these elements. 

To redesign the graph, I thought it was important to read the article and identify what the main points of it was and how the article is using the graph. The article addresses growing trends in low-back pain diagnosis and high medical costs related to it. The main point of the article (and what the graph is meant to illustrate) is that the burden of low-back pain is slowly decreasing over time, inferring that there is some justification for the price of care. The point of the graph seemed simple, to show that years lived with back pain is decreasing, but it is shown in a convoluted way. 

Below are my initial wireframes. I decided to move the y-axis scale to the left and use the average years lived instead of the per 100,000 people unit that the articles used. I started with a bar graph to compare with the line graph. The bar graph seemed to focus on years lived per each age group, so I stuck with the line graph. I cleaned it up and added more details to it before sharing it for feedback from two different people. 


![image](https://user-images.githubusercontent.com/59805738/73603471-3f023c00-4551-11ea-894f-db9cd068744f.png)


Feedback I received:
-Change y-axis scale, too much blank space
-Line graph was a good choice to show the information
-Monocolor was acceptable because the graph is only measuring 2 things
-Understood that back pain disability was decreasing over time

I used the feedback to modify the y-axis scale. After pulling the files from IHME and working with the data, I realized it was harder to show average life lived per person with back pain (the data was not available to support it). Instead, I massaged the data to show the percent of total years lived with back pain per age group. I used Tableau to create an updated version of the graph. 
Updated version: 


![image](https://user-images.githubusercontent.com/59805738/73603480-622ceb80-4551-11ea-84c1-80f29ca49c00.png)
