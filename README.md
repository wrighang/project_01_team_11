# Project One: Team Eleven
Behavioral Impact of Social Media Usage on Productivity and Engagement

# Deliverable(s)
Dataset Used: ['Time Wasters on Social Media' dataset](https://www.kaggle.com/datasets/muhammadroshaanriaz/time-wasters-on-social-media)<br>
[Project Combined Team Python Notebook](https://github.com/DWallace740/team_11project1/blob/main/Team_Eleven_Behavioral_Study.ipynb)<br>
[Cleaned CSV file](https://github.com/DWallace740/team_11project1/blob/main/data/Cleaned_dataset.csv)<br>
[Project PowerPoint Presentation](https://github.com/DWallace740/team_11project1/blob/25f8adc8d2b8070d8fa7bfac72ba2dd5ba0a951a/Team%2011%20Project%201.pdf)<br>

## Table of Contents 
1. `Project Overview`
2. `Project Ideation`
3. `Data Collection & API Integration`
4. `Data Cleanup & Preparation`
5. `Analysis & Methodology`
6. `Visualizations`
7. `Findings & Conclusion`
8. `Future Work & Improvements`
9. `Setup & Usage Instructions`
10. `Contributors`
11. `Coding Process`

# 1. `Project Overview`
## Description
This project investigates the behavioral impact of social media usage, with a focus on how different factors such as device type, location, profession, and engagement levels influence productivity and social media addiction. By analyzing data related to user habits on various devices, locations, and professions, we aim to uncover insights into how specific behaviors and patterns contribute to productivity loss and social media addiction.

## Project Goals & Objectives
The primary goal is to analyze user data to identify patterns that could help explain the behavioral impact of social media usage. Specifically, we aim to understand how location, device type, profession, engagement levels and scroll rate contribute to addiction levels and productivity loss. Each question brings a different dimension to this analysis, helping us build a comprehensive understanding of the behavioral impacts of social media.
This project investigates the behavioral impact of social media usage, with a focus on how different factors such as device type, location, profession, and engagement levels influence productivity and social media addiction. By analyzing data related to user habits on various devices, locations, and professions, we aim to uncover insights into how specific behaviors and patterns contribute to productivity loss and social media addiction.

# 2. `Project Ideation`
## Why This Topic Was Chosen
As a team, we were interested in understanding the effects of social media on daily productivity, especially since social media has become an integral part of both personal and professional life. We wanted to explore the factors that contribute to social media addiction and productivity loss, as this could provide valuable insights for individuals looking to manage their time better and organizations aiming to enhance workplace productivity. Each team member contributed a unique perspective on the broader question of how social media impacts behavior, resulting in a multifaceted approach to the topic.

# 3. `Data Collection & API Integration`
## Summary 
The data collection and integration process focused on identifying a dataset that aligned with the `project goals` and setting up an efficient API connection.

## Initial Data Source Considered
The 'Mobile Device Usage and User Behavior' dataset was first explored on Kaggle, but it lacked the detailed geographic data required for the analysis.

## Final Dataset Selection
The 'Time Wasters on Social Media' dataset was chosen, as it provided more comprehensive geographic and behavioral data. This dataset aligned with the goal of studying regional differences in mobile and social media usage.

## API Integration
To retrieve the data, a Kaggle account was created, a token was set up, `Kagglehub` was installed in the development environment, and the necessary code was added to the Python notebook to authenticate directly within the notebook.

# 4. `Data Cleanup & Preparation`
## Addressing Inconsistencies  
Typos were corrected and column names were standardized for clarity (e.g., 'Barzil' to 'Brazil' and 'DeviceType' to 'Device Type'). Unnecessary columns, such as indexed columns, were removed to streamline the dataset.

## Handling Missing Values and Duplicates
Null values were checked for and duplicate entries were removed to ensure data accuracy and prevent skewed results.

## Outlier Review 
Extreme values were assessed, and no significant outliers required removal, as the data generally fell within realistic ranges.

## Creating New Variables
A "Time Spent" category column to group users into time spent ranges (e.g., "0-50," "50-100") to allow for more insightful analysis of productivity loss across different usage levels.

## Reproducibility and Documentation
All data cleaning steps were documented in the README file, and a `data` folder was created to store the cleaned CSV file.

# 5. `Analysis & Methodology`
## Summary
The analysis combined correlation analysis and summary statistics to explore patterns in the data and address the research questions.

To ensure a cohesive approach, device type was used as a central theme, with a variety of visualizations examining the behavioral impacts of social media usage. Each question was represented with specific charts that highlighted different aspects of the data.
 
 ## Key Challenges 
- Balancing high engagement values against lower scroll rate values required careful visualization choices to ensure clarity.
- Data imbalance, with certain regions (like India) having more participants, introduced potential skew in some of the analyses.
- Some data points lacked consistent measurement units, which posed additional formatting challenges.

# 6. `Visualizations`
## Visuals and Key Insights:
- Scatter Plot: Showed consistent productivity loss across device types, regardless of time spent.
- Facet Grid Bar Charts: Revealed that smartphones have slightly higher productivity loss, with minimal impact from time spent.
- Box Plot: Displayed the variability in productivity loss, with smartphones showing higher and more variable loss.
- Pie Chart: Highlighted that smartphones account for 59.4% of total productivity loss.
- Bar Charts:   
    - By Location: Showed that smartphones have higher productivity loss in most regions.
    - By Profession: Found that lower-wage professions experience higher productivity loss, especially with smartphones.
## Visual Tools:
- Libraries Used: Matplotlib and Seaborn for all visualizations.
- Formatting: Consistent labels, color coding, and thoughtful legend placement improved clarity.

# 7. `Findings & Conclusion`
## Summary 
The analysis yielded several key findings regarding the impact of device type on productivity loss and its relationship to behavioral factors in social media usage.

## Support for Initial Hypotheses:
- Device Impact Hypothesis: The findings support the hypothesis that device type impacts productivity loss, with smartphones having a more significant negative effect.

- Behavioral Factors: The results indicate that while time spent does not drastically change productivity loss, other factors like profession and location do play a role.

## Addressing Research Questions:
    - Does the Type of Device Impact Productivity Loss?
Yes, smartphones lead to higher productivity loss compared to computers and tablets.

    - Are Addiction Levels Higher in Certain Locations?
Although not the primary focus, the data suggests higher productivity loss in certain locations, which could correlate with addiction levels.

    - Is There a Relationship Between Profession and Device Type?
Yes, certain professions show a preference for device types that are associated with higher productivity loss.

    - Is There a Relationship Between Scroll Rate and Engagement Level?
Due to data limitations, this question was challenging to answer definitively, but initial analysis indicates a potential correlation that requires further investigation.

## Real-World Implications:
- Individual Productivity Management: Users might consider limiting smartphone usage to mitigate productivity loss.

- Workplace Policies: Employers could develop strategies to manage device usage during work hours, especially in professions more prone to productivity loss.

- App Development: Developers might design apps with features that help reduce distraction and promote productive use.
The analysis yielded several key findings regarding the impact of device type on productivity loss and its relationship to behavioral factors in social media usage.

# 8. `Future Work & Improvements`
## Summary 
The analysis revealed useful insights but also highlighted areas for improvement and further exploration.

## Limitations:
- Data Imbalance: Some regions had more participants, which may skew results.
- Measurement Units: Inconsistent units made some data harder to interpret.
- Data Skewness: Outliers and uneven distributions may have influenced results.

## Potential Improvements:
- Additional Data: More datasets would provide a balanced view and strengthen findings.
- Standardized Data: Consistent measurement units across all variables would improve clarity.
- Behavioral Analysis: Further exploration of age, gender, and specific app usage could add depth.

## Next Steps:
- Machine Learning: Use predictive models to identify users at risk of productivity loss.
- Longitudinal Studies: Study data over time to track changes in device usage and productivity.
- Cross-Cultural Analysis: Examine how cultural factors influence device usage.

## New Questions:
- How does specific app usage (e.g., social media vs. productivity apps) impact productivity?
- Does notification frequency affect productivity?
- Can app limits or usage tracking reduce productivity loss?

# 9. `Setup & Usage Instructions`
## Summary
To replicate the analysis or explore the data independently, please follow the instructions below.

## Prerequisites:
    - Python 3.7+
    - Jupyter Notebook or Visual Studio Code with Python and Jupyter extensions

1. Clone [Repository](https://github.com/DWallace740/team_11project1.git)
2. Create Conda Environment
3. Install Requirements 
    - pip install kagglehub 
    - pip install seaborn
4. Navigate Project Files
    - data folder 
    - [Cleaned CSV file](https://github.com/DWallace740/team_11project1/blob/main/data/Cleaned_dataset.csv) (The cleaned dataset ready for analysis)
    - gitignore
    - [README.md](https://github.com/DWallace740/team_11project1/blob/main/README.md) (Provides an overview of the project, methodology, findings, and instructions.)
    - [Project Combined Team Python Notebook](https://github.com/DWallace740/team_11project1/blob/25f8adc8d2b8070d8fa7bfac72ba2dd5ba0a951a/Team_Eleven_Behavioral_Study.ipynb) (Notebook containing the final analysis code and visualizations)
    - [Project PowerPoint Presentation](https://github.com/DWallace740/team_11project1/blob/25f8adc8d2b8070d8fa7bfac72ba2dd5ba0a951a/Team%2011%20Project%201.pdf) (Presentation Slides reviewing project questions and overall summary analysis)
5. Run Notebook 

- Notes:
    - No additional data fetching is required as the dataset is included in the repository.
    - Ensure that your working directory is set to the project root to avoid file path issues.

# 10. `Contributors`
## Angelina Wright
Contributions: Actively involved in data collection and API integration, data cleaning and preprocessing, and visualization creation. Angelina also contributed to documentation, including the README, and managed version control to ensure seamless collaboration. Angelina worked on slides and code focused on the first two research questions, ensuring they aligned with the overall project goals.

## Cameron Magor
Contributions:  Collaborated on data cleaning and preparation, setting up the initial codebase, and performing quality checks such as handling null values and duplicates. Cameron also supported the team by assisting with merge conflicts, ensuring everyone’s contributions were effectively integrated. Cameron focused on the third research question, editing slides and code to reflect key insights.

## Daena Wallace
Contributions: Played a key role in project ideation and coordination, helping to shape the direction of the analysis. Daena was involved in updating project documentation, contributed to the analysis and interpretation of results, and structured and refined the presentation slides. Daena worked on the final research question, editing related slides and code for clarity and consistency with the project’s findings.

Each team member contributed to all major areas—including data preparation, analysis, visualizations, and documentation—and edited their own slides and code based on the research questions they addressed. By collaborating closely, we ensured that each part of the project reflected the combined expertise and input of the entire team. This collective effort was essential in delivering a cohesive and thorough final product.

====================================================================

# 11. `Coding Process`

The course activites and following lines of code was referenced/obtained from Xpert Learning Assistant/Chat GPT:

## Chat GPT:

- Facet Grid for Grouped Data: Recommendations to use Seaborn's `FacetGrid` and `barplot` for displaying grouped relationships, such as productivity loss by device type and time spent.

### Defining time spent categories

darkside_df['TimeSpentCategory'] = pd.cut(darkside_df['Total Time Spent'], bins=[0, 50, 100, 150, 200, 250], labels=['0-50', '50-100', '100-150', '150-200', '200-250'])

### Creating a FacetGrid with bar plots for each time spent category

g = sns.FacetGrid(darkside_df, col="TimeSpentCategory", height=4, aspect=0.8)

g.map(sns.barplot, "Device Type", "ProductivityLoss", order=['Smartphone', 'Computer', 'Tablet'])

g.set_axis_labels("Device Type", "Average Productivity Loss")

g.set_titles("Time Spent: {col_name}")

plt.suptitle("Average Productivity Loss by Device Type and Time Spent Category", y=1.05)

### Added median value labels to a box plot for displaying central tendency in productivity loss by device type, enhancing interpretability without overcrowding the plot.

### Calculate the median values and add as labels

medians = darkside_df.groupby(['Device Type'])['ProductivityLoss'].median().values

positions = range(len(medians))
for pos, median in zip(positions, medians):
    plt.text(pos, median, f'{median:.2f}', ha='center', va='center', color='black', fontweight='bold') (edited) 

### Scatter Plot Structure: The use of Seaborn's `sns.scatterplot` to display relationships between device type, connection type and productivity loss, with varying point sizes and hues.

device_connection_productivity = darkside_df.groupby(['Device Type', 'Connection Type'])['ProductivityLoss'].mean()

mean_productivity_loss = device_connection_productivity.mean()

device_connection_productivity = device_connection_productivity.reset_index()

sns.scatterplot(data=device_connection_productivity, x='Device Type', y='ProductivityLoss', hue='Connection Type', style='Connection Type', s=200)

plt.axhline(y=mean_productivity_loss, color='red', linestyle='--', linewidth=1.5, label=f'Average Productivity Loss ({mean_productivity_loss:.2f})')

## Xpert Learning Assistant:

mobile_usage_df.isna().sum()

mobile_usage_df[mobile_usage_df.duplicated()]

device_avg_scroll_rate = cleaned_dataset_df.groupby('Device Type')['Scroll Rate'].mean().round(1)

ax = device_avg_scroll_rate.plot(kind='bar', color='blue', stacked=True)

for container in ax.containers:
    ax.bar_label(container, label_type='edge', fmt='%.0f')

avg_df = pd.DataFrame({'Device Type': device_avg_scroll_rate.index,
                        'Average Scroll Rate': device_avg_scroll_rate,
                       'Average Engagement Level': device_engagement_lvl
                       })

avg_df.set_index('Device Type', inplace=True)

plt.annotate(line_eq, (0.2, 0.1), fontsize=22, color='red', xycoords='axes fraction', ha='center')

facet_scatter = sns.FacetGrid(avg_df2, col='Device_Type', hue='Device_Type', height=4, aspect=1)

facet_scatter.set_titles(col_template='{col_name} Device')
