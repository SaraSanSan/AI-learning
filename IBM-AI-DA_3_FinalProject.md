# | Generative AI: Enhance your Data Analytics Career |

# < FINAL PROJECT & EXAM >

In this module, you will complete a guided practice project where you will use a real-world data set and practice generative AI to generate Python codes that can perform data preparation, analysis, visualization and dashboarding. In addition, you will attempt a final graded exam designed to evaluate your understanding of generative AI.

Learning Objectives:

    Practice tasks such as data preparation, analysis, visualization, and dashboarding using an existing data set.
    Test your knowledge of generative AI and its techniques by attempting a final graded exam.


# Guided Practice Project Overview

In this practice project, you will use a real-world data set and practice generative AI to generate Python codes that can perform data preparation, analysis, visualization and dashboarding.

### Project Scenario

You have been employed as a data analyst by a Healthcare consultancy firm which has been conducting a survey on the state of global happiness annually. The World Happiness Report offers valuable insights into factors influencing happiness across countries. The firm wants you to produce a report to find out whether there are demographic, regional, and/or economic characteristics that lead to a better life.

- About the data set:

The World Happiness Report is a landmark survey of the state of global happiness. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness. This is a public dataset available on the Kaggle website as World Happiness Report under the CC0: Public Domain license.

For this guided practice project, you will work on the year 2016 data, which has been slightly modified for the purpose of this guided practice project.

Hold down the Ctrl key while you click to download it from here: 2016 data

Attributes of this dataset have been explained below:

    Variable: Description

    Country: Name of the country
    Region: Region the country belongs to
    Happiness Rank: Rank of the country based on the Happiness Score
    Happiness Score: A metric measured in 2016 by asking the sampled people the question: "How would you rate your happiness?"
    Lower Confidence Interval: Lower confidence interval of the Happiness Score
    Upper Confidence Interval: Upper confidence interval of the Happiness Score
    Economy (GDP per Capita): The extent to which GDP contributes to the calculation of the Happiness Score
    Family: The extent to which family contributes to the calculation of the Happiness Score
    Health (Life Expectancy): The extent to which life expectancy contributes to the calculation of the Happiness Score
    Freedom: The extent to which freedom contributes to the calculation of the Happiness Score
    Trust (Government Corruption): The extent to which trust contributes to the calculation of the Happiness Score
    Generosity: The extent to which generosity contributes to the calculation of the Happiness Score
    Dystopia Residual: Dystopia is an imaginary country that has the world's least-happy people. The residuals, or unexplained components, differ for each country, reflecting the extent to which the six variables either over- or under-explain average 2014-2016 life evaluations. These residuals have an average value of approximately zero over the whole set of countries.

### Tasks in the project

The project tasks are data preparation, analysis, visualization, and dashboarding. Based on the data set, you must write prompts to generate the Python codes for performing specific tasks. You can access a JupyterLite-based testing environment to test the generated codes using the Generative AI classroom prompts.

The tasks assigned to you are as follows:

- There might be a few missing values in the dataset. Data cleaning will be a part of the assignment.

- You have to perform exploratory data analysis to draw keen insights on the data:

  1. Identify the GDP per capita and Healthy Life Expectancy of the top 10 countries.and represent it as a bar chart.
  2. Find the correlation between the Economy (GDP per Capita), Family, Health (Life Expectancy), Freedom, Trust (Government Corruption), Generosity, and Happiness Score.
  3. Create a scatter plot to identify the effect of GDP per Capita on Happiness Score in various Regions.
  4. Create a pie chart to present Happiness Score by region.
  5. Create a map to display GDP per capita of countries and include Healthy Life Expectancy as a tooltip.

- Create a dashboard with at least four of the above visualizations.

- Generate the narrative to present the dashboard.


# Hands-on Lab: Guided Practice Project

## Project Scenario

You decide to use Generative AI to create python codes that can help you analyze the data, determine the best features and create the visualization as per requirement.

