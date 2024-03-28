# MedInsure Claims Analysis

MedInsure is a medical insurance company helping thousands of people cover the cost of preventative care and medical bills throughout the US. They offer four plan types (bronze, silver, gold, and platinum) with different premiums and claim coverage rates. In 2019, MedInsure launched a series of new campaign categories covering topics like wellness tips, the affordability of their plans, and preventative care. I created an interactive Tableau dashboard to report on marketing, signup, and claims metrics to investigate the campaign category performance and provide recommendations on future budget allocation with two goals in mind: (1) increasing the number of customer signups and (2) raising awareness of MedInsure's brand across the country. Lastly, I created a PowerPoint presentation for the marketing team to present my insights and recommendations. 

## Interactive Tableau Dashboard

The interactive dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/astrosica/viz/MedInsureClaimsDashboard/Dashboard). This dashboard enables users to filter by plan type, campaign type, and customer state, focusing on marketing, signup, and claim metrics.

![MedInsure_Dashboard](https://github.com/jessicacampbell-astro/MedInsure_claims_analysis/assets/23153120/6c0646f2-37fc-4202-9c34-ec369e02d6ae)

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
- The Golden Years Security campaign had the lowest CTR (1%), highest CPC ($0.68; nearly six times the average), and only about half the average impressions (422K).
- Despite having the fourth-highest impressions, the Family Coverage Plan campaign had zero clicks.

### Signup Metrics

- The Healthy Living campaign had the highest number of signups (3.7K) with a particularly low cost per signup ($1.79) and surprisingly low signup rate (0.3%).
- The Golden Years Security campaign had the lowest signup rate (0.01%), lowest number of signups (23), and highest cost per signup ($177).
- The Family Coverage Plan campaign had one of the lowest signup rates (0.03%) and one of the lowest number of signups (300), possibly due to zero clicks on the marketing campaign.

### Claims Metrics

- The Compare Health Coverage campaign had the highest average claim amount ($410) and the highest total claim amount ($3.9M), possibly due to a post-pandemic surge in claim amounts.
- The Golden Years Security campaign had the lowest average claim amount ($215) and the lowest total claim amount ($16K), likely because it was severely underperforming in marketing and signup metrics.
- The claim amounts for the Compare Health Coverage campaign saw a rapid increase at the beginning of the COVID-19 pandemic and have since rapidly declined to higher than pre-pandemic amounts.
- Despite having the highest to-date average and total claim amounts, the relative success of the Health For All campaign has slowly declined over the pandemic.

## Recommendations

The team provides the following recommendations:
- Reallocate the budget from the lowest-performing Golden Years Security campaign (which has the highest CPC and the highest cost per signup) to the higher-performing Benefit Updates campaigns with a focus on increasing impressions.
- Reconsider alternate means for directing marketing campaigns to new Golden Years Security customers (e.g., physical handouts over electronic ads).
- Investigate the lack of clicks with the Family Coverage Plan, which may reflect a data quality issue, to increase the low signup rate and number of signups.
- Decrease investment in the Health For All and Compare Health Coverage campaigns as their post-pandemic success is declining.

## PowerPoint Presentation

The PowerPoint presentation presenting the above insights and recommendations for the marketing team can be found here. Some highlights are shown below:

![PPT_opening](https://github.com/jessicacampbell-astro/MedInsure_claims_analysis/assets/23153120/d610cf6f-c4fe-4813-af1c-59e99b535c54)
![PPT_signup_rates](https://github.com/jessicacampbell-astro/MedInsure_claims_analysis/assets/23153120/7e7efb2d-903f-422c-a254-7beb31dc6d0b)
![PPT_recs](https://github.com/jessicacampbell-astro/MedInsure_claims_analysis/assets/23153120/3b578649-2f28-4d6e-b640-0bbda88da224)
![PPT_tech_process](https://github.com/jessicacampbell-astro/MedInsure_claims_analysis/assets/23153120/109c1f84-5d13-4778-86b1-6bbef7177384)

## Contact

Feel free to contact me on [LinkedIn](https://www.linkedin.com/in/jessicacampbell-astro/)!
