<img alt="logoforgithub" src="https://github.com/user-attachments/assets/d184e7dd-c31a-478d-80b8-5b2dd24a8494" width="90" align="left"/>

# MediPulse Campaign Performance Analysis 

<br clear="left"/>

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Structure](#dataset-structure)
- [Insights Summary](#insights-summary)
- [Recommendations](#recommendations)
- [Dashboard](#dashboard)
- [Presentation Sample](#presentation-sample)

 # Project Overview 
Interactive Tableau dashboard analyzing the to-date impact of marketing campaign categories on signup and claim performance, designed to support quarterly business reviews and strategic decision-making.


MediPulse Marketing Insights - Project Overview
The goal of this project is to investigate the performance of marketing campaigns at MediPulse in order to surface recommendations on marketing budget allocation across future campaign categories.
Founded in 2016, MediPulse is a medical insurance company serving over thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories spanning topics like wellness tips, the affordability of their plans, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates.

Now that they’ve hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of MediPulse’s brand across the country.

 # Dataset Structure
 There are three main tables referenced, with the Entity Relationship Diagram (ERD) below:

 <img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/f80415b5-48e9-48d7-87eb-d7c22207e9eb" />

# Insights Summary

In order to evaluate campaign performance, we focused on the following key metrics:

- **Click through Rate (CTR)**: The percent of people who see a campaign and click on the associated link.
- **Cost per Click (CPC)**: The amount an advertiser pays each time a user clicks on their advertisement.
- **Signup Rate**: The percent of people who see a campaign and subsequently sign up for a MediPulse plan.
- **Cost per Signup**: The average dollars spent in order to acquire a signup from each campaign.

### Click through Rate
- Across categories, Health for All and Benefit Updates performed nearly 3-4x better than the average CTR at 36% and 22%, respectively.
- Within the two categories with high CTR, product promotion-based campaigns had relatively low CTR (0% and 7%).
- Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.

### Cost per Click (CPC)
-  Overall CPC remained relatively low across most campaign categories, indicating efficient click acquisition, with an average CPC of approximately $0.07.
- Golden Years Security stood out with a significantly higher CPC compared to other categories, suggesting higher competition or lower engagement efficiency for this audience segment.
- Campaign categories such as Health for All and Healthy Living achieved lower CPCs while maintaining strong click volumes, indicating more cost-effective marketing performance.

### Signup Rate
- Across campaign categories, Health for All campaigns had the best-performing signup rate (2.9%) and the second-highest number of signups (3.5K).
- This high signup rate is due to the Health Awareness campaign type, which had by far the highest signup rate across all campaign types (3.72%).
- Interestingly, the category with the highest number of signups - #HealthyLiving - had a comparably low signup rate at 0.3%.

### Cost per Signup
- Across campaign categories, Golden Years Security had by far the highest cost per signup ($124), as well as the lowest number of signups (23), compared to an average of $2.2.
- Within the two campaign categories with highest cost per signup, info-based campaign types (like offers and policy info) drove high costs per signup.
- Some COVID-based campaigns also had abnormally high CACs at $1.2-$1.3K.

# Recommendations

Recommendations focus on two strategies: removing ineffective campaign categories and reallocating budget towards categories with better performance across north star metrics.

- Golden Years Security: Consider discontinuing or overhauling this campaign due to its low click-through rate (1%) and high cost per signup ($177). Reallocate its budget to the Health For All Campaign, which has a stronger click-through rate (25%) and signup rate (2%).

- Family Coverage Plan: Investigate the lack of clicks despite high impressions, as there are likely issues with the campaign or missing data.

- Compare Health Coverage: Collaborate with the actuarial team to analyze this campaign category's demographics and health needs to ensure the campaign isn’t attracting higher-risk profiles than planned.

- Health Awareness: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had low signup rate and CTR.

- COVID Campaigns: Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that costed over $1K, compared to an average signup cost of $3,70. Consider removing these campaigns altogether.

 # Dashboard

 The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/anupa.ninan/viz/Rowhealth_Analysis/CampaignCatDash?publish=yes). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

<img width="1164" height="887" alt="image" src="https://github.com/user-attachments/assets/d50e76f9-0712-43c7-8b86-953783a85128" />



# Presentation Sample
The presentation created for the marketing team walks through the insights and recommendations above and can be found [here](https://docs.google.com/presentation/d/1jfcE_HRtPxFgq-1opKZuH0EJK164pnbPJKlDHCcqGDY/edit?slide=id.g3bdffef60c7_2_268#slide=id.g3bdffef60c7_2_268). Some extracts are presented below for easy viewing.

<img width="1226" height="718" alt="image" src="https://github.com/user-attachments/assets/b9269839-7c06-432e-b887-836c125945ee" />

<img width="1220" height="716" alt="image" src="https://github.com/user-attachments/assets/ba591d72-aba2-4637-aa19-a3b281cb5b36" />

<img width="1211" height="715" alt="image" src="https://github.com/user-attachments/assets/88ee9fb2-72f8-4ca0-aa15-dcd502196055" />

