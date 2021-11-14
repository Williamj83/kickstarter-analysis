# Kickstarting with Excel

## Overview of Project
The project will visualize campaign outcomes based on their launch dates and their funding goals. 

### Purpose
Louise wants to know how different campaigns faired in relation to their launch dates and their funding goals.

## Analysis and Challenges
Analysis of Outcomes Based on Launch Date
For Outcomes Based on Launch Date, I used a pivot table to filter out campaign outcomes; successful, failed or canceled based on launch date. These results are visualized using a line chart. The data indicate May-June as the best time to launch campaigns.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/90795844/141693575-feda80e7-f878-41dd-94f6-597c3ad59486.png)

Analysis of Outcomes Based on Goals
For Outcomes Based on Goals, I created a chart and used countifs() function to populate the monetary goals of successful, failed and canceled campaigns that were plays. These results were visualized using a line chart. The data indicate that most campaigns are more successful at $5000 and below goal ranges.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90795844/141693615-2481b062-ac13-4e74-8f42-04689f391dd4.png)

### Challenges and Difficulties
There were no challenges or difficulties encountered. Possible challenges and difficulties in relation to the length of the countifs() function and duplicating it to every column were noticed early.

## Results

One conclusion drawn about the Outcomes based on Launch Date are May-June is the most successful time to launch, this is demonstrated by the number of successful launches during that timeframe vs the number of unsuccessul.
Another conclusion is December is the least successful time to launch because that time period has the least amount of successful launches.

One conclusion drawn from the Outcomes based on Goals is Campaigns are only half as successful once they goal goes over $5000.

 Some limitations of this dataset for the Outcomes Based on Goals are the dollar amount for the goal ranges. It doesn't allow for the possibility of determining a more narrow range of the most successful dollar amount. Creating another chart for Outcomes Based on Goals that examines the specific goals between $0 to $4999 would go even further to see the most successful goal amount.


