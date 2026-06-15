# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

VISUALIZATION #2: Homeless deaths by cause
https://open.toronto.ca/dataset/deaths-of-people-experiencing-homelessness/
    > What software did you use to create your data visualization?
    I used Python with matplotlib and pandas libraries. The script is available in the jupyter notebook file.

    > Who is your intended audience? 
    The intended audience would be the City of Toronto policy staff, public health researchers, and non-profit advocates working on homelessness. The viz is designed to be interpretable without specialist statistical knowledge.

    > What information or message are you trying to convey with your visualization? 
    Acute Drug Toxicity is the dominant cause of homeless deaths in Toronto across all three years, far exceeding every other cause. Stratifying by year reveals two additional patterns: a notable decline in drug toxicity deaths in 2024, and a spike in 'Pendng' cases that year, suggesting classifications are still in progress. The chart makes it easy to compare each cause across years simultaneously.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I was mindful to ensure my visualization was aesthetically clean and clear, using a minimal grid and white background. I also ensured substantive accuracy by including exact counts per year as data labels, excluding suppressed cells. I also ensured perceptual clarity by using horizontal grouped bars that allows the audience to easily compare causes across years using length. Causes are also sorted by total deaths so the most critical causes appear at the top. The x-axis uses 10-unit intervals for additional reference to the data labels. Three colourblind-accessible colours from the online resource provided in class were used to distinguish years. 

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    The Python script is plain text and well annotated to ensure reproducibility. The script satisfies the FAIR principles discussed in our classes by explicitly noting data provenance and suppression conventions. 

    > How did you ensure that your data visualization is accessible?  
    Bar colours were selected carefully to ensure that it is colourblind-accessible. Data labels on every bar remove the need to estimate values from the axis. All axes are labelled and a legend identifies each year.

    > Who are the individuals and communities who might be impacted by your visualization?  
    People experiencing homelessness and their families are most directly represented. Advocacy groups, harm-reduction service providers, and City of Toronto departments may use this visualization to argue for drug toxication interventions. Framing drug toxicity as the dominant cause rather than an individual failure aligns with a structural rather than stigmatizing reading that was discussed in class.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Gender and age breakdowns were available in the dataset, but were excluded to maintain a single clear message about cause of death. Including all dimensions would have fragmented the chart into dozens of bars, increasing cognitive load. Rows with 'Suppressed' counts were dropped because they contain no numeric information. 

    > What ‘underwater labour’ contributed to your final data visualization product?
    Some work preceded the final visualization. Reading documentation to understand the suppression policy, deciding how to aggregate the multi-dimensional csv file without double-counting, and testing colour combinations. 

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
