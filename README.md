<<<<<<< HEAD
# Team-Belize-Live-Project-1

=======
# Analyzing Indian Startup Funding: A Comprehensive Data-Driven Approach
Startups play a vital role in driving economic growth, technological advancement, and innovation. Over the years, Indian startups have captured the attention of investors globally, making the country one of the largest startup ecosystems. However, understanding the funding patterns, particularly in the technology sector, has become crucial for investors, entrepreneurs, and policymakers.

In this project, I set out to analyze funding data from Indian startups over a period of four years (2018–2021), with a specific focus on identifying trends in technology versus non-technology sectors. By leveraging Python’s data analysis capabilities and statistical tools, I aimed to gain insights into the nature of startup funding. 

## Objective of the Project
The core objective of the project is to comprehensively analyze the Indian Startup Ecosystem from 2018 to 2021, identify key trends and insights and provide data driven recommendations for strategic entry 

Dataset Overview
The dataset used in this project comprises funding data for Indian startups across different sectors and years. The data includes key information such as:

Startup Sector
Funding Amount
Year of Funding
This information provides a rich ground for uncovering insights into how funding flows into various industries.

The Approach
To carry out the analysis, I adopted the following steps:

# 1. Classifying Sectors: Tech vs. Non-Tech
One of the challenges was to classify the startups into broad categories: Tech and Non-Tech. I created a list of technology-related keywords such as "AI", "cloud", "fintech", and "e-commerce". Any startup with a sector description containing these keywords was classified as "Tech," while the rest were categorized as "Non-Tech."

The classification was done using Python’s pandas library, with a custom function that scanned each sector description for the presence of these keywords.This classification allowed me to perform the next steps of the analysis, comparing the funding between these two broad categories.

2. Funding Distribution Analysis
Once the classification was complete, I calculated the total funding raised by both Tech and Non-Tech startups. This was achieved using simple group-by operations, summing the funding amounts across each category.

3. Statistical Analysis: Is There a Difference?
The next step was to assess if there was a statistical difference in the funding amounts between tech and non-tech startups. For this, I performed an independent t-test, a common statistical test to compare the means of two groups.

This test gave us an important insight into whether investors favor technology-driven startups more than their non-tech counterparts.

# Results and Key Insights
Funding Distribution:
Tech startups consistently attract a larger share of total funding across the years.
The funding gap between tech and non-tech sectors is significant, with tech startups often raising higher amounts of capital per round.
# Statistical Significance:
The independent t-test showed a p-value lower than 0.05, indicating a statistically significant difference in the funding amounts between technology and non-technology startups. In simpler terms, this means that tech startups tend to attract more funding, and this observation is not due to random chance.
# Implications for Investors:
Investors looking for high-growth opportunities should continue focusing on technology sectors such as AI, e-commerce, and cloud computing.
However, it’s important not to overlook non-tech sectors, as they still attract a considerable share of the investment and offer diverse opportunities.
Visualizing the Data

# Challenges Faced
Data Standardization: Startup sector names were often inconsistent, requiring preprocessing before analysis.
# Conclusion
This project highlights the growing dominance of technology startups in the Indian startup ecosystem. While non-tech startups are still relevant and receive substantial funding, the clear trend towards investing in tech-driven companies cannot be ignored. As technology continues to evolve, we expect even more capital to flow into areas such as AI, blockchain, and cloud computing.






>>>>>>> 1dcd670d702cf7441b6c3d33fa1caee606ea7065