INFO370  
2/17/2017  
Final Project Proposal  
Team members: Huijie Guan, Amber Kim, Yutong Pan, Stacy Zeng

#Final Project Proposal
##Project Description

The purpose of our project is to provide supporting data, graphs, and evidence of the importance of youth tobacco usage to get attentions from parents, schools, organizations, and government. The results from the process of our data analyzation can potentially lead to regulations or programs carried out by the local government or organizations in the purpose of youth tobacco usage control and help.

The dataset we will be using is Youth Tobacco Survey (YTS) Data, which was conducted by Centers for Disease Control and Prevention yearly from 1998. However, the dataset we accessed through Data.gov, where CDC published it and made it publicly accessible, has only from 1999 to 2015. The dataset is fairly up-to-date, since the most recent update was a few days ago from today (1/16/17). The fact that there are some absent values in the dataset due to a small sample size makes it harder in the beginning of the analysis phase. Specific approaches toward it will be discussed in the following technical description section.

The main target audience of our project will be organizations that provide smoking cessation services. By knowing the youth behavior and attitude towards tobacco, the organizations will be able to carry out more effective programs or solutions to interfere and educate youth on tobacco usage. 

From our recourse, our targeted audience can learn:  

- The overall trend of youth tobacco usage from 1999 to 2015.  
- How the youth smoking users and trends differ geographically.  
- How the smoking status differs between males and females.  
- How the percentage of current smokers who want to quit varies throughout the years

##Technical Description

What will be the format of your final product (Shiny app, HTML page or slideshow compiled with KnitR, etc.)?

- Besides a formal paper structured in CHI style, we will publish a slideshow made by KnitR (beamer) online to grant public access to our analysis and result. We believe an Rmarkdown file will be the most efficient way to present our deliverable, given the time constraint and limited skills regarding other possible methods.  

Do you anticipate any specific data collection / data management challenges?  

- The original dataset we downloaded from data.gov is fairly large and disorganized, so it will be necessary to clean the dataset and make it analyzable based on the questions stated above that we are trying to answer.  

- Based on the format of our dataset, some skills using MS Excel to organize and manage data will be required, which could be one of the biggest challenges in the early phases of our project.  

What new technical skills will need to learn in order to complete your project?  

- We will need to learn a number of R packages, especially those related to showing trends geographically to complete that part of the project. We will also likely need to get a better understanding of R to most efficiently complete the project.  

How will you conduct you analysis? Please include a detailed description of your intended modeling approach.  

- Get data, clean data, separate data into test and use, create models from use data, test model on the test data and analyze fit.  

What major challenges do you anticipate?   

- The biggest challenge we anticipate is the selection of a proper modeling approach. 
- Determination of what proportion of the data to use for analysis.
- Figuring out what to do with the missing data from the small sample size. 
