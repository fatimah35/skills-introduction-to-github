Short description
This report analyzes a financial consumer complaints dataset to uncover insights into the types of complaints received, the timeliness of company responses, and patterns in consumer dispute resolutions.
README
Table of contents

Project overview
Analysis tools
Data acquisition
Data cleaning
Data analysis
Key findings
Recommendations
Conclusions
Project Overview

This report provides insights into complaint trends, company performance, and areas for improvement. The dataset consists of the following columns:

Response Days: Time taken by the company to respond to a complaint.

Products: Financial products involved in the complaints.

Issues: Types of issues raised by consumers.

Countries: Geographic locations where complaints originated.

Consumer Dispute: Indicator of whether the consumer disputed the resolution.

Consumer Consent: Whether the consumer consented to share complaint data publicly.

Medium via Issues Were Submitted: Channels through which complaints were submitted (e.g., email, phone, web).

Company Response: Descriptions of how companies responded to complaints.

Timely Response: Indicator of whether the company responded within a specified time frame.

Analysis Tools

Google Sheets: Used for initial data extraction online

Microsoft Excel: Employed for advanced data cleaning and transformation

Power BI: DAX was utilized for creating custom calculations and metrics to derive deeper insights, bi was used for reporting and dashboard creation to visualize trends and performance metrics.

Data Acqustion : data was extracted online .
Image

Data Cleaning and Validation

To ensure accuracy and realibility of the dataset, missing values were checked. 3% of the dataset were missing,the missing values in the countries column were replaced with others empty columns were replaced with N/A, Also, columns that were unnecessary for the analysis were removed, duplicate entries were removed and the date column was also checked to ensure the issues were recorded between 2011- 2020.
Image

Data Analysis and Insights

Descriptive Analaysis

Issues : The dataset’s "Issues" column highlights recurring problems reported by customers. By Summarizing the number of complaints for each product category, grouping and analyzing these issues, we can identify the most frequently reported problems. The company received a total of 75,513 complaints between the year 2011-2020.

Product: The products purchased from the company shows more insights into issue reported, there are 8 products the company offers its customers. Identifying which products generate the most complaints can help prioritize areas for process improvements.

Regional Trends: Analysis of the "countries" column provides insights into geographical patterns. Specific regions or countries may have higher complaint volumes, possibly reflecting market size or unique financial challenges in those areas. There are 62 countries in total in this dataset.

Timely Response: Using the "Timely Response" column, i evaluated how often companies meet deadlines for responding to complaints. High levels of timely responses indicate strong operational efficiency, whereas delays may point to congestion in complaint handling processes.

Response Days: Using the date complaint was submitted and received a new column Response Days" was created. It provides a quantitative measure of the average response time. Trends can reveal if certain issues or products take longer to address, allowing companies to refine complaint management processes.

Dispute Resolution: The "Consumer Dispute" column tracks whether consumers dispute the company’s resolution. High dispute rates may signal dissatisfaction with company practices or inadequate resolution methods. These trends are critical for improving customer satisfaction.

Consent to Share : Examining the "Consumer Consent" column reveals how many consumers agreed to share their complaints publicly, understanding this trend helps determine the level of consumer trust and transparency.

Submission Medium: The "Medium via Issues Were Submitted" column provides valuable insights into consumer behavior. Popular submission methods, such as web portals or phone calls, can inform companies on optimizing communication channels.

Comparative Analysis

Issue by Product: Analyzing which products (e.g., credit cards, student loans) generate the most complaints and identifying differences in complaint frequency or types of issues across products.
The chart shows credit card was the product associated with high volume of complaints while vehicle loan or lease had least complaints re orded.

Image

Geographical Trends: Examining complaint patterns across different countries or regions to determine which areas have higher or lower complaint volumes and understanding the reasons behind them.
Image
Image

The chart above shows the top countries complaints were received and countries with least complaints. California had the highest while palau had the least received complaints.
Furthermore, it was neccessary to examine the dominant issues in the 62 geographical locations customers reside. To acheive this, new measures dominat issues and thier respective counts were created using dax. Dominant issues, thier counts and percentage in each countries are showed in the table below.
Image

Company Responses: Comparing the timeliness and effectiveness of responses across different companies or types of complaints.
Majority of complaints (98%) received were timely responded to. Furthermore, 55k issues were closed and explanation were given to customers. This resulted in 41.32% of complaints not disputed by customers.
Image
Image
Image