To test the prompt-generated code, open the Jupyter Notebook that you have been provided with in the succeeding lab in the course.

The data set for this lab is available in the following URL.

URL = "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-AI0272EN-SkillsNetwork/labs/dataset/2016.csv"

## Importing the Dataset

You can begin by using the Generative AI model to create a python script that can load the dataset to a pandas dataframe. The dataset file already has the headers in the first row.

    Write a Python code that can perform the following tasks:
    1. Read the CSV file, located on a given file path, into a pandas data frame, assuming that the first row of the file can be used as the headers for the data.
    2. Print the first 5 rows of the dataframe to verify correct loading.

## Data Preparation

### Data Cleaning - Checking for correct data types

You need to check the columns in the dataset for the right data type. If the data type is not appropriate, it may lead to misinterpretation of the data. Write a prompt that performs the following tasks:

1. List the data types of the columns and check if there is any column type that is unsuitable.

        Write a python code that performs the following tasks:
        1. Check the data types of the columns and see if it correct.


### Data Cleaning - Change the data types

1. Change the data type to an appropriate type.

        Write a python code to do the following tasks as per latest pandas:
        1. Remove leading and trailing whitespaces from the values in a column.
        2. Clean a column in a DataFrame by replacing empty strings with NaN values.
        3. Change the data type of the columns to appropriate type as per the latest version of pandas.

_Please note as of the future version 3 of pandas it is recommended to use " df.method({col: value}, inplace=True) " instead of " df[col].method(value, inplace=True) ". You may see warning message in this regard, when you generate code and execute it in the notebook._


### Data Cleaning - Checking for missing values

At this stage, you need to clean up the data. As has been shared earlier, the data may have missing values. Write a prompt that performs the following tasks:

1. Identify the columns with missing values and fill the blank cells with mean value of the columns.

    _Please ensure that you have changed all the column to the appropriate data type before you do this._

        Write a python code that performs the following tasks as per latest pandas:
        1. Identify the columns of a data frame with missing values.
        2. Replace the missing values thus identified with mean values of the column.


## Data Insights and Visualization

Write prompts that generate codes to perform the following actions:

1. Identify the GDP per capita and Healthy Life Expectancy of the top 10 countries.

        Write a python code that identifies the GDP per capita and Healthy Life Expectancy of the top 10 countries and create a bar chart named fig1 to show the GDP per capita and Healthy Life Expectancy of these top 10 countries using plotly.

2. Find the correlation between the Economy (GDP per Capita), Family, Health (Life Expectancy), Freedom, Trust (Government Corruption), Generosity and Happiness score. You may like to represent the correlation as a heatmap of a readable, visually appealing size.

        Write a python code that performs the following actions:
        1. Create a sub-dataset including Economy (GDP per Capita), Family, Health (Life Expectancy), Freedom, Trust (Government Corruption), Generosity, and Happiness Score attributes from the dataframe (df).
        2. Find the correlation between the attributes in the subdataset as a heatmap named fig2 using Plotly of width 800 and height 600.

3. Create a scatter plot to identify the effect of GDP per Capita on Happiness Score in various Regions. Use plotly for creating the plot.

        Write a code that creates a scatter plot named fig3 between Happiness Score and GDP per Capita attributes of a dataframe using Plotly. Use Region to color the data points on the scatter plot.

4. Create a pie chart to present Happiness Score by Regions

        Write a Plotly code that creates a pie chart named fig4 to present Happiness Score by Region attributes of dataframe df.

5. Create a map to display GDP per capita of countries and include Healthy life expectancy to be shown as a tooltip

        Write a Plotly code that creates a map named fig5 to display GDP per capita of countries and include Healthy Life Expectancy to be shown as a tooltip.


## Dashboarding and Storytelling

1. Write prompts that generate codes to write at least four of the graph plots generated in the previous steps into a HTML page.

        Write Python code to write any four of the Plotly figures (fig1, fig2, fig3, fig4, fig5) to a single HTML file named “dashboard.html”

