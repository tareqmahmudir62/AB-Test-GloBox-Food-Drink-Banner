# AB-Test-GloBox-Food-Drink-Banner
# GloBox Food and Drink A/B Test Project

## Description

This GitHub repository contains the code, data, and documentation for the GloBox Food and Drink A/B Test project. The project's goal is to assess the efficacy of a promotional banner highlighting GloBox's food and drink products on the company's e-commerce website. GloBox, an online marketplace known for its niche fashion and upscale decor items, has recently expanded its food and beverage offerings. The growth team aims to increase revenue in this category through a targeted marketing campaign.

## Background

GloBox is an e-commerce company that has expanded its food and drink offerings and wants to raise awareness to increase revenue in this category. The team has proposed an A/B test to compare the performance of the company's website with and without a promotional banner highlighting key food and drink products.

## Objective

The primary objective of this project is to increase revenue for GloBox's food and drink product category through an A/B test. The test aims to determine whether the presence of a promotional banner on the website's landing page can significantly influence customer purchase behavior. By analyzing the results, the team hopes to identify the website version that performs better in driving sales for the food and drink category, thus aiding in the formulation of an effective marketing strategy.

## Dataset

The dataset for this project was obtained from a relational database accessed through the online database management platform, bit.io. It consists of three tables - users, groups, and activity. SQL was used to consolidate the data into a single dataset, which was then exported in CSV format for further analysis using Python. The dataset includes 48,943 unique participants divided into a control group (24,343 participants) and a treatment group (24,600 participants).

## A/B Test Setup

The A/B test is conducted exclusively on GloBox's mobile website to ensure consistency and accuracy of the results. Upon visiting the main page, each user is randomly assigned to either the control or test group, which serves as their join date for the experiment. The website landing page loads the promotional banner for the test group, while it does not load for the control group. Users may purchase products from the website at any time following their assignment to the test or control group, and any such purchases are considered a "conversion."

## Project Deliverables

The project includes the following deliverables:

1. **Analysis Plan**: A detailed analysis plan that outlines the approach, methodology, and statistical tests used to analyze the A/B test results. The plan is reviewed and approved by the team.

2. **A/B Test Results**: A comprehensive report that analyzes the A/B test results to determine the success of the experiment. It includes a summary of key performance indicators (KPIs) such as conversion rates, revenue generated, and other relevant metrics.

3. **Presentation**: A recorded presentation summarizing the A/B test results and providing recommendations for improving the company's marketing strategy based on the findings. The presentation includes visual aids, charts, and graphs to illustrate the results.

## Recommendations

Based on the analysis, we recommend against launching the banner on the website. Although the conversion rate shows statistical significance, the observed change in the average amount per user spent is not statistically significant enough to yield a substantial increase in sales. Therefore, we propose either not launching the banner or conducting another test with a larger sample size to arrive at a more definitive conclusion.

Thank you for visiting this repository! If you have any questions or feedback, feel free to reach out.
