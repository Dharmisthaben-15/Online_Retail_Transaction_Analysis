# Online Retail Transaction Analysis
 Online Retail Transaction Analysis is a data analytics project designed to analyse online retail transaction data and generate meaningful business insights. The project focuses on understanding customer purchasing behaviour, product performance, sales trends and geographical sales patterns.

 Python will be used data cleaning, exploratory data analysis, statistical analysis and masin learning. Streamlit will be used to develop an interactive data application that allows users to explore the analysis and visualisations through an easy to use interface.

 The project aims to transform raw retail transaction data into useful insights that can support business decision making, particularly around products, customers, sales performance and marketing strategies. 

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Dataset Content
The dataset contains transactional information from an online retail store, including:
- invoice number
- stock code
- product description
- quantity
- invoice date
- unit price
- customer ID
- country

## Business Requirements

The business needs a clear understanding of how the online retail store is performing and where improvements can be made.

* Analyse sales trends over time to identify periods of high and low revenue.
* Identify the best-selling products and the products that generate the most revenue.
* Understand customer purchasing behaviour and determine which customers provide the highest value.
* Measure sales performance by country to highlight key markets and potential growth areas.
* Detect data quality issues such as missing customer information, cancelled orders, and unusual transaction values.
* Segment customers based on purchasing behaviour to identify distinc customer groups and support targeted marketing and customer retention strategies.
* Use the findings from the analysis to provide evidence based recommendations for inventory planning, marketing and customer retention.
## Hypothesis and how to validate?

* The project will investigate the following hypothesis using the online retail transaction dataset.

* H1: The United Kingdom contributes the highest share of total revenue compared to other countries.
  * Validation: Group the data by Country and calculate total revenue using Quantity * UnitPrice. Compare revenue by country using bar charts and summary tables.

* H2: Sales volume and revenue increase during certain months or seasonal periods.
  * Validation: Convert InvoiceDate to datetime, group sales by month, and analyse revenue and quantity trends over time using line charts.

* H3: A small number of products generate a large proportion of revenue.
  * Validation: Group the dataset by StockCode or Description, calculate total revenue, and rank the top-performing products using bar charts.

* H4: Some transactions contain data quality issues such as negative quantities, zero or negative unit prices, or missing customer IDs.
  * Validation: Check for missing values, invalid quantities, invalid prices, and duplicate or cancelled transactions before analysis.

* H5: High-value customers are a small segment of the customer base but contribute a significant portion of total sales.
  * Validation: Group by CustomerID, calculate total spend, identify the top customers, and compare their contribution to total revenue.
## Project Plan

* Define the business problem and project objective. 
* Obtain and inspect the dataset.
* Create an ETL pipeline. 
* Clean and transform the data.
* Perform exploratory data analysis.
* Conduct discriptive and statistical analysis.
* Test the project hypotheses.
* Perform customer segmentation and machine learning analysis.
* Develop interactive visualisations.
* Develope the interactive dashboard/application.
* Evalute the results and discuss limitations.
* Product business recommendations.
* Documents the project developement process.
* Prepare and final presentation.

## The rationale to map the business requirements to the Data Visualisations

* List your business requirements and a rationale for mapping them to the Data Visualisations

## Analysis techniques used

* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques? Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations (optional)

* Feel free to delete this section if this is a data visualisation only (unit 1 or 2) project submission.
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design (optional)

* Feel free to delete this section if this is a data visualisation only (unit 1 or 2) project submission.
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during project development, you may revisit your dashboard plan to update a feature (for example, at the beginning of the project, you were confident you would use a given plot to display an insight, but later you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs

* Please list any unfixed bugs and explain why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap

* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment (optional)

* If this is a Unit 3 Streamlit, Power BI or Tableau Public project, then you can include a link here and explain how you hosted the dashboard.

### Heroku (optional)

* This section is necessary only if you are deploying a Streamlit app to Heroku as part of your submission for units 2 and 3. 
* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the `.python-version` Python version to a [Heroku-22](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click the button Open App at the top of the page to access your App.
6. If the slug size is too large, then add large files not required for the app to the `.slugignore` file.

## Main Data Analysis Libraries

* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.

## Credits

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials; however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section into Content and Media, depending on what you include in your project. 

### Content 

- The text for the Home page was taken from the Wikipedia Article A
- Instructions on how to implement form validation were taken from a [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)

* Thank the people who supported this project.