# Cyclistic-Case-Study-Final
A study of how Cyclistic's users compare, a detailed analysis and actionable insights

Cyclistic is a Chicago-based bike-share company offering a diverse range of more than 5,800 bicycles, including traditional bikes, reclining bikes, hand tricycles, and cargo bikes, through 600 docking stations across the city. Cyclistic has built a solid reputation for its inclusivity, allowing a variety of users to meet their transportation needs, whether for leisure or commuting. While only 8% of users rely on the assistive options, the majority of Cyclistic’s ridership opts for traditional two-wheeled bicycles. Approximately 30% of total trips are for commuting purposes, while the remaining 70% are for leisure and other activities.

As Cyclistic continues to grow, the Director of Marketing, Lily Moreno, has identified that increasing the number of annual memberships is key to securing the company’s long-term success. After reviewing financial data, the Cyclistic marketing team found that annual members are significantly more profitable than casual riders. In response, Moreno has tasked the marketing analytics team with designing a data-driven marketing strategy aimed at converting casual riders into annual members.

Objective:

The primary objective of this case study is to analyze 12 months of historical bike trip data to uncover patterns and differences in how casual riders and annual members use Cyclistic bikes. With this knowledge, the goal is to design a targeted marketing campaign that convinces casual riders to become annual members.

By answering three key questions:

	1.	How do annual members and casual riders use Cyclistic bikes differently?
	2.	Why would casual riders consider purchasing annual memberships?
	3.	How can Cyclistic use digital media to effectively influence casual riders to convert to annual memberships?

Through deep analysis of the data, we aim to provide actionable insights that will form the foundation for a targeted marketing strategy aimed at increasing annual memberships and, ultimately, enhancing Cyclistic’s profitability.

Business Context:

Cyclistic launched in 2016 and has steadily expanded to become one of Chicago’s leading bike-share providers. The company’s bikes are geo-tracked, and users can unlock and return them at any station within the system. Cyclistic’s pricing strategy includes flexible plans: single-ride passes, full-day passes, and annual memberships. While casual riders purchase single-ride or day passes, annual members enjoy unlimited rides for a flat fee. The finance team has concluded that annual members generate more consistent revenue and are more valuable to the company’s long-term growth.

Up until now, Cyclistic’s marketing strategy has focused on general awareness, with campaigns aimed at broad consumer segments. However, to maximize future growth, Moreno believes that focusing on converting casual riders into annual members is the most effective path forward. Casual riders are already familiar with Cyclistic’s service, making them a promising segment for targeted marketing.

To ensure the success of this initiative, the marketing team needs to understand the key behavioral differences between the two user groups—casual and annual—and why casual riders would be motivated to convert to annual memberships.

Methodology:

In this case study, 12 months of historical data from August 2023 to July 2024 will be analyzed. The data was provided by Motivate International Inc. and is publicly available under Cyclistic’s data license agreement. The analysis will examine bike usage trends, focusing on ride duration, trip frequency, bike type preferences, and time of day for both casual and annual riders.

The data cleaning process began in RStudio and Excel where all 12 files were individually prepared for analysis:

	•	Duplicate and erroneous entries were removed.
	•	Trip duration and ride distance were calculated to eliminate potentially unreliable data.
	•	The Haversine formula was applied to determine the exact distance between start and end locations.
	•	Short and irrelevant trips, particularly those lasting under 10 seconds or covering no distance, were deleted to maintain the integrity of the dataset.

After cleaning, the data was analyzed using Tableau to generate visualizations that compare the usage patterns between the two groups. The insights gained will support the creation of a targeted marketing strategy aimed at converting casual riders into annual members, with the support of data visualizations to back up the key findings.

Goals:

The analysis aims to achieve the following:

	1.	Provide insights into the differences in bike usage between casual riders and annual members.
	2.	Identify behavioral trends that suggest why casual riders might consider switching to annual memberships.
	3.	Develop a data-driven marketing strategy that can be implemented through digital channels to maximize the conversion of casual riders into annual members.

By conducting a thorough analysis and offering actionable recommendations, the Cyclistic marketing team can take targeted steps to increase the number of annual memberships, ultimately improving customer retention and profitability.
