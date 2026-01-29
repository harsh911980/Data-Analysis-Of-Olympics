# Data-Analysis-Of-Olympics
Interactive Olympics data analysis web app built using Python &amp; Streamlit, featuring medal tally insights, country &amp; athlete analysis, rich visualizations, and ML-based medal prediction.

This project is an interactive data analysis and visualization web application developed using Python and Streamlit.
It explores historical Olympics data to analyze medal tallies, country-wise performance, athlete statistics, and participation trends across different Olympic editions.
The application also integrates a Machine Learning model to predict medal outcomes based on athlete attributes.

🧠 Key Functionalities
🥇 Medal Tally Analysis

Year-wise and country-wise medal tally

Overall and filtered medal performance

Dynamic selection using Streamlit sidebar

📊 Overall Olympics Analysis

Total Olympic editions, host cities, sports, events, athletes, and nations

Trends of participating nations, events, and athletes over time

Heatmap visualization showing number of events per sport across years

Identification of most successful athletes

🌍 Country-wise Analysis

Medal trend of a selected country over the years

Sport-wise performance using heatmap visualization

Top performing athletes of a selected country

🧍 Athlete-wise Analysis

Age distribution of all athletes and medalists (Gold, Silver, Bronze)

Sport-wise age distribution of gold medalists

Height vs Weight analysis based on sport, gender, and medal

Male vs Female participation trends across Olympic years

🤖 Machine Learning Integration

Machine Learning model loaded using pickle

Predicts medal outcome based on:

Age

Height

Weight

Integrated directly into the Streamlit UI

🗂 Dataset Used

athlete_events.csv – athlete details, events, medals, age, height, and weight

noc_regions.csv – country/region mapping for NOC codes
