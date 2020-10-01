# Kickstarter: Exploratory Data Analysis
Kickstarter is an American public benefit corporation that maintains a global crowdfunding platform focused on creativity. To raise funds, a ‘creator’ describes a project, sets a goal for the amount to raise, and appeals ‘backers’ to invest in the campaign. If the goal is reached, then creator receives all the funds pledged. Otherwise, the campaign will not be funded, and all the money is returned to the backers. This project focuses on performing exploratory data analysis that can provide valuable insights for budding creators to understand the market before enlisting their projects and enthusiastic backers to invest on successful projects.<br/>
Following are the questions the project tries to answer:
* Which main categories are more successful in reaching the goal?
* Which main categories attract more backers?
* Which main categories raise more money from successful campaigns?
* Are there any significant differences in the projects' success across countries?
* Does goal amount set by a fundraiser have any impact on the success of a project?
* Is there any noticeable trend over time?
* Does duration of the project influence the project success?
## About Data
The dataset contains information about 375k + projects with following major attributes:
* `id` – Project ID number
* `name` – Project name
* `main_category` – Project main category (decided by project creators)
* `category` – Project subcategory within main category (decided by project creators)
* `launched` – When project was launched on Kickstarter
* `deadline` – Deadline by which fundraising goal should be met
* `state` – Whether project was successful (reached fundraising goal), failed (did not reach fundraising goal), or cancelled (cancelled early by the project creator)
* `backers` – Number of people who have contributed to the project by paying an amount of money
* `country` – Where the project is located
* `usd_goal_real` – Project fundraising goal in USD
* `usd_pledged_real` – Amount of money pledged by the deadline in USD
## Analysis
The complete analysis report is published on [RPubs](https://rpubs.com/phxlumens/kickstarter).<br/>
## Get Help
* `code/run.Rmd` – Run the code file for complete analysis
* `code/report.Rmd` – Knit the code file to generate publishable report
