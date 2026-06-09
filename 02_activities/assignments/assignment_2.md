# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad): 
    GOOD visualization
    NewYork Airbnb Traveller Guide (Sahil Lodhi)
    https://public.tableau.com/app/profile/sahil.lodhi/viz/NewYorkAirbnbTravellerGuide/HomePage
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      This visualization is a dashboard that presents an overview of New York City's Airbnb market through various charts, including a horizontal bar chart comparing listings by neighbourhood, a donut chart for room type distribution, a geographic dot map showing the density of Airbnb listings available by location, and KPI cards showing summary metrics.

      1. Aesthetic quality
      This visualization uses a cohesive palette with a clean white background and simple geometric shapes throughout. The consistency and simplicity of the visualization's design improves interpretability and reduces cognitive load. 

      2. Perceptual quality
      Each chart included in the visualization matches its data type. The horizontal bar chart effectively communicates magnitude comparisons across neighbourhoods. This is a familiar chart type, one that I actually use most often in my research too, that reduces unnecessary cognitive load. The donut chart is used only for the room type distribution, which has just three categories, keeping the visualization easy to interpret. The geographic map encodes spatial data through the Gestalt principle of proximity, where clusters of dots immediately signal to the audience density. This chart effectively achieves its intended purpose. The dashboard as a whole uses cognition over memory by presenting all key metrics side by side, and demonstrates the careful choice of visualization or chart types to effectively communicate different data structures.

      3. Substantive quality
      The numerical values are displayed prominently on the charts. These precise labels enable accurate interpretation rather than approximate reading from visual encoding alone. This also helps to reduce cognitive load. The visualization honestly presents data across multiple views without distortion, satisfying the substantive quality criterion.

      ```
    - How could this data visualization have been improved?  
      ```
      The donut chart presents data through area and angle, and is among the least accurate/preferred visualization types as they require approximate rather than precise intepretation. Replacing it with a horizontal bar chart would allow the audience to compare room type proportions more accurately and quickly using position among a common scale.

      The monochromatic pink palette, while visually cohesive and clean, provides limited contrast differentiation. Adding a secondary colour or using colour blindness-friendly colours would improve accessibility and interpretability.
      
      ```
    BAD visualization
    GDP & Climate Change (Michael Reilly)
    https://public.tableau.com/app/profile/michael.reilly/viz/GDPClimateChange/Dashboard1 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      1. Aesthetic quality 
      The visualization uses a red-to-green diverging palette, which is unreadable for audiences with red-green colour vision deficiency, which is the msot common form.

      2. Perceptual quality
      The colour scale spans from -100% to +1,500%, but the vast majority of countries fall in the -100% to +200% range (esp in years 2030, 2050). This extreme skew compresses most nations into a narrow, nearly indistinguishable band of similar colours. It's hard to tease out differences with this scale and legend. Based on our lessons, we also know that colour and area encoding already require approximate rather than accurate interpretation; the distorted scale compounds this challenge by making it nearly impossible to perceive meaningful differences between most countries. Data visualization should leverage human cognition to understand data more intuitively. 

      3. Substantive quality
      The visualization provides no explicit citation of the underlying economic model, dataset, or climate scenario. The provenance rhetoric, as learned in class, states the inclusion of a data source signals transparency and trustworthiness to audiences. Without attribution, the audience cannot evaluate whether the projections are credible or reproducible. The title also states 'GDP AND Climate Change', but the colours and legend are only conveying GDP changes.

      ```
    - How could this data visualization have been improved?  
      ```
      The red-green diverging palette could be replaced with a colourblind-friendly accessible alternative such as blue-orange or purple-orange. This preserves the diverging logic while remaining interpratble for audiences with red-green colour vision deficiency. 
      
      The colour scale can be truncated or transformed to better differentiate countries in the common range, and add an explicit data source citation identifying the underlying economic model and climate warning scenario. This would improve both perceptual accuracy and substantive transparency. 

      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-09`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
