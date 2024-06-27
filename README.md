# Social-Buzz-Analysis
The project enables the development of a comprehensive understanding of the client's needs and business challenges, allowing for the identification of specific requirements that need to be addressed and prioritizing the key tasks that as a data analyst should focus on to deliver a successful outcome.

## Table of Contents
- Problem Statement
- Objectives
- The Data
- Data Cleaning and Preparation
- Exploratory Data Analysis
- Data Analysis
- Insights
- Dashboard
- Recommendations

## Problem Statement

Over the past 5 years, Social Buzz has reached over 500 million active users each month. They have scaled quicker than anticipated and need the help of an advisory firm to oversee their scaling process effectively. Due to their rapid growth and digital nature of their core product, the amount of data that they 
create, collect and must analyze is huge. Every day over 100,000 pieces of content, ranging from text, images, videos and GIFs are posted. All of this data is highly unstructured and requires extremely sophisticated and expensive technology to manage and maintain. Out of the 250 people working at Social Buzz, 200 of them are technical staff working on maintaining this highly complex technology. Up until this point, they have not relied on any third party firms to help them get to where 
they are. However there are 3 main reasons why they are now looking at bringing in externalexpertise:
- They are looking to complete an IPO by the end of next year and need guidance to ensure that this goes smoothly. 
- They are still a small company and do not have the resources to manage the scale that they are currently at. They could hire more people, but they want an experienced practice to help instead.
- They want to learn data best practices from a large corporation. Due to the nature of their business, they have a massive amount of data so they are keen on 
understanding how the world's biggest companies manage the challenges of big data.

## Objectives
This project will design and develop an intuitive and user-friendly dashboard that provides actionable insights into the top-performing categories, content types, and trends. The envisioned dashboard will offer a comprehensive overview of performance metrics, including the top 5 categories, content type performance, distribution by category, and monthly trends for 2011. By leveraging Microsoft Excel, this project aims to empower informed decision-making and drive sustainable growth for social buzz.

## The Data
The dataset for this project was provided by [Forage](https://www.theforage.com/simulations/accenture-nam/data-analytics-mmlb). This include 3 datasets; The Reaction, Content and Reaction Types. After thorough cleaning, it amounts to a total of 2,627 rows and 7 columns withe the following information:
  1. Content ID
  2. Reaction Type
  3. DateTime
  4. Content Type
  5. Category
  6. Sentiment
  7. Score

<img width="451" alt="Screenshot 2024-06-26 223620" src="https://github.com/a0damy/Social-Buzz-Analysis/assets/171259818/742a0a35-c0f4-4a89-8a06-582ba595153e">

## Data Cleaning and Preparation
After successfully importing the data into Excel, I moved on to the data cleaning and preparation phase. This involved implementing the following steps to ensure the data was suitable for analysis:
- Removing rows that have values which are missing
- Changing the data type of some values within the column
- Removing columns that are not relevant to the task
- Data modelling by merging three tables together

## Exploratory Data Analysis
The project answer the following questions:
- What are the top 5 categories by aggregate popularity score?
- What are the performance of each content type?
- What are the distribution of each categories?
- Which is the month with the highest content?

## Data Analysis
This include an Excel function used in this project to derive the aggregations of values based on condition <br>
=SUMIF('Social Buzz Cleaned Data'!F:F,'Popular Categories'!B16,'Social Buzz Cleaned Data'!H:H)

## Insights
  1. Top 5 Categories: Animals, Science, Healthy Eating, Technology and Food. Animals with the highest score at 74,965.
     
     <img width="130" alt="Screenshot 2024-06-26 231130" src="https://github.com/a0damy/Social-Buzz-Analysis/assets/171259818/2636ad95-cca9-4eab-b354-74c0e4f34530">

  2. Performance by Content Type: Photo, Video, Audio and GIF. Photo has the highest performance of 6,589 total posts.
     
     <img width="134" alt="Screenshot 2024-06-27 001508" src="https://github.com/a0damy/Social-Buzz-Analysis/assets/171259818/3c91ab31-fbdc-4a7f-a91e-f3af8cdb6758">

  3. Distribution by Category: A total of 16 unique categories.
     Animals ranked the top with a total of 1,897 engagement, while Public speaking ranked the least with 1,217 engagements.
     
     <img width="154" alt="Screenshot 2024-06-27 001945" src="https://github.com/a0damy/Social-Buzz-Analysis/assets/171259818/966194f5-588c-4c1a-955d-10723e166f31">
     
  4. Content Type by Month: The trend of content type by month shows that May is the peak month for content creation with a total of 2,138 engagements.
     February has the least with 1,914 engagements.
     
     <img width="165" alt="Screenshot 2024-06-27 003344" src="https://github.com/a0damy/Social-Buzz-Analysis/assets/171259818/e4e7a7e5-5e5e-4edf-9c7a-04a94ef73fd5">

## Dashboard

## Recommendations
  1. Food being a dominant topic, capitalize on the popularity of healthy eating content by launching a targeted campaign that resonates with the audience. This 
     campaign can include; Sponsored content and product placements with healthy eating brands, Influencer partnerships with wellness experts and nutritionists.
  2. Utilization of the peak engagement month (May) to launch the campaign and maximize user interaction.
  3. Creation of high-quality, engaging content (e.g. videos, recipes, blog posts) that addresses user interests and concerns.
  4. Monitoring and tracking key performance indicators (KPIs) such as engagement metrics, click-through rates, and conversion rates to measure and determine the
     content's effectiveness.
  5. Regularly reviewing and adjusting the campaign's strategy to optimize results and ensure alignment with the business objectives.





