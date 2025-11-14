# Fashion_Trends_Analysis

- This dataset explores winter fashion styles and trends from 2023 to 2025, featuring over 150 clothing and accessory items from popular global brands.
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
- Limitations: The data set was quite small and could be improved by having a larger data set with more of the same clothing item to allow better comparisons of the various variables
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
- All steps were performed in Python (version 3.10) via VScode using Jupyter Notebook. The initial preprocessing steps were performed with pandas and NumPy python modules. Data visualisation was performed with matplotlib and seaborn. 
--- 
## 4. Visualisation techniques
- **Hypothesis 1:** Heatmaps were used to compare the price point of different clothing items against different brands. This would helo classify brands to 'High-End', 'Mid-range' and 'Basic Fashion' according to the different price points 
- **Hypothesis 2:** Various Box plot graphs were used to distinguish the trends in colour, style and material used for various market segments.
- **Hypothesis 3:** Scatter matrices used to understand the correlation between price, customer rating and popularity score of clothing items.
- **Hypothesis 4:** Histogram and kde graphs were used to assess the relationship between price vs gender and price vs trend status at vaarious market segments.
--- 
## 5. Summary of findings
- **Hypothesis 1:** The classification system was based on online research/ AI tool and data analysis of the price range of brands. The reults showed some inconsistency, therefore, a fair judgement was made between the discrepancies mostly favoring data analysis. **H1: Not true**
- **Hypothesis 2:** High-End brands favored bolder colors, natural materials and luxury style to show case exclusivity, Mid-range brands chose more neutral tones with blended material focusing on sporty clothes. Basic fashion brand used most colours, synthetiic materials and a wide range of styles to appeal to more of the market. **H2: Mostly true showing some variation in colour** 
- **Hypothesis 3:** There was no or very weak correlation between Price, Customer rating and popularity score of the data. **H3: Not true**
- **Hypothesis 4:** Gender did not impact the price of an item. Trend status had minimal influence with trending and emerging prices at a higher price range. Additionally, price did not imapct market segment either. **H4: Mostly not true, trending items shown to be more expensive**
--- 
## 6. Ethical considerations
- GDPR was followed by ensuring any personally identifying information (PII) was not included in the analyses.
--- 
## 7. Development roadmap and future works 
- Re-classify the brand market segments using more detailed data, but perhaps comparing the price of the same clothing item. Alternatively, look at material quality prestige index.
- Apply machine learning techniques to predict trends for each market segment.
---
## 8. Credits
- Code Institute teaching materials from the ‘Data Analytics with AI Bootcamp 2025’-Newham cohort course were used.
- AI Tools such as Chatgpt/ Gemini used to debug code, and online research for brand classification. 
- Kaggle for providing the data set.
