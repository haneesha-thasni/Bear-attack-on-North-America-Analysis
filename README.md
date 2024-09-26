# Bear Attack in North America Analysis

This project focuses on analyzing bear attack incidents across North America. Using a dataset containing various features about the victims, types of attacks, and related information, the analysis provides insights into the frequency, causes, and trends of bear attacks over time.

![image](https://github.com/user-attachments/assets/91f80b3e-47c2-42b6-9347-61682db1f08d)

## Project Overview

The analysis aims to answer key questions regarding the distribution and trends of bear attacks by examining factors like gender, age, bear species, victim activities, and more. Visualizations have been generated to better understand the context and dynamics of these incidents.

## Dataset Features
The dataset used in this analysis contains the following columns:

* Name: The name of the individual involved in the bear attack.
* Age: The age of the person involved in the incident.
* Gender: The gender of the individual (Male/Female) involved in the attack.
* Date: The specific date on which the attack occurred (DD-MM-YYYY format).
* Month: The month during which the bear attack took place.
* Year: The year the bear attack happened.
* Type: The nature of the encounter or attack, such as provoked, unprovoked, etc.
* Location: The location (place, region, or area) where the bear attack occurred.
* Description: A brief description or summary of the incident and circumstances of the bear attack.
* Type of bear: The species of bear involved in the attack (e.g., Grizzly, Black Bear).
* Hunter: A binary indicator (Yes/No) showing if the individual was a hunter at the time of the attack.
* Grizzly: A binary indicator (Yes/No) indicating whether a grizzly bear was involved in the incident.
* Hikers: A binary indicator (Yes/No) showing if the individual(s) were hikers.
* Only one killed: A binary indicator (Yes/No) indicating if only one individual was killed in the attack.
* Latitude: The latitude coordinate of the location where the bear attack occurred.
* Longitude: The longitude coordinate of the location where the bear attack occurred.

## Information of the dataset

* Columns = 16
* Rows = 166
* Data types
   - Float = 3
   - integer = 5
   - object = 8
* No duplicated values
* Null values occur
  - age = 2
  - gender = 1
  - Latitude = 46
  - Longitude = 46

## Technologies Used
* Python: For data analysis and visualization.
* Pandas: To clean and manipulate the data.
* Matplotlib & Seaborn: For generating visualizations.
* Jupyter Notebook: To document the workflow and display the analysis.

## Key Sections of the Analysis
#### Gender and Age Distribution of Bear Attack Victims

* This section provides insights into which demographic groups (gender and age) are most affected by bear attacks.
*  Various charts are used to visualize the distribution of victims by gender and age.
#### Bear Attack Incidents: Wild vs. Captive

* Analyzing whether attacks occur in the wild or involve captive bears to determine risk levels in different environments.
#### Incident Trend over Time (Years/Months)

* A detailed investigation into how bear attacks have varied over time, with a focus on identifying any patterns across different years and months.
#### Bear Attacks on Hikers and Hunters by Month

* This section specifically examines the attacks on hikers and hunters, categorizing the data by the month of occurrence to identify seasonal trends in bear attack incidents.
#### Visualizing Bear Attack Intensity on Location

* The geographical distribution of bear attacks is visualized through maps, highlighting the most affected regions and areas.

## Key Insights
1) Demographic Analysis

* The majority of bear attack victims are male.
* Most victims fall in the middle-aged group, particularly between the ages of 20 and 50.
2) Bear Species & Attack Trends

* Brown bears are the most aggressive species, with more attacks compared to black bears. Polar bears account for the fewest attacks.
* There was a sharp increase in bear attacks starting around 1970.
* The years 1980, 2005, and 2018 had the highest number of incidents, with 1983, 1992, and 2014 also seeing elevated attack numbers.
3) Seasonal Patterns of Attacks

* Highest Incidents in August and July: The summer months of August and July experience the highest number of attacks, likely due to increased outdoor activities such as hiking and camping.
* Significant Incidents in September and October: These months also show high attack frequencies as bears prepare for hibernation.
* Lower Incidents in Winter and Early Spring: The months of December to March have significantly fewer attacks, aligning with the bear hibernation period.
4) Geographical Analysis

* Glacier National Park, Montana: This location has the highest intensity of incidents, averaging 10 attacks per month, signaling a need for heightened visitor safety and wildlife management.
* Yellowstone National Park, Wyoming: Moderate intensity with an average of 7 incidents per month, suggesting continued monitoring is necessary.
* Algonquin Provincial Park, Ontario: Although lower in intensity (5 incidents per month), it still represents a concern for park authorities and visitors.

## Suggessions

* Enhance safety practices and launch awareness campaigns, especially during the high-risk months of July through October.
* Boost awareness initiatives and educational programs in regions with higher bear attack rates.
* Introduce preventive safety measures during periods of increased bear activity.
* Investigate the causes behind the higher occurrence of incidents in specific areas.
* Create species-specific educational materials for park visitors and staff to raise safety awareness.
* Strengthen management protocols for captive bears to minimize the risk of attacks.
* Conduct more research into factors contributing to bear aggression and the frequency of human-bear encounters, both in the wild and in captivity.
* Improve Incident Reporting: Complete geolocation data (latitude and longitude) for bear attacks to track high-risk areas and improve monitoring.
* Real-Time Alerts: Set up alert systems in high-risk areas to warn about bear sightings and prevent encounters.
* Monitor Long-Term Trends: There’s been a rise in bear attacks since the 1970s. Investigating reasons like habitat loss and climate change could help develop preventive measures.
* Encourage the use of bear deterrents (bear spray, noise devices)






