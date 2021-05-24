# UT-VIRT-DATA-Group-6-Project

### Segment Overview
In segment one we'll complete the following tasks:
- Create the foundation for the final project and - importantly - decide on a topic/question that can be answered using data
- Define roles between team members and establish a team communication structure
- Source a dataset, and begin to clean, organize, and perform exploratory data analysis
- Create mockups of a machine learning model, a database, and a firm grasp of how you want these different pieces to interact

### Introduction
For our final project, we'll source a dataset from the US Census Bureau API. This dataset will include individual demographic information - such as age, gender and race - as well as education level and salary. Our machine learning model will predict whether an individual is likely to earn a yearly income below a certain threshold. 

### Project Objective
Health, education and income - among numerous other factors - influence quality of life. Our goal is to create a model that will allow users to see if their income is likely to be below the yearly threshold. For individuals who are interested, we'll also provide resources to help them reach their career and life goals.

![](HealthyPeopleGraphic.png)

## Work as a Team
As a virtual team, we share the same goal - but we have different obligations and responsibilities outside of this project. In order to reach our goal, we will communicate through Slack and work concurrently via Github. Group members are expected to meet on Monday and Wednesday nights, communicate regularly, do their best to acheive goals, and reach out if issues arise.

T help our team reach our goal for this segment of the project, we've assigned roles which are outlined below:
- Square: The team member in the square role will be responsible for the repository. (Ibrahim)

- Triangle: The member in the triangle role will create a mockup of a machine learning model. This can even be a diagram that explains how it will work concurrently with the rest of the project steps. (Edgar/Robert)

- Circle: The member in the circle role will create a mockup of a database with a set of sample data, or even fabricated data. This will ensure the database will work seamlessly with the rest of the project. (Joe)

- X: The member in the X role will decide which technologies will be used for each step of the project. (Edgar/Robert)

## Machine Learning Model
Team members will be expected to present a provisional machine learning model that stands in for the final machine learning model and accomplishes the following:

- Takes in data from the provisional database
- Outputs label for input data

## Database Integration
Pulling data from census.gov using following api:
- ACS (American Community Service) API (Possible dataset)
- PEP (Population Estimates and Projections 2010-2019) API
- - https://api.census.gov/data/2019/pep/charagegroups?get=NAME,POP,RACE,SEX,AGEGROUP&for=state:*
- PSEO (Post-Secondary Employment Outcomes) API
- - https://api.census.gov/data/timeseries/pseo/earnings?get=Y1_P50_EARNINGS,Y1_P25_EARNINGS,Y1_P75_EARNINGS,Y1_GRADS_EARN,Y5_P50_EARNINGS,Y5_P25_EARNINGS,Y5_P75_EARNINGS,Y5_GRADS_EARN,Y10_P50_EARNINGS,Y10_P25_EARNINGS,Y10_P75_EARNINGS,Y10_GRADS_EARN,Y1_IPEDS_COUNT,Y5_IPEDS_COUNT,Y10_IPEDS_COUNT,INSTITUTION,INST_STATE,DEGREE_LEVEL,CIP_LEVEL,CIPCODE,GRAD_COHORT

### Database Design

![](QuickDBD-export.svg)



