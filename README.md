# HR Survey Analysis

## Situation
I've just been hired as a Human Resources (HR) Associate for the Seattle Department of Public Works

## The Assignment
The city recently surveyed ~1,500 public works employees to measure job satisfaction and identify opportunities to keep staff motivated and engaged. Please note: this project dataset was adapted from actual survey responses provided by the Pierce County, WA human resources department.

I've been asked to analyze the survey response data, and prepare a visual summary for the HR leadership team.

## The Objectives
1. Explore and profile the data to correct any quality issues
- Calculate the minimum, maximum, count, and number of blanks for each numerical field
- Remove any records with blank responses
- Remove any records containing duplicate values across all fields
- Calculate the count or frequency of each value in the `Department` and `Question` fields, and standardize any inconsistencies

2. Prepare and reformat the data for visualization
- Create a new tab named `Chart Source`, and generate a unique list of survey questions
- For each question, calculate the count of records associated with each response type (1-4) and the average response, excluding zeros
- Add new columns to conver the counts into percentages, based on the total responses for 1, 2, 3 or 4
- Copy and paste the data as values, then sort the questions descending by average response

3. Visualize the data and identify key insights and recommendations
- Visualize the percentages as a 100% stacked bar chart, showing the question with the highest average response at the top
- Update colors to shades of orange or red for negative responses (1,2), and shades of blue for positive responses (3,4)
- Add data labels and remove the x-axis, title and vertical gridlines, then format individual chart elements to improve readability
- Based on your findings, what insights or recommendations might you bring to the HR leadership team?
- BONUS: Modify the chart to vertically align the bars so that positive responses skew to the right and negative responses skew to the left (you’ll need calculated columns)

For survey question #10, how many respondents answered either 1 (strongly disagree) or 2 (disagree)?