Submission Mediums: Analyzing which communication channels are most effective for resolving complaints quickly or which channels consumers prefer to use. High number of customers prefer to submit issues via web, fewer customers complained via email.
Image
Further analysis into the average number of days issues were received showed issues received via email takes longer time compared to via web.
Image

Complaints over the time: Analysis revealed more complaints were received during the year 2018 with april been the peak month.
Overall, August was the month highest complaints were received.
Image
Image

Key Findings

Image
Image

Product Trends: Credit cards have the highest number of complaints, while vehicle loans have the lowest.

Geographical Insights: California reports the highest number of complaints.

Timeliness: The overall timely response rate is 98%.

Channel Preference: Web is the fastest medium for issue resolution, while email is the slowest.

Consumer Disputes: The dispute rate is 9.75%, suggesting room for improvement in resolution quality.

Recurring Issues: The dominant issue reported is "managing an account."

Seasonal Patterns: August has the highest complaint volume, followed by July.

Recommendations

Address High Complaint Products

Focus on resolving recurring issues with credit cards, as they generate the most complaints.

Provide proactive account management solutions and educational resources for consumers.

Improve Complaint Resolution Quality

Analyze the root causes of disputes and implement solutions to address consumer dissatisfaction.

Provide better training for customer service teams to handle complex complaints.

Optimize Communication Channels

Invest in web portal enhancements to maintain its status as the fastest resolution medium.

Review and streamline email communication processes to reduce delays.

Regional Focus

Investigate why California has the highest number of complaints and address regional-specific concerns.

Deploy targeted campaigns to educate consumers in high-complaint regions.

Prepare for Seasonal Spikes

Allocate additional resources during peak months like August and July to manage the higher complaint volumes effectively.

Implement preventive measures to address recurring seasonal issues.

Maintain Timeliness

Continue efforts to sustain the 98% timely response rate and aim for 100%.

Monitor response time trends regularly to identify and address potential delays promptly.

Enhance Account Management Services

Develop tools and resources to help consumers manage their accounts effectively.

Introduce self-service options for common account management tasks to reduce complaints.<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Introduction to GitHub

_Get started using GitHub in less than an hour._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Step 1: Create a branch

_Welcome to "Introduction to GitHub"! :wave:_

**What is GitHub?**: GitHub is a collaboration platform that uses _[Git](https://docs.github.com/get-started/quickstart/github-glossary#git)_ for versioning. GitHub is a popular place to share and contribute to [open-source](https://docs.github.com/get-started/quickstart/github-glossary#open-source) software.
<br>:tv: [Video: What is GitHub?](https://www.youtube.com/watch?v=pBy1zgt0XPc)

**What is a repository?**: A _[repository](https://docs.github.com/get-started/quickstart/github-glossary#repository)_ is a project containing files and folders. A repository tracks versions of files and folders. For more information, see "[About repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories)" from GitHub Docs.

**What is a branch?**: A _[branch](https://docs.github.com/en/get-started/quickstart/github-glossary#branch)_ is a parallel version of your repository. By default, your repository has one branch named `main` and it is considered to be the definitive branch. Creating additional branches allows you to copy the `main` branch of your repository and safely make any changes without disrupting the main project. Many people use branches to work on specific features without affecting any other parts of the project.

Branches allow you to separate your work from the `main` branch. In other words, everyone's work is safe while you contribute. For more information, see "[About branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)".

**What is a profile README?**: A _[profile README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)_ is essentially an "About me" section on your GitHub profile where you can share information about yourself with the community on GitHub.com. GitHub shows your profile README at the top of your profile page. For more information, see "[Managing your profile README](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)".

![profile-readme-example](/images/profile-readme-example.png)

### :keyboard: Activity: Your first branch

1. Open a new browser tab and navigate to your newly made repository. Then, work on the steps in your second tab while you read the instructions in this tab.
2. Navigate to the **< > Code** tab in the header menu of your repository.

   ![code-tab](/images/code-tab.png)

3. Click on the **main** branch drop-down.

   ![main-branch-dropdown](/images/main-branch-dropdown.png)

4. In the field, name your branch `my-first-branch`. In this case, the name must be `my-first-branch` to trigger the course workflow.
5. Click **Create branch: my-first-branch** to create your branch.

   ![create-branch-button](/images/create-branch-button.png)

   The branch will automatically switch to the one you have just created.
   The **main** branch drop-down bar will reflect your new branch and display the new branch name.

6. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-github) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
