# Fashion_Trends_Analysis

This dataset explores winter fashion styles and trends from 2023 to 2025, featuring over 150 clothing and accessory items from popular global brands.
It aims to provide insights into how materials, colors, prices, and styles influence popularity and customer ratings across winter seasons.
---
## 1.Data set content
Raw data from kaggle: https://www.kaggle.com/datasets/shayanzk/winter-fashion-and-trends?resource=download contains the following information (data downloaded 10/11/2025):
- ID Unique: identifier for each fashion item
- Brand: Fashion brand (e.g., Zara, H&M, Uniqlo)
- Category: Type of winter item (Jacket, Boots, Scarf, etc.)
- Color: Main color of the product
- Material: Primary fabric/material used
- Style: Style category (Casual, Sporty, Luxury, etc.)
- Gender: Target audience (Men, Women, Unisex)
- Season: Season year of the trend (Winter 2023–2025)
- Price (USD): Retail price in USD
- Popularity_Score: Popularity rating from 1 to 10
- Customer_Rating: Average customer rating (2.5–5.0)
- Trend_Status: Indicates whether the item is Trending, Classic, Emerging, or Outdated
--- 
## 2.Project motivation and objectives:
### Motovation:
- Understanding winter fashion trends helps brands to forecast desired styles, colours, and material, maximise profits and reduce waste and overstock.
- Provides a competitive advantage within similar market segments.
- E-commerce platforms can utilise to improve personalised recommendations.
- Price optimisation of clothes
### Objectives:
1. **Classify fashion brands into market segments**  
   **Hypothesis 1:** Online research and data comparison will show similar classification patterns.
2. **Identify trending colours, materials, and styles over the last three winter seasons**  
   **Hypothesis 2:** Neutral tones, natural material, and luxury styles will be more prominent in high-end markets; the latter is expected for fast/basic fashion.
3. **Assess whether higher prices correlate with customer satisfaction**  
   **Hypothesis 3:** More expensive items generally have higher customer satisfaction.
4. **Examine whether gender or trend status affects item price**  
   **Hypothesis 4:** Female clothing items and trending/ Emerging items are typically the most expensive.
--- 
## 3. Project structure and logic
- The dataset will be downloaded from Kaggle and loaded into the JupyterNotebook. After that, it will be cleaned and prepared so it’s in the right format for the analysis or if it needs to be used forfuture work. Once the data is ready, Exploratory Data Analysis (EDA) will be carried out to look at methods of classification, check for outliers and understand correlation and distribution between variables. Finally, visualisations will be created to show how the variables relate to each other, understand trend and validate the hypothesis.
--- 
## 4. Visualisation techniques
- **Hypothesis 1:** Heatmaps were used to compare the price point of different clothing items against different brands. This would helo classify brands to 'High-End', 'Mid-range' and 'Basic Fashion' according to the different price points 
- **Hypothesis 2:** Various Box plot graphs were used to distinguish the trends in colour, style and material used for various market segments.
- **Hypothesis 3:** Scatter matrices used to understand the correlation between price, customer rating and popularity score of clothing items.
- **Hypothesis 4:** Histogram and kde graphs were used to assess the relationship between price vs gender and price vs trend status at vaarious market segments.
--- 
## 5. Summary of findings
- **Hypothesis 1:** 
- **Hypothesis 2:** 
- **Hypothesis 3:** 
- **Hypothesis 4:** 
## 6. Ethical considerations
## 7. Development roadmap and future works 
## 8. Credits
