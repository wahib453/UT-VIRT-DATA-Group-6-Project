# Particulate Matter and COVID-19 Outcomes

## Segment One Overview

### Purpose

In segment one we'll complete the following tasks:

- Select a topic, why we selected the topic, describe source of our data, and questions we hope to answer with the data
- Define roles between team members and establish a team communication structure
- Source a dataset, and begin to clean, organize, and perform exploratory data analysis
- Create mockups of a machine learning model, a database, and a firm grasp of how you want these different pieces to interact

## Result

1. ### Select a topic, why we selected the topic, describe source of our data, and questions we hope to answer with the data

- #### Selected topic: Particulate Matter and COVID-19 Outcomes

    Air pollution is a major public health concern due to its negative impact on individual and population health. A major component of air pollution is particulate matter - all the solid and liquid particles suspended in air. Particulate matter (PM) can enter the body through inhalation, and may negatively impact peoples' respiratory, cardiovascular, cardiopulmonary, and reproductive systems. The route of entry - and system affected - depends on the size, shape, and concentration or density of the particulate matter.

    ![ParticulateMatter](Resources/ParticulateMatter.jpg)

- #### Why we selected the topic?


Understand whther their is a relatonship between fine particles inhlaed and the number of hopitalizations and possible deaths that arise from covid-19 symptoms.

covid-19 has had an immense impact on the world's population. Early studies have shown that there is a positive correlation between air pollution and spread of COVID-19. Air pollution consists of particulates matter - a complex heterogeneous mixture of particles suspended in the air. Particulates matter exists in different sizes, shapes, and density and can act as a carrier through the aerosol, transmitting the virus and increasing its spread. Studies has also revealed that particulate matter of size 2.5 𝜇m (a.k.a fine particles) can reach the lower respiratory system and cause health issues.

understanding and extablishing a relation between envrionmental factors that exascerbate covid sysmptoms which then result to high number of deaths and possible deaths is 
COVID-19 has had an immense impact on the world's population. Understanding what exascerbates COVID-19 symptoms - contributes to COVID associated hospitalizations and deaths - is an important and fascinating area of study. Studies have shown that increased concentrations of fine particulate matter can cause elevated susceptibility to respiratory disease. Thus, may exascerbate the symptoms caused by COVID-19, and increase hospitalizations and deaths due to COVID-19.
This disease has had an immense impact on the world. . This is also a great opportunity to exercise the skills we've learned in our data analysis program.

### Description of the source of our data

Our data sources include:
*United State Environmental Protecton Agency (EPA)
*covidactnow.org

### The question we hope to Answer with the data

For our final project, we have chosen to create a machine learning model to assess the relationship between particulate matter 2.5 (atmospheric particulate matter with diameter less than 2.5 μm) and the clinical outcomes of COVID-19. The question we hope to answer is as follows: does increased concentrations of particulate matter contribute to an increase in the severity of COVID-19 symptoms, and lead to higher hospitalization and death rates?

## Work as a Team

As a virtual team, we share the same goal - but we have different obligations and responsibilities outside of this project. In order to reach our goal, we will communicate through Slack and work concurrently via Github. Group members are expected to meet on Monday and Wednesday nights, communicate regularly, do their best to acheive goals, and reach out if issues arise.

To help our team reach its goals for this segment of the project, we've assigned roles which are outlined below:

- Square: The team member in the square role will be responsible for the repository. (Ibrahim)

- Triangle: The member in the triangle role will create a mockup of a machine learning model. This can even be a diagram that explains how it will work concurrently with the rest of the project steps. (Robert)

- Circle: The member in the circle role will create a mockup of a database with a set of sample data, or even fabricated data. This will ensure the database will work seamlessly with the rest of the project. (Joe)

- X: The member in the X role will decide which technologies will be used for each step of the project. (Edgar)

## Machine Learning Model (see Covid_PM_Model.ipynb for basic script outline)

Present a provisional machine learning model that stands in for the final machine learning model and accomplishes the following:

- Takes in data from the provisional database
- Outputs label for input data

The basic procedure for implementing a supervised learning model is as follows: create a model, train the model, and then create predictions.

Our model will use logistic regression to predict a binary outcome - two possible outcomes. Our logistic regression will be able to decide, based on county level data, whether higher concentrations of PM 2.5 is associated with increased COVID-19 hospitalizations and deaths.

 We'll take the following steps to use a logistic regression model:

- Create a model with LogisticRegression().
- Train the model with model.fit().
- Make predictions with model.predict().
- Validate the model with accuracy_score().


## Database Integration
Pulling data from covidactnow.org and US EPA using following api:
- apidocs.covidactnow.org
- United States Evironmental Protection Agency
- - https://www.epa.gov/air-trends/air-quality-cities-and-counties


### Database Design

![](Resources/CovidProjectDatabaseDesign.png)


### Google Slides
https://docs.google.com/presentation/d/1QtQoBtW4AktTGot_MRScFSNJ2KotpPKPlfP7MPlIExM/edit?usp=sharing