_NOTE: Please ensure that the code has the plotly codes generated for creating various visualizations in the previous section._

2. Generate the narrative to present the dashboard

       Generate a narrative to present the dashboard on world happiness report with the following charts:-
        1. A heatmap showing correlation
        2. A scatter plot to identify the effect of GDP per Capita on Happiness Score in various Regions
        3. A pie chart to present Happiness score by Regions
        4. A map to display `GDP per capita` of `countries` and include `Healthy Life Expectancy` to be shown as a tooltip

You can use this narrative to showcase your dashboard in a business meeting!


## CONCLUSION

Congratulations! You have completed this guided project on using Generative AI for different data analytics tasks.

By the end of this project, you are now capable of using Generative AI for the tasks of:

    Data preparation
    Data analysis
    Dashboarding
    Storytelling



# Enhancing Your Data Analyst Career with Generative AI 

It's time to reflect on your learning journey.
You've delved into the integration of generative AI in the data analytics domain
over the past few weeks.
Through demonstrations, lessons, and labs, you've learned how to use various
generative AI models and platforms to improve the timeliness and
effectiveness of processes throughout the data analytics lifecycle.
Anaconda, an open-source AI and data science platform,
regularly surveys its users.
Its 2022 online survey, state of data science, conducted from April to May,
surveyed 3,493 individuals from 133 countries and regions.
Anaconda's most recent 2023 survey included 2,414
individuals representing 126 countries.
These respondents reported that data preparation, cleaning, and
visualization remained the most time-consuming tasks.
Not so surprisingly, on the question, how do data scientists spend their time?
2022 survey respondents reported spending about 37.75% of their
time on data preparation and
cleaning more than one-third of their total data analytics efforts.
Using generative AI abilities data analysts can boost their productivity and
efficiency by automating repetitive tasks, including processing and cleaning data,
identifying missing values, normalizing data, standardizing data,
organizing data for analysis, or selecting data for training models.
The number of organizations using AI grew to 40%, with respondents reporting that
their companies use internal generative AI tools like LLMs.
In 2023, 63% of data science practitioners are using generative
AI tools with the same frequency or more compared to 2022.
They use generative AI primarily for content creation, data cleaning,
visualization, and analysis.
Generative AI speeds statistical analysis you can use generative AI to develop code
in the programming language of your choice, which you can implement for
data cleaning and data analysis.
Additionally, if you lack sufficient data, you can use
generative AI to quickly create synthetic data sets that mimic real-world data.
Furthermore, in the 2022 Anaconda survey, data practitioners reported
spending 12.99% of their time creating data visualizations and
6.2% of their time creating reports and presentations.
Generative AI can enhance data exploration by suggesting insights,
generating reports, and saving valuable time.
Most 2023 survey respondents also indicated concerns about the ethics and
sustainability of generative AI.
When employing AI models work to minimize bias and to produce transparent and
easy-to-understand outcomes.
Recognize and deal with the ethical issues raised by generative AI,
such as fairness and data privacy.
Survey respondents also expressed their concerns about job loss and
the talent landscape.
Generative AI provides excellent potential for
data analysts to transform their profession.
To maintain and enhance your data analyst career,
you must keep up with rapidly evolving generative AI technologies.
You'll not only enhance your capabilities and productivity, but you'll also be
capable of helping your organization reach goals using optimal work efforts.
You are now equipped with the necessary skills and
knowledge to effectively use generative AI tools for data generation, augmentation,
analytics, and data preparation.
You know how to use generative AI to query databases and
apply Q and A models to various data analytics applications.
And you know how to use generative AI to derive actionable insights,
create visually compelling data presentations, and
construct informative interactive dashboards.
Applying these skills will demonstrate greater effectiveness, perception,
and adaptability and boost your standings in the fast-paced field of data analytics.
So cheers to the next chapter of your analytical adventure.
May the data always be illuminating and discoveries abundant.
Thank you for finishing this course and
good luck with all of your upcoming data-related pursuits.
