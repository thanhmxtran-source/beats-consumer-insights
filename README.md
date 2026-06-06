# Consumer Insights Data Analytics: Beats by Dre
 
## Overview
This project looks at consumer reviews of Beats by Dre earphones to pull out actionable insights for product strategy and brand improvement. I examined customer sentiment and benchmarked Beats against key competitors, which helped identify strengths, weaknesses, and emerging market trends that can support data-driven decisions.
 
## Objectives
- Collect Amazon reviews for 2 Beats models and 10 competitor models across major audio brands
- Clean and preprocess raw review data for analysis
- Conduct exploratory data analysis (EDA) to uncover patterns in ratings and engagement
- Perform sentiment analysis to classify customer reviews as positive, negative, or neutral
- Use AI to extract deeper thematic insights from unstructured text
- Benchmark Beats against competitors through comparative analysis and SWOT
## Dataset
- **Source:** Amazon.com (scraped using Python and OxyLabs)
- **Products Analyzed:** 12 earphone models, including Beats Fit Pro, Beats Solo Buds, Sony WF-1000XM5, Bose Ultra Open Earbuds, Samsung Galaxy Buds 2 Pro, JBL Live Pro TWS 2, and others
- **Size:** 1,000+ reviews
- **Key Features:** Rating, review content, helpful count, verified purchase status, timestamp
## Tools & Technologies
- **Language:** Python
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, NLTK (VADER), TextBlob
- **AI:** Gemini AI (required by the externship program)
- **Scraping:** OxyLabs
- **Environment:** Google Colab
## Methodology
1. **Data Collection**: Scraped reviews from Amazon pages 1–15 per product using OxyLabs
2. **Data Cleaning**: Handled missing values, capped outliers in helpful count, removed duplicates, converted categorical variables to numerical
3. **Exploratory Data Analysis**: Computed descriptive statistics, created rating distributions, box plots, scatter plots, and heatmaps
4. **Sentiment Analysis**: Applied VADER to classify reviews; Beats achieved a compound score of 0.80 vs. 0.61 industry average
5. **AI-Generated Insights**: Used Gemini AI to identify key themes, strengths, and weaknesses from review text
6. **Comparative Analysis**: Benchmarked Beats against 7 competitors across sound quality, battery life, comfort, noise cancellation, and price
7. **SWOT Analysis**: Synthesized findings into strategic strengths, weaknesses, opportunities, and threats
## Key Findings
- Beats earbuds have a higher average rating (4.4) compared to the overall dataset average (4.1)
- Beats reviews have a significantly higher average helpful count (15.65 vs. 5.99), suggesting stronger review engagement
- Sentiment analysis revealed an overall positive compound score of 0.80 for Beats products
- Beats Fit Pro outperforms Beats Solo Buds in customer satisfaction
- Key weaknesses include button placement, app reliability, call quality, and noise cancellation relative to competitors like Bose and Sony
## Recommendations
- Relocate and redesign the left earbud button to prevent accidental presses
- Overhaul the Beats app for improved reliability and connectivity
- Invest in noise cancellation technology without compromising sound quality or battery life
- Improve the microphone and sound processing for clearer call quality
- Use more durable materials for the charging case
- Consider adding features like multipoint connectivity and wireless charging to compete with premium rivals
## Disclaimer
This project was completed for a Consumer Insights Data Analytics Externship. Using Gemini AI was required as part of the program.
