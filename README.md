# bikesharing

## Project Overview
The scenario for this project is that a friend and you want to make a service like New York City's Citi Bike available in Des Moines, Iowa. In order to you so, you need some seed money from investors. To convince these individuals that this business model will be profitable in Des Moines, you begin digging through some Citi Bike trip data. Eventually, a tableau dashboard is created from this data, showing a variety of visualizations comparing variables like ride number by gender (male, female, or unknown) and user type (Citi Bike subscriber, or single time use). From these visualizations we are able to deduce market insights and patterns that can be paired with Des Moines market conditions to support our belief that this business will succeed and generate return for our investors.

## Resources
Data Source: https://s3.amazonaws.com/tripdata/index.html (August 2019 dataset)
Software: Tableau, Python, Jupyter Notebooks

## Results
In our public dashboard, there are three sections that tell the story of why this business will be successful. We begin with general ride information. This includes how many total rides took place in August 2019 (~2.3M rides). We then break this data down by the hour to show which days at what hour generally have the highest usage. The trend we see is 8am and 5-6pm have the highest usage. This is a good sign as these hours signifiy the beginning and end of the work day respectively, and is thus when people are commuting. These commuting hours occur on a national level, thus we could believe that these hours would translate well in Des Moines.

![generic.png](https://github.com/asliwinski23/bikesharing/blob/main/generic.png)

In the second part of our analysis, we discuss gender. An overwhelming majority of Citi Bike users are men as seen in the chart below. However, this is not because there are more men than women in New York City. In fact, in New York City it is almost a 1:1 breakdown between male and female. This is also the case for Iowa. Thus, my friend and I can strengthen our case by addressing this underserved population by Citi Bike. We can pitch a marketing strategy to attract more women to ride our service. For example, many women have been taken out of the workforce since the pandemic, thus they would not likely be riding our bikes during the seemingly popular 8am and 5-6pm hours. Pitching a relaxing afternoon in the park with friends or family can be an enticing way to get others interested in the service.

![gender.png](https://github.com/asliwinski23/bikesharing/blob/main/gender.png)

Lastly, we look at ride by user type. There are two key types of users: those who are Citi Bike subscribers and those who are not. Over 80% of Citi Bike users are subscribers, which works in Des Moines favor. Subscribers are not likely to be tourists, as the average vacation duration is just four days. New York City certainly attracts more tourists than Des Moines, so if the service mainly attracted tourists, we may not have a compelling argument on this aspect.

![user.png](https://github.com/asliwinski23/bikesharing/blob/main/user.png)

The compelte dashboard can be found in the following link. The recommended view is full screen.
https://public.tableau.com/profile/alaina.sliwinski#!/vizhome/ChallengeDashboard_16218017477840/Story1?publish=yes

## Summary
Our Citi Bike analysis supports our belief that we can replicate the success of Citi Bike in Des Moines. However, an aspect that investors would certainly be curious about that is not highlighted in these charts would be demographic information about users outside of gender. For example, if majority of the users fall between age 25-34 and this age group has a large prescence in Des Moines, our argument would be a lot stronger. Furthermore, it would be extremely compelling if we were to have a business model that includes variables around revenue and cost predictions (on an annual basis, not just for August) in our presentation. Our results tell us that a lot of Citi Bike users are subscribers, so it would be valuable to know how much revenue Citi Bike is making on these individuals, in order to have a better idea when our business would be profitable.
