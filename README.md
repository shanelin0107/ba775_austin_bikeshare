# Beyond Traffic: Transforming Austin's Mobility with Bike Share and Weather Data

# Executive Summary
This report analyzes Austin's bike share system and weather data to optimize urban mobility and support sustainability goals. By examining station utilization, peak usage times, and the impact of weather conditions on  ridership, it identifies opportunities to enhance system efficiency. Findings reveal high-demand stations that could benefit from relocation, weather's significant influence on casual riders, and the system's role in reducing car trips and improving air quality. Recommendations include relocating underused stations, increasing bike availability during peak times, implementing weather-based promotions, and highlighting environmental benefits to attract diverse users. The framework offers actionable insights for Austin and can be adapted for other cities like Boston, emphasizing climate-specific strategies for sustainable transit.

# Business Problem Definition
The analysis of the Austin bike share dataset, in conjunction with weather data, aims to provide a comprehensive understanding of bike usage patterns and their relationship with weather conditions. By examining factors such as temperature, precipitation, and humidity, the project seeks to uncover insights that can help optimize bike share operations and improve urban mobility.  

# Key objectives are:

1. Identify Station Activity: Determine the most and least active bike stations to understand usage patterns and inform station placement strategies.  

2. Analyze Peak Usage Periods: Analyze different times of day with varying ridership to optimize service availability and resource allocation.  

3. Examine Subscriber Behavior: Understand how different weather conditions influence ridership among various subscriber types, allowing for targeted marketing and service adjustments.  

4. Identifying Environment Impact and potential Health Insights: Illuminate the positive contributions of cycling to sustainability, including reductions in carbon emissions, improved air quality, and enhanced public health.  

# Motivation
With the increasing challenges of urban traffic congestion and pollution, bike-sharing systems offer a sustainable transit solution. Integrating weather insights can make these systems more responsive to real-time conditions, enhancing accessibility and convenience. By analyzing how weather impacts bike usage in Austin, we can make bike-sharing more adaptable to user needs, improve operational efficiency, and align with the city’s environmental initiatives. This study supports Austin’s commitment to green city goals, promoting healthier transit options and creating a data-driven foundation for a more resilient, eco-friendly urban landscape, which can not only improve the conditions of Boston but also has the potential to impact the entire world.  

# Conclusion
The analysis of Austin's bikeshare and weather data reveals distinct trends in bike usage influenced by environmental factors. Lower humidity correlates with slightly higher trip counts and shorter durations, while moderate humidity sees higher ridership and longer trips. Weekday riders show more resilience to rain than weekend riders. High-traffic stations near the University of Texas and downtown Austin require increased bike supply, especially during extreme weather, while underperforming stations may need relocation. Seasonal and weather trends affect bike preferences, with classic bikes favored in good weather and electric bikes preferred for faster, less demanding commutes. The data highlights bikesharing's positive environmental and health impacts, including reduced car usage, lower emissions, and improved air quality.  

These insights are crucial for optimizing bike share operations in Austin, as they provide actionable data on fleet management, station location, and maintenance schedules, particularly during peak demand times or adverse weather conditions. The clear identification of weather patterns that influence trip behavior allows for tailored resource allocation, ensuring bikes are available where and when they are most needed. For example, understanding that weekends see longer rides can help adjust fleet sizes at popular stations in recreational areas like Zilker Park. Similarly, ensuring bike availability during rainy conditions in resilient stations helps maintain user satisfaction. Furthermore, the data on environmental impacts provides a foundation for marketing campaigns that emphasize the sustainability and health benefits of bikesharing, promoting it as an eco-friendly alternative to car use and a tool for improving public health.  

Stakeholders can enhance the bikeshare system by investing in weather-resilient infrastructure, such as sheltered racks at stations with stable usage during adverse conditions, and promoting flexible pricing plans to cater to both occasional and regular riders. Fleet management should focus on allocating bikes based on weather conditions, with increased availability of electric or classic bikes during favorable weather and ensuring reliable service during rain. Station placement should prioritize high-demand areas like downtown and the University of Texas, reallocating bikes to optimize bike and dock availability. Marketing efforts can highlight the environmental and health benefits of biking, while promotions targeting rainy days can maintain ridership. Additionally, data-driven resource allocation and operational adjustments for peak hours and adverse weather will improve efficiency and user satisfaction across all conditions.  

Also, adding information regarding demography such as the demographic information of Austin can be used to further enhance this analysis and make more personalised recommendations to the stakeholders.  

# Challenges
The first challenge that we faced was the challenge of the nulls. Many columns had nulls in the weather dataset and initially, we figured this may be a very big issue but some analysis revealed even the nulls have meaning and so, we decided to keep it. The next challenge was to identify how to divide the analysis in different sections such that it gives a holistic and broad view for the stakeholders, who own this bikeshare system and since, they have to deal with city planners and deal with different areas, so how can we cover those aspects and that issue brought the Environmental and Health Insight section. Another big challenge that we encountered was how do we dive deep into the analysis for why students use the system the most, which was uncovered in the Subscriber Type Behavior section. Also, it was a major challenge to identify how to personalise the Weather Specific Trends for Austin but some analysis into the dataset revealed the different aspects which can be used. The windgust, cloudcover and humidity were identified to be the best as Austin is typically known for tornadoes and these are some of the strongest identifiers for the tornadoes.  

# Dashborad
![image](https://github.com/user-attachments/assets/e8b28e08-dbc2-4008-9c07-9a6f25916670)


# References
1. Capital Metro. (n.d.). Bike share., 2024, from https://www.capmetro.org/bikeshare  
2. University of Texas at Austin. (n.d.). Bike sharing: CapMetro BikeShare. ,2024, from https://parking.utexas.edu/transportation/bikeut/bike-sharing-capmetro-bikeshare
Modern SQL. (n.d.). COUNTIF in SQL., 2024, from https://modern-sql.com/excel/countif-in-sql  
3. Portland State University, Transportation Research and Education Center (TREC). (2017). Breaking Barriers to Bike Share: Insights and Lessons Learned from Bike Share Equity Programs. Retrieved from https://betterbikeshare.org/wp-content/uploads/2017/07/TREC_BreakingBarriersSummaryReport_emQeiBA.pdf  
4. The Daily Texan. "Austin B-cycle Ends Free Student Membership after University Refuses Funding Operating." The Daily Texan, 23 Jan. 2019, https://thedailytexan.com/2019/01/23/austin-b-cycle-ends-free-student-membership-after-university-refuses-funding-operating/.  
5. BCycle. "Austin B-cycle Expands Service to UT Campus and West Campus Neighborhoods." BCycle, 14 Feb. 2018, https://www.bcycle.com/news/2018/02/14/austin-b-cycle-expands-service-to-ut-campus-and-west-campus-neighborhoods#:~:text=Austin%20B-cycle%20Expands%20Service.  
