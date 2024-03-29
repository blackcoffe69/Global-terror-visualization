# Global Terror Report

- This project presents a comprehensive analysis of global terrorism and its profound impact on human populations worldwide. The report meticulously examines the various ramifications, including the regions most affected by attacks, the types of weapons employed, the modes of attack, and the methods by which these acts of terrorism are executed.

# Data source
- The data is from a csv file containing details of the terorr attack over the period of years.
[Download Here](https://www.kaggle.com/code/gpreda/global-terrorist-attacks)

  # Introduction
- This project delves into the intricate landscape of global terrorism, driven by the imperative to monitor and analyze terrorist activities worldwide. Its core objective is to meticulously examine the multifaceted impact of terrorism on human lives and property. By scrutinizing factors such as the types of weapons utilized, preferred targets of attackers, peak periods of heightened attacks, the most affected regions, involved terrorist organizations, and casualty statistics, this endeavor seeks to provide invaluable insights into the complex phenomenon of terrorism.
  
#### The goal is to get insightful knowledge on the trend and activites of terrorist organisations accross the globe.

# Skills demonstrated for this project:

#### * Data cleaning
#### * Filter/tooltips
#### * Critical analysis
#### * Data visualition
#### * Problem solving

# Problem statement

#### - To know the effect of global terror on human lives
#### - To study the kind of weapon used over time
#### - To check the trend of the facilities that gets attack most
#### - To view the part of the world that is most affected by this terror

# Data Sourcing 

##### After critically defining the problem with global terror and what we seek to achive with this analysis,I obtained a xlsx file from kaggle.com and imported it into my Power Bi. I cleaned the data, and then performed my analysis and created visualizations to help answer my questions.

# Data transformation/cleaning

#### The csv file was downloaded from kaggle.com imported into Power Bi,the data was dirty so I proceeded to use Power Query in Power Bi Bi to visualize,analyze the data theregy perfoming some critical cleaning using the filter/tooltips.The data set contains 58 columns that needs to be analyzed,cleaned before proceeding to visualization.

<img width="919" alt="glb blanks 1" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/e19bbbef-a01e-4425-8044-8f8ad1bcf3c3">

This column contains null values that will greatly affect the outcome of the data set,so I had to convert it to 0 since it is not blank,so if the data is available for it later it can be inputed.

<img width="928" alt="glb dirty" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/49b24292-3997-42ac-b73a-a34b50350224">

During the cleaning process,I noticed the summary contains dates of attacks with some blank cells,I need to extract the date out since it is critical to the task to evaluate the date of the attacks. 

<img width="910" alt="split" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/d3b66947-a35d-4ab8-9f0e-ccc709cc8bd8">

This was done by using the split function by delimeter.The blank cells were removed using the filter tool by unchecking the box that creates an effect that applies to all the cells containing blank cells.

<img width="904" alt="glb date of attacks" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/3daf7e7a-3cc2-4014-acdc-b232ac9acb6a">

This is the result after spliting the date from the details about the attack,the column had to be named Date for easy identification.

<img width="928" alt="glb blanks" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/918bf367-b3c2-4385-bfdd-f7ea5da57762">

The provstate column also contain some blank column that was removed with the filter tools


# Data Modelling

#### No data modelling is required for this project.


# Analysis and Visualisation :


#### I choose to create simple and easy-to-understand visuals. To reflect the situation of global terror, I used their colors of red, white. These colors are also bold and eye-catching, which helps to make the visuals more memorable. I wanted to ensure that the visualization would be easily understood by anyone who viewed it, regardless of their level of expertise.


<img width="586" alt="count" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/7d1b001d-203a-4fbf-a4c4-d4cecd57f56f">

#### I created a silcer that contains all countries so that this will help when choosing each countries anyone can easily see the trends for every tables I created in project. Below it I gave a brief history of the global terror with the view of the year period from 1970 to 2015 which is what we are looking at in the data set provided. The total count of the country involved is 57 country,provided this using the card visualization tool. Total sum of attacks using card method also is 2210,Total number of people killed 468,total number of wounded people was 330 while nationalities targeted was 11k.

### Sum of Attack type:

<img width="724" alt="Sum of attack type" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/43b93047-dc65-45d3-8a7e-efe2c25b56cd">

1. Attack type 1, Sum of attack type by Bombing/Explosion was 129 and sum in a day was 709
2. Attack type 1,Sum of attack type by Armed assault was 24 and sum in a day was 158
3. Attack type 1,Sum of attack type by Unknown was 9 nd sum in a day was 14
4. Attack type 1, Sum of attack type by Assassination was 1 anad sum in a day was 14

### Sum of People Wounded in a Day :

<img width="670" alt="sum of nwounded in a day" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/75ff9897-22b5-47c2-ae67-99e3c8abc8f1">

. Within the space of 30 days in a month 24th has the highest number of people wounded 
. The 4th of the month comes up with no one wounded with value of 0

### Target type by Sum nationalities :

<img width="662" alt="Tagret type and sum of nationality" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/5a43ffb8-a31d-4c2f-8f64-af4b7f8f0203">

The treemap shows the target type with the nationalities involes:

1. Vehicle has a total of 1270 nationalities that were attacked in vehicle
2. Soldier has the lowest of nationalities attacked

### Total by month and year :

<img width="628" alt="Suicide by year" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/4f4be622-b727-4ad3-918e-04b23d7c91e0">

1. The year 2005 ranks the highest with the total number 310 suicide within the space of a month.
2. The year 1998 has the lowest with the total number of 32 within a month

<img width="214" alt="nu" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/a6c0cd38-82ad-4209-982f-8c7cc46e72b8">

 The next slide has the card for the total sum of property damaged 201 while 2210 is the total number of people wounded.
 
 ## Attackers nationality and Targets

<img width="657" alt="attackers nationality" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/947087d6-d300-456c-8cd2-8aa3f15d5f86">

Analysis of nationality attacks reveals significant disparities in the targets of terrorist activities. Vehicles emerge as the most frequently targeted, with a total of 1,270 nationalities affected. In stark contrast, soldiers experience the lowest incidence of attacks, with only four nationalities affected. This disparity underscores the varied tactics employed by terrorist groups and highlights the vulnerability of certain populations.

## Weapon type by year

<img width="665" alt="Weapon type by year" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/2c122f64-cee8-4b4f-aecb-37cb0508c45d">

Examining the weapon types used in terrorist attacks across different years provides valuable insights into the evolution of tactics. The year 199 ranks the highest in terms of the total number of weapons used, with six incidents recorded, affecting 238 individuals. This data underscores the dynamic nature of terrorist strategies and emphasizes the need for adaptive counterterrorism measures.

## Weapon by region

<img width="660" alt="weapon by region" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/5ea5fa32-361b-4b2f-bbd3-a095a5394949">

Regional analysis reveals significant variations in the prevalence of weapon types used in terrorist activities. South Asia emerges as the region with the highest weapon type use, with 37 incidents recorded, followed by the Middle East and North Africa with 10 incidents. Conversely, North America experiences the lowest incidence of weapon use, with only one recorded incident. These regional disparities highlight the complex geopolitical dynamics that contribute to the proliferation of terrorism.

## Target by city with count of attacks by  establishments

<img width="635" alt="Target by city" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/dec5e72f-31c0-4738-b14c-430c9b57b148">

Analysis of target locations sheds light on the geographic distribution of terrorist activities. Imphal city emerges as the most heavily targeted, with two establishments attacked in a single year. Additionally, Unknown city records 16 attacks with four incidents in a year, underscoring the challenges associated with identifying and preventing terrorist threats in certain regions.

## Sum of country by attack type

<img width="635" alt="Sum of country by attack type" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/e4334b23-9794-4d17-9132-c4a71645ffc5">

Pie chart analysis reveals the prevalence of different forms of terrorist attacks across countries. Bomb explosions are the most common means of attack, accounting for 71.93% of incidents and involving 7,611 nationalities. Armed assaults and bombings/explosions follow, with 19.3% and 3.51% of incidents, respectively. These findings highlight the diverse tactics employed by terrorist groups and the need for multifaceted counterterrorism strategies.


## Nationalities targeted most

<img width="636" alt="Nationalities targeted most" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/c98a17b5-e68a-4b0d-8738-12d2debea78b">

Analysis of nationalities targeted underscores the global nature of terrorism. International individuals bear the brunt of terrorist attacks, with a total of 5,064 nationalities affected. In contrast, Afghanistan records the lowest incidence of attacks, with only eight nationalities affected. These findings emphasize the need for international cooperation and solidarity in combating terrorism.


## Individual property targeted by suicide attacks

<img width="638" alt="Individual sucide target type" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/a428dbad-9288-418f-8d89-4f4d0d68f2a8">

Analysis of individual property targeted by suicide attacks reveals the diverse range of targets. Military installations experience the highest incidence of attacks, with 47 incidents recorded. Private citizens/property follow, with four incidents, while airports, businesses, educational institutions, government facilities, utilities, and violent political parties each record one incident. These findings highlight the indiscriminate nature of terrorist attacks and the importance of protecting critical infrastructure and civilian populations.

## Here are the dashboards:

<img width="621" alt="cpglb1" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/af9170ef-1945-49ef-b35d-7eb1f252332e">


<img width="621" alt="cpglb2" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/cfb72e26-b0e5-4fdf-ab07-f4c862239a02">

# Conclusion :
In conclusion, our analysis of global terrorism reveals the multifaceted nature of this complex phenomenon. By examining nationality attacks, weapon types, target locations, attack methods, and individual property targeted by suicide attacks, we gain valuable insights into the patterns and trends of terrorism. These insights can inform the development of effective counterterrorism strategies aimed at safeguarding lives and promoting peace and security worldwide. Addressing the root causes of terrorism and fostering international cooperation are essential steps in mitigating this persistent threat.
