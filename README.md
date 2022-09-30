# stackoverflow_survey_2017

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

All relevant modules, versions and dependencies can be found in the 
poetry.lock and pyproject.toml

## Project Motivation<a name="motivation"></a>

I was interested in using Stack Overflow survey data from 2017 to 
answer the following questions:

1. Which countries show the highest and lowest job and career satisfaction?
2. What are the most and least important factors when assessing a potential 
job?
3. Which of these features are correlated?


## File Descriptions <a name="files"></a>

The project is structured using two folders:
1. src: contains a jupyter notebook nb_analysis.ipynb that contains the 
detailed survey analysis.
2. data: contains two csv files: survey_results_public.csv (survey results) 
and survey_results_schema.csv (survey schema, i.e., the questions that 
correspond to each column name)


## Results<a name="results"></a>

1. The five countries with the lowest overall job and career satisfaction 
are in East and Southeast Asia. The five countries with the highest overall 
satisfaction, are located in Latin America, Europe, and the Middle East. 
Another phenomenon is that career satisfaction is higher than job satisfaction
in all ten countries.
2. Despite an increasing preference for work-life balance, potential job 
applicants value compensation and professional development. However, the 
amount of time spent commuting is also important to potential applicants. 
Languages, frameworks, and other technologies with which the developer will 
be working, as well as how projects are managed at the company or organization
, have a similar, albeit less significant, distribution.
3. Over all feature pairs, the mean correlation coefficient is 0.21, while the
minimum correlation coefficient is 0.02. This already suggests that the 
majority of the features have some positive linear relationships and that 
there are no feature pairs where a higher importance for one feature goes 
along with a lower importance for the other.
Furthermore, some feature pairings have a substantially stronger correlation 
than others, such as the importance of a given industry and department, or 
the industry and influence of the company's product, or financial performance
and senior leaders' reputations.

The main findings of the code can also be found at the post available [here](https://medium.com/@gianluca.manca89/is-your-company-ready-for-a-competitive-labor-market-d6aa75aa03b8).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Code is under MIT licens (see file). Data licensing can be found [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).  