# MedInsure Claims Analysis

MedInsure is a medical insurance company helping thousands of people cover the cost of preventative care and medical bills throughout the US. They offer four plan types (bronze, silver, gold, and platinum) with different premiums and claim coverage rates. In 2019, MedInsure launched a series of new campaign categories covering topics like wellness tips, the affordability of their plans, and preventative care. I created an interactive Tableau dashboard to report on marketing, signup, and claims metrics to investigate the campaign category performance and provide recommendations on future budget allocation with two goals in mind: (1) increasing the number of customer signups and (2) raising awareness of MedInsure's brand across the country. I created a PowerPoint presentation for the marketing team to present my insights and recommendations. 

## Interactive Tableau Dashboard

The interactive dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/astrosica/viz/MedInsureClaimsDashboard/Dashboard). This dashboard enables users to filter by plan type, campaign type, and customer state, focusing on marketing, signup, and claim metrics.

![MedInsure_Dashboard](https://github.com/jessicacampbell-astro/MedInsure_claims_analysis/assets/23153120/98b0fbfe-0109-4efb-9e69-9eb6853e6918)

## Data Structure

The data consisted of 70K records over three tables: (1) marketing campaigns, (2) customer signups and demographics, and (3) claim information. The entity relationship diagram (ERD) for this dataset is shown below:

![MedInsure_ERD](https://github.com/jessicacampbell-astro/MedInsure_claims_analysis/assets/23153120/3a9cbbe6-d83f-4d51-9807-92ebcc8524ab)

## Key Metrics

In evaluating campaign performance, the analysis focused on the following key metrics:

- **Impressions**: The number of people who saw a marketing campaign.
- **Cost per Impression**: The average dollar amount spent on obtaining an impression.
- **Click-Through Rate (CTR)**: The percentage of people who saw a marketing campaign and clicked on the associated link.
- **Cost per Click (CPC)**: The average dollar amount spent on each marketing campaign click.
- **Signups**: The number of people who signed up for an insurance plan.
- **Signup Rate**: The percentage of people who saw a marketing campaign and signed up for an insurance plan.
- **Cost per Signup**: The average dollar amount spent on obtaining a customer signup.
- **Claim count**: The number of claims.
- **Claim amount**: The dollar claim amount.

## Summary of Insights

### Marketing Metrics

- The Health For All campaign had the highest CTR (25%) despite having the lowest impressions (171K).
- The Health For All and Benefit Updates campaigns performed 2-3 times better than the average CTR, at 25% and 22% respectively.
- The Golden Years Security campaign had the lowest CTR (1%), highest CPC ($0.68; nearly six times the average), and only 5% of the average impressions (422K).
- Despite having the fourth-highest impressions, Family Coverage Plan had zero clicks.

### Signup Metrics

- The Healthy Living campaign had the highest number of signups (3.7K) with a particularly low cost per signup ($1.79) and surprisingly low signup rate (0.3%).
- The Golden Years Security campaign had the lowest signup rate (0.01%), lowest number of signups (23), and highest cost per signup ($177).
- item

### Claims Metrics

- item
- item
- item

## Recommendations

The team provides the following recommendations:
- Reallocate the budget from the under-performing Golden Years Security campaign, which has the highest CPC, to the highest-performing Health For All and Benefit Updates campaigns.
- item
- Investigate the lack of clicks with the Family Coverage Plan as this may reflect a data quality issue.

## PowerPoint Presentation

The PowerPoint presentation presenting the above insights and recommendations for the marketing team can be found here. Some highlights are shown below:

## Contact

Feel free to contact me on [LinkedIn](https://www.linkedin.com/in/jessicacampbell-astro/)!
