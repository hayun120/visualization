# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

VISUALIZATION #1: Homeless deaths by month
https://open.toronto.ca/dataset/deaths-of-people-experiencing-homelessness/
    > What software did you use to create your data visualization?
    I used Microsoft Excel to create my data visualization. The line chart was built from the Homeless deaths by month.csv from the City of Toronto's Open Data Portal, with data organized in a pivot table and a chart inserted on the same sheet.

    > Who is your intended audience? 
    The general public and municipal decision-makers are the intended audience. A line chart is a familiar format and is easy to interpret at glance.

    > What information or message are you trying to convey with your visualization? 
    Homeless deaths in Toronto have declined year over year, but the seasonal pattern is uneven. Deaths peak in winter months (November - January) and again in summer (July), suggesting weather and seasonal service pressures both play a role.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    A colourblind-accessible palette was used to ensure accessibility and interpretability for all audiences. A line chart with markers is appropriate for continuous monthly data as it encodes temporal trend through slope, which viewers can read accurately. Both axes are labelled, a legend identifies each year, and a source note provides provenance.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Excel visualizations are less reproducible than python scripts because the chart is stored in a binary file rather than plain text. However, the source data table is visible in the same sheet, and the chart derives directly from it. There are no hidden transformations, and anyone with the CSV file and the workbook can verify the numbers.

    > How did you ensure that your data visualization is accessible?  
    Markers are added to each line so the series are distinguishable by shape in addition to colour. The y-axis starts at zero to avoid misleading comprehension of differences. A data label source note is included. Excel's built-in accessibility checker can add the alt-text: 'Line chart showing monthly homeless deaths in Toronto for 2022, 2023, and 2024. Deaths peak in winter and summer months. Across all years and months, there was a greatest decline in late 2024.'

    > Who are the individuals and communities who might be impacted by your visualization?  
    People experiencing homelessness are most affected by how their deaths are represented. Seasonal patterns visible in this chart could inform arguments for increased winter shelter capacity or summer cooling centres. However, if decontextualized, this visualization could be misused to minimize structural causes by attributing deaths to weather alone.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    This dataset did not show anything beyond death counts by month. Monthly granularity was retained rather than aggregating to quarters, because the month-level data reveals the seasonal pattern that is the key message of the visualization. A bar graph was considered but rejected because connecting lines make temporal trend easier to follow across 12 months for three series (years).

    > What ‘underwater labour’ contributed to your final data visualization product?
    Sorting months into calender order (the initial csv file was not sorted chronologically) and deciding how to handle the declining 2024 count (i.e. is this a representation of a true declining trend, or perhaps just a result of incomplete data collection?) required judgment that is invisible in the final visualization. The choice to keep 2024 data as is itself shapes how viewers read and interpret the declining trend. 

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-16`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * Two distinct data visualizations (for example, PNGs, PDFs, or screenshots)
        * Two Markdown files answering all questions for each visualization (including a link to your dataset in both files)
        * One Python file contains the complete code and visualization, and another file (with or without code) contains the visualization.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
