# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    Visualization #1 was created using Python. The dataset of choice for this assignment is data on The Economic Impact of Tourism in Ontario - 2022, available in Ontario's Open Data Catalogue. 

    Visualization #2 was created using Excel. The dataset of choice is data on supports to Youth Justice Court for youth aged 12-17 with mental health needs who are in conflict with the law, availabe in the Ontario's Open Data Catalogue.

    > Who is your intended audience? 

    Visualization #1: The intended audience for this visualizations would be policy makers or analysists, rather than the general public. Government policy makers would be interested to know which sectors bring in the most valye to inform funding decisions, policy development, and investment strategies. 

    Visualization #2: The intedned audience for this visualization would also be policy makers, but also youth justice and mental health professionals ashey can use the visualization to understand trends in caseloads and where support is most needed.

    > What information or message are you trying to convey with your visualization? 
    Visualization #1: The visualization is intended to communicate the scale and structure of the direct economic contribution of tourism to Ontario’s economy in 2022. Specifically, it conveys that tourism is not only a cultural or leisure activity, but a major economic sector. Specifically, GDP and labour income.

    Visualization #2: The visualization depicts that the northern region provides the least mental health support to its youth compared to other regions. In addition, the MCYS social services program 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Visualization #1: The original data had very large numbers and mixed units (jobs vs dollars). To address this, I converted monetary indicators to billions of dollars, and removed Employment to avoid confusion. This ensures the audience can immediately understand magnitudes without mentally converting numbers. Audience includes policymakers, analysts, and industry stakeholders, so I focused on direct monetary impacts, not total impacts or non-monetary data.
    
    Visualization #2: Grouping each social services program by color (Gestalt principles) allows the reader to easily identify the different groups the data is organzied by (YJSD, MCYS). 

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Visualization #1: The visualization was created entirely in Python using pandas and matplotlib. The data import step uses the direct URL to the Ontario Open Data Excel file. This ensures anyone with the code can access the same dataset without manual download.
    
    Visualization #2: Although this figure was created in excel which makes reproducibility more difficult, I have saved a master copy of the raw dataset separate from the figure, so anyone can start from the same data. In addition, code books explaining the variables and preprocessing steps of the data help others to replicate the images.

    > How did you ensure that your data visualization is accessible?  
    Visualization #1: Color choice matters for color-blind readers. So I used a color-blind-friendly palette (blue #0072B2 for Tourism Receipts, orange #E69F00 for Visitor Spending) which had a good colour contrast.

    Visualization #2: Increase the font size and ensured a strong colour contrast for color-blind readers. A line chart was chosen to show the trends in youth mental health support across the region and social service providers. 

    > Who are the individuals and communities who might be impacted by your visualization?  
    Visualization #1: I would say that the Tourism Industry Stakeholders (Hotels, restaurants, attractions, and tourism boards) would be impacted by my visualization since tourism Receipts are consistently higher than Visitor Spending across all indicators, reflecting that tourism generates additional economic value beyond what visitors directly spend.
    
    Visualization #2: The figure shows how many youth are served per region and over time, helping decision-makers allocate resources, plan interventions, and monitor program reach and effectiveness. In addition, this may support families and youth by highlighting access to mental health supports and can inform improvements in service coverage or outreach to underserved regions.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Visualization #1: Employment (Jobs) was removed because it uses a different unit (thousands of jobs) compared with monetary indicators (billions of dollars), which would make the y-axis confusing and the chart harder to interpret. In addition, indirect impact rows were excluded to keep the focus on direct impacts, which are immediately policy-relevant and easier to interpret.
    
    Visualization #2: I chose to exclude the year of mental health supports for youth as the message of the graph is how this support varies by region rather than year. Especially since data for each year was not available for all regions which made the graph incomplete. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Visualization #1: Firstly, data cleaning and preprocessing is important to remove duplicate rows/na values and filtering only the columns you want to include (Direct Impacts only), and normalizing the units for interpretability. Once the figure is made, I notived that including employment data was confusing, and so I removed employment data to avoid unit confusion. Finally, playing around with different colours, and choosing accessible, color-blind-friendly palettes.
    
    Visualization #2: Data cleaning and preprocessing such as renaming the fiscal year values to only be numerical, rather than leading with "FY" as the data was provided. In addition, I collapsed the data across year since this variable was not informative and only complicated readibility of the graph. 

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
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
