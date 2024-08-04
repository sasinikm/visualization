# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

    ```
    1. Visualization created with Python (in assignment4.ipynb file)
    ```
    > What software did you use to create your data visualization?
    Python

    > Who is your intended audience? 
    General public, Economists, Businesses and investors
    
    > What information or message are you trying to convey with your visualization? 
    This visualization includes a line graph and a pie chart. 
    * Line graph indicates how the Gross Domestic Product(GDP) of Ontario changes over time (2007-2022). 
    * Pie chart indicates the contribution of two main industries(Services,Goods Producing) to the GDP of 2022.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive Principles:
        * The visualizations are accurately plotted and labeled
        * Clear axis labels, titles and legends are provided to ensure that users understands the plots
        * The plots clearly convey the required message
        * Only key insights are shown by the plots without making the visualizations cluttered

     Perceptual Principles: 
        * Contrasting colours are used to plot GDP for different industries
        * Custom tooltips are used to display relevant information concisely
        * The use of markers and lines shows the data points and trends over time
    
     Aesthetic Principles
        * Colors used are neautral which are accessible for color sensitive and color blind audiences
        * Consistent use of fonts, line styles, and marker sizes
        * Properly spacing and aligning to ensure the plot is not cluttered improving the readability

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Data source is mentioned below each plot and the python code (commented for clarity) is available in Git in a public repository making this visualizations reproducible. Beacuse python tool is used to generate these plots, they are reporoducibe. 
    
    > How did you ensure that your data visualization is accessible?  
    To make the these visualizations accessible 
    * contrasting and neutral colours are used
    * Titles, x-axis label, y-axis label and a legend are added
    * Tooltips are added for users to hover over the plots and understand data
    * Fontsizes over 12pt are used

    > Who are the individuals and communities who might be impacted by your visualization?  
    *Economists and policy makers who use GDP data to analyze economic performance
    *Businesses and investors who rely on GDP data to make investment decisions
    *The general public who uses GDP data to understand the economy of Ontario

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    As the main purpose of the visualizations was to give an overview of Ontario's GDP, only the GDP of main two industries are selected for representation. GDP of the sub sectors under Goods producing industry were not included in the visualizations.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Finding an accurate dataset, Cleaning and modifying data in to python readable format, Writing python
    script to generate required plots, commenting the script for reproducibility and modifying the plots for better accessibility. 


    ```
    2. Dashboard created with PowerBI (in assignment4.pbix file and assignment4.png)
    ```
    > What software did you use to create your data visualization?
    PowerBI 

    > Who is your intended audience? 
    General public, Economists, Businesses and investors
    
    > What information or message are you trying to convey with your visualization? 
    This visualization includes a line graph, a pie chart and a bar graph. 
    * Line graph indicates how the Gross Domestic Product(GDP) of Ontario changes over time (2007-2022)
    * Pie chart indicates the contribution of two main industries(Services,Goods Producing) to the GDP based on user selected year
    * Bar graph shows the contribution of sub sectors to the GDP of Goods Producing industry based on the user selected year
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive Principles:
        * The visualizations accurately plot and label the data
        * Clear axis labels, titles and legends are provided to ensure that users understands the plots
        * The plots clearly convey the required message
        * Only key insights are shown by the plots without making the visualizations cluttered

     Perceptual Principles: 
        * Contrasting colours are used to plot GDP for different industries
        * Custom tooltips are used to display relevant information concisely
        * The use of markers and lines shows the data points and trends over time
        * Colors of the industries are consistent throughout the dashboard to avoid confusion  

     Aesthetic Principles
        * Colors used are neutral colors which are accessible for color sensitive and color blind audiences
        * Consistent use of fonts, line styles, and marker sizes
        * Properly spacing and aligning to ensure the plot is not cluttered to improve the readability

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Data source is mentioned in the report for reproducibility. As PowerBI tool is used to generate these plots, they are not reporoducibe. This will
        * reduce the trasperency of the report
        * be challenging to verify the accuracy
        * be difficult to reproduce the insights
        * modifications will be time consuming
        * be difficult to idnetify errors in the process of creating the plots

        But by using PowerBI with a work account, the dashboard could be published in the cloud and users can be given 
        edit access which will improve the reproducilibilty. Also it will improve the transperency and will be easy to maintain and make changes to the plots. By doing all the data transformations in PowerBi itself, all the steps associated with data cleaning will be available in the data transform tab of PowerBI.
    
    > How did you ensure that your data visualization is accessible?  
    To make the these visualizations accessible 
    * contrasting and neutral colours are used
    * Titles, x-axis label, y-axis label and a legend are added
    * Tooltips are added for users to hover over the plots and understand data
    * Fontsizes over 12pt are used
    * The dashboard is interactive for further analysis by year 

    > Who are the individuals and communities who might be impacted by your visualization?  
    * Economists and policy makers who use GDP data to analyze economic performance
    * Businesses and investors who rely on GDP data to make investment decisions
    * The general public who uses GDP data to understand the economy of Ontario

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    As the main purpose of the dashboard was to give an overview of Ontario's GDP, the GDP of main two industries are selected
    for representation. GDP of the sub sectors under Goods producing industry are also ncluded in the dashboard
    as this is an interactive report, so users can select the years and get a better understanding based on their 
    knowledge level.

    > What ‘underwater labour’ contributed to your final data visualization product?
    Finding an accurate dataset, Cleaning and modifying data using powerBI transform and creating the 
    plots, adding slicers and formatting the dashboard to improve the readability.


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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
