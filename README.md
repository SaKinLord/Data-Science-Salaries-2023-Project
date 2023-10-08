# Data-Science-Salaries-2023-Project

Data Science Salaries 2020-2023

Introduction:

This dataset appears to have been created to understand and analyze various factors influencing data science salaries, as well as to predict or estimate the salaries of individuals working in this profession. The data was likely collected by aggregating job postings from multiple websites. The primary purpose of this dataset is to provide valuable information about the factors that impact data science salaries. The dataset and the goal of prediction aim to assist job seekers looking to enter the field of data science. I intend to develop a machine learning model that predicts salaries in various data science roles based on factors such as experience, location, and job role, providing valuable insights to job seekers.

Dataset Description:

This dataset is a source containing information on the experience levels, salaries, and other relevant details of employees with different job positions and types of employment between the years 2020 and 2023. The dataset includes various features such as work year, experience level, employment type, job title, salary, salary currency, salary in USD, employee residence, remote work ratio, company location, and company size.

The dataset serves as a comprehensive data source that can be used to examine the relationships between employee salaries and experience levels, taking into account different job positions and company sizes in various countries. This dataset has the potential to support research and analysis in a range of topics, including data science, employment, and salary analysis.

Data Exploration and Cleaning:

Firstly, abbreviations in some columns of the dataset were converted to descriptive terms to enhance its understandability. These transformations improved the clarity of the dataset. For instance, "SE" was transformed to "Senior." Columns 'salary' and 'salary_currency,' which were not processed in this analysis, were removed from the dataset. Various visualizations were created to better understand the dataset. These visualizations displayed the distributions of categorical features such as experience levels, employment types, and company sizes. Salary distributions were analyzed using histograms and box plots. The distribution of remote work ratios was visualized as well.

Data Analysis:

The basic summary statistics of the dataset were calculated. These statistics provided results for important features such as work year, salary in USD, and remote work ratio, including:
For the work year, the mean is 2022.37, standard deviation is 0.69, with a minimum in 2020 and a maximum in 2023.
For salary in USD, the mean is $190,695, with a standard deviation of $671,676, ranging from a minimum of $6,000 to a maximum of $30,400,000.
Remote work ratio has a mean of approximately 46.27%, a standard deviation of 48.59%, with a minimum of 0% and a maximum of 100%.
Salary analysis in the dataset revealed that most salaries were concentrated between $100,000 and $200,000, but there were outliers in high-paying positions. Remote work ratios in the dataset showed that around 56% of employees worked remotely, 42% worked in the office, and 0.7% preferred a hybrid work arrangement.

Results and Insights:

The significant decrease in remote work options from 2020 to 2023 may be related to the easing of COVID-19-related restrictions. The dataset predominantly represents companies and employees residing in the United States. Average salaries increased significantly in medium and large-sized companies from 2020 to 2023, while small companies exhibited relatively stable average salary levels during the same period. The highest average salary is found in medium-sized companies. Full-time employment type has a higher expected average salary compared to others, likely due to significant differences in salary levels for senior positions.

In the modeling section, all three commonly used models did not perform well and required additional tuning or testing of different models.

Overall, this dataset provides valuable insights into data science salaries and the factors influencing them between 2020 and 2023, serving as a resource for both researchers and job seekers in the field.
