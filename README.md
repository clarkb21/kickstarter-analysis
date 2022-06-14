# Kickstarter Analysis 

## Overview of Project
- Analyze large amounts of data from a kickstarter campaign data set
- Use visualizations to help show results and trends in the data 
- Find patterns in the data to assist Louise in being as successful as possible with her business ideas

### Purpose
- Apply skills from the first module into an applicable scenario
- Challenge myself to create new ways to show how data can help people and businesses make decisions
- Familarize myself with coding and formulas in an Excel spreadsheet
- Utilize pivot tables, Excel commands, and various types of charts for visualization purposes

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
  - I created a Pivot table and set up the filters to allow me to only see the months a campaign was launched and whether or not it was successful. 
  - I filtered the table to only see theater campaigns
  - A line chart would work best to show the outcomes over a year. 
  
![Theater Outcomes Pivot Table- Screenshot](https://user-images.githubusercontent.com/104038813/173471104-324db2ff-4547-4ad6-831d-f8a470fdeddc.png)

### Analysis of Outcomes Based on Goals
  - In order to see a pattern for outcomes based on goals, I created a new table with multiple intervals for the goal amount for each campaign. 
  - I set up columns to show the number of successful, failed, and canceled campaigns based on their goal amount. Then I found the percentage of each interval that was successful to see any trends in the data. 
  - Again, I used a line chart to show the changes in successful and failed campaigns as the goal amount increased. 
  - To determine the number for each goal, I used the "countifs" formula in Excel, and set criteria to filter out only the play campgains in each interval. 
  
 ![Count ifs Formula ](https://user-images.githubusercontent.com/104038813/173471947-93130848-bb35-4e9a-98e4-3662034c8644.png)
 
 ### Challenges and Difficulties Encountered
  - For the first part of the challenge, Theater Outcomes by Launch Date, I struggled at first creating the Pivot table to show the Rows as months instead of years. I knew I wanted to know the outcomes by month; "outcomes" was put correctly in the Columns section, and "Count of Outcomes" was successfully placed in the values section. Once I filterd the months to show in the Pivot table, the data was showing me exaclty what I wanted to know. 
  
 ![Pivot Table- Outcomes by Launch Date](https://user-images.githubusercontent.com/104038813/173472405-2d8161cb-0054-401e-8f40-555a4bf26934.png)
 
 - For the second part of the challenge, Outcomes Based on Goal, I struggled at first with setting up the "countifs" formula to properly display what I was wanting to show. I realized I wanted to filter out just successful play campaigns with a goal less than $1000, and I finally set it up where I locked the cell numbers from the existing Kickstarter workbook so that I could copy the formula over to the failed and canceled columns without having to change much of the information. 
 
 ![Count ifs Formula- 2](https://user-images.githubusercontent.com/104038813/173472903-934d9f53-2b79-40ae-827c-762d08365d3e.png)
 
 - I was also confused for a moment that the canceled column was all zeros. I went back to the original document to double check that there were in fact no canceled play campaigns for any of the goal amounts. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1) Based on the data, launching a theater campaign during the month of May is more likey to be successful compared to any other month. 
      - May had 111 successful outcomes compared to just 52 failed outcomes
     - The failed outcomes were very consistent throughout the year. 
    2) Launching a theater campaign in December is not advised.
       - December saw only 37 successful campaigns compared to 35 failed. 
       - This is the only month where the successful and failed campaigns are virtually even. 

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
