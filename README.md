# Emerald Lead Distribution and Conversion Rate Analysis

### Table Of Content
[Background](#background)

[Problem Statement](#problem-statement)

[Analysis Objectives](#analysis-objectives)

[Dataset Description](#dataset-description)

[Tools Used](#tools-used)

[Data Cleaning Process](#data-cleaning)

[Data Analysis](#data-analysis)

[Key Insight](#key-insights)

[Business Recommendation](#business-recommendation)

### Background

Emerald Properties Ltd generates property leads through multiple marketing channels and 
assigns them to sales executives for follow-up.

In July 2023, the company recorded 193 total leads, distributed across: 
- Six sales executives
- Three property types
- Multiple branches
- Different customer demographics and inspection outcomes
Management has requested a descriptive overview of how these leads were distributed during 
the month.

### Problem Statement
Management currently lacks a clear, summarized view of how total leads were distributed and converted in July 2023. 
Specifically:
- There is no consolidated understanding of how leads were shared among sales executives
- Customer distribution by gender is unclear
- Lead outcomes (sales status) are not easily visible at a glance
- Distribution by branch, property type, and inspection status has not been summarized
- What is the conversion rate of these leads by sale rep, gender, location, property type and inspection type

Without this clarity, management cannot accurately monitor workload distribution, track lead 
flow, or understand overall sales activity patterns for the month.

### Analysis Objectives
This analysis aims to:
- Present the total number of leads recorded
- Show how leads were distributed across sales executives
- Summarize lead distribution by gender
- Display the breakdown of leads by sales status
- Show how leads were distributed across branches (states)
- Highlight lead distribution by property type
- Summarize inspection outcomes (Yes / No)
- What is the conversion rate of these leads by sale rep, gender, location, property type and inspection type

### Dataset Description
This is a lead distribution dataset which contains data spanning the period of July 2023. It contains ten (10) columns and 193 rows. This dataset basically contained date and text data typesThis dataset contains the following columns
- Client ID: The client ID serves as the unique identifier for this table.
- Client Gender: The sex of the client
- Sales Executives: The employee responsible for this lead
- Date: The date the data was gotten
- Sales: Provides a feedback on the sales status, it tells us if a purchase was made, or provides a feedback regarding purchase
- State: The location of the Lead
- Product: This explains the property type that was engaged by the lead
- Inspection: This tells us if the property was inspected by the lead
Taking a deeper look into the data and analyzing based on DQD, I noticed there were no missing values, duplicates or outliers. This data did not capture the value of sale made.

### Tools Used
- Excel
- Power Query
- DAX
- Conditional Formatting

### Data Cleaning Process
To clean this data, I carried out the following steps
- imported this data into power query and renamed the file
- Confirmed the headers are named appropriately
- Ensured the data type is correctly assigned to each column 

### Data Analysis
I loaded this clean data into Excel, and used Pivot table to summerize this data. This data summerization provided me with insight into the objective of this analysis. Using the pivot table, i carried out an exploratory data analysis to extract the following information
- Total number of leads recorded
- Lead distribution and conversion rate across Sales Executives
- Lead distribution and conversion rate by Gender
- Breakdown of leads by sales status
- lead distributed and conversion rate across branches (states)
- Lead distribution and conversion rate by property type
- Lead inspection outcomes (Yes / No), and conversion rate

### Key Insight
From this analysis here are 7 key insights genetated;
- The company had a conversion rate of 43.5%
- The company had a total lead of 193, total paid of 84 and pending leads of 109
- None of the leads were interested in buying industrial properties
- Most of the buying customer were males
- Most females were either not interested, suggested they will buy next time, or said the property was too expensive
- Lagos has the highest paying clients
- Clients that eventually bought properties were clients that went for inspection. Inspection played a great role in motivating the leads to purchase the properties
- Porthacourt Lead went for inspection more based on lead distribution, however most of the paid clients came from lagos. Lagos are more action takers.
- For the sales executives, Funmi had the highest lead distribution, and Olumide had lowest at 27 leads. However, Olumide ensured most of his customers went for inspection. we can't say Olumide did outstandly well, because overall, he had more male leads, and this gave him higher conversation rate. Same goes to Funmi, most of her buying clients were males. 16/20 males for funmi bought, and 14/16 malesfor Olumide bought. Olumide and Funmi did well, however Olumide outperformed Funmi

### Business Recommendation
Here are some recommendations;
Usin the Pareoto principle strategy, the 80/20 rule which states that 80% of the results come from 20% of the imputes. I would recommend that
- Emerald Enterprise should focus on more residendial properties
- Target more of males leads
- Ensure that most of leads generated go for inspection
- Since most of the buying clients come from lagos, Emerald properties should invest in acquiring more properties in Lagos.
- Since most of the females that paid came from Portharcourt, Emerald properties could provide more demographics on these females to understand why they purchased and target such females in Port harcourt and other regions 
