# Unicorn-Dataset-Analysis
Analysis of the Unicorn companies dataset

This project involves performing a basic exploratory data analysis of the features of the Unicorn Companies dataset and coming up with data driven overall recommendations to help Unicorn Companies in creating good business models and making decisions that will focus on companies with high growth potential, diversify investment portfolio and prioritize companies with experienced leadership teams.

Recommended Analysis

1. Which unicorn companies have had the biggest return on investment?
2. How long does it usually take for a company to become a unicorn? Has it always been this way?
3. Which countries have the most unicorns? Are there any cities that appear to be industry hubs?
4. Which investors have funded the most unicorns?

Steps taken:

Loaded the data into a DataFrame using pd.read_csv(). Calculated the return on investment (ROI) for each company. Displayed the top 5 companies by ROI. Calculated the number of years it takes for a company to become a unicorn by subtracting the 'Year Founded' column from the 'Year Joined' column. Replaced any negative values with 0 and calculated the average number of years it takes for a company to become a unicorn. Grouped the DataFrame by country and summed the valuation values. Selected the top 10 countries by valuation and created a bar chart using Plotly Express.

Challenges faced:

I encountered some challenges during data analysis like handling missing data, choosing appropriate statistical methods, and interpreting results accurately. But I managed well.
