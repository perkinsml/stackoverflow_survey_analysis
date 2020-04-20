# Project Motivation
This project uses <a href='https://insights.stackoverflow.com/survey'>The Public 2019 Stack Overflow Developer Survey Results</a> to provide data-driven insights to some of the pressing questions I had when considering my career change into Data Science 2.5 years ago.

This analysis is based on the responses from survey participants identifying as a 'Data Scientist or Machine Learning specialist' and seeks to understand:
<ol>
    <li> The multi-faceted scope of the Data Scientist role</li>
    <li> Overall job satisfaction level</li>
    <li> How job satisfaction varies by organisation size and Manager confidence level</li>
    <li> The range of companies sizes employing Data Scientists</li>
    <li> Salary variations within and across countries</li>
    <li> The range and prevalence of programming languages applied by Data Scientists and how this relates to salary</li>
    <li> The drivers of job satisfaction</li>
</ol>

A short blog summarising the results of this analysis is available <a href='https://www.perkinsml.me/a-data-scientist-should-know'>here</a>.

# File Descriptions
The notebook contains the code required to understand, prepare and visualise the data to answer the questions listed above.  'Observations' sections within this notebook summarise my insights from the analysis.  All visualisations included in the blog are generated within this notebook.

2 CSV files downloaded directly from the <a href='https://insights.stackoverflow.com/survey'>Stack Overflow Annual Developer Survey page</a> contain the survey data used for this analysis:
<ol>
    <li>survey_results_public.7z - A compressed file with the CSV file with main survey results, one respondent per row and one column per answer</li>
    <li>survey_results_schema.csv - CSV file with survey schema, i.e., the questions that correspond to each column name</li>
</ol>

# Installation
There should be no libraries required to run the code in the notebook beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.\*   

The code was developed using Python version 3.7.6 and Pandas 1.0.1.

# Results
The main findings of the code can be found at the <b>'9 things every budding Data Scientist should know'</b> post <a href='https://www.perkinsml.me/a-data-scientist-should-know'>here</a>.

# Acknowledgment
A big thanks to Stack Overflow for managing the annual Developer survey and sharing the cleaned and anonymised results publicly.  You can find the Licensing for the data <a href='https://opendatacommons.org/licenses/odbl/1.0/'>here</a>. Otherwise, feel free to use the code here as you wish!
