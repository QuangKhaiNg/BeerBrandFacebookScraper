

# Brandswatch Data Collection and Analysis Project of Beer brands

## Project Overview  

This project is designed to automate data extraction from web pages and analyze the collected data from 3 beer brands in Vietnam including Heineken, Saigon Beer and 333 Beer performs detailed analysis on the content, hashtags, and emojis to uncover actionable insights. It focuses on analyzing text-based content alongside visual elements like emojis and hashtags to understand trends in audience engagement. Specifically, it focuses on:  
1. **Scraping dynamic web content**: Extracting text, hashtags, and emojis from social media.  
2. **Data analysis**: Exploring trends, identifying high-frequency patterns, and visualizing results for actionable insights.  


### Key Highlights:  
- **Dynamic social media posts scraping**: Automates navigation through multiple pages of web content, handles interactive elements, and ensures complete data capture.  
- **Posts' content analysis**: Identifies common emojis and hashtags, analyzes their frequencies, and visualizes their distribution to provide engagement insights.  
- **Actionable visualizations**: Produces meaningful charts, bar plots, and summaries to support decision-making in marketing and content strategy.  

---

## Project Components  

### 1. Data Collection   


#### Features:  
- **Pagination handling**: Navigates through multiple pages to collect comprehensive datasets.  
- **Content extraction**: Scrapes specific elements like text, hashtags, and emojis from web pages.  
- **Data organization**: Saves extracted data into a structured format (e.g., CSV) for analysis.  

#### Outcomes:  
- A structured dataset containing fields like:  
  - **Post content**: The main body of text from posts.  
  - **Hashtags**: Extracted tags for trend analysis.  
  - **Emojis**: Frequency data for understanding emotional tone or engagement.  
  - **Engagement data**: Metrics like likes, shares, or comments (if applicable).  


### 2. Categorization and Analysis (`analysis.ipynb`)  

#### Content Categorization  

This module categorizes posts into predefined themes to better understand their influence on user engagement metrics.  

**Categories include**:  
- **Promotional Posts**: Focused on discounts, giveaways, and offers.  
- **Event Posts**: Highlighting celebrations, product launches, or special occasions.  
- **CSR Posts**: Addressing corporate social responsibility efforts, including sustainability and community initiatives.  
- **Lifestyle Posts**: Showcasing brand identity or products in aspirational settings.  

#### Analysis Components  

1. **Category-Wise Engagement Analysis**  
   - Calculates average engagement rates (reactions, comments) per category.  
   - Highlights the most and least engaging categories to optimize future strategies.  

2. **Emoji and Hashtag Trends by Category**  
   - Tracks the most frequently used emojis and hashtags for each category.  
   - Analyzes their correlation with engagement metrics to identify successful elements.  

3. **Visualization**  
   - **Bar Charts**: Compare reaction and comment counts across categories.  
   - **Word Clouds**: Highlight key hashtags by category, aiding theme refinement.  

---

#### Outcomes  

1. **Engagement Insights by Category**:  
   - Promotional posts consistently had the highest engagement, driven by clear calls to action like discounts or giveaways.  
   - Event-related posts ranked second, often leveraging celebratory tones with emojis like 🎉 and ✨.  
   - CSR-related posts fostered positive sentiment, strengthening brand reputation.  

2. **Trends and Patterns**:  
   - **Emojis**:  
     - CSR Posts: Emojis like 🌱 and ❤️ reinforced themes of care and sustainability.  
     - Event Posts: Celebration-oriented emojis like 🎈 and 🎶 were prevalent.  
   - **Hashtags**:  
     - Promotional Posts: `#Sale`, `#Giveaway`.  
     - CSR Posts: `#Sustainability`, `#BetterTogether`.  

3. **Strategic Insights**:  
   - Diversifying content with a mix of promotional, event, and lifestyle themes ensures sustained audience interest.  
   - CSR posts, while less frequent, contribute significantly to brand equity and long-term loyalty.  

---


## Tools and Technologies  

- **Scraping**: Selenium (handles dynamic content and interactions).  
- **Data Analysis**: pandas for data manipulation, matplotlib for visualizations.  
- **Environment**: Jupyter Notebooks for an interactive workflow.  



## Applications  

- **Marketing Strategy**: Optimize campaigns by identifying emojis and hashtags that drive engagement.  
- **Content Creation**: Tailor posts to audience preferences based on trend analysis.  
- **Competitive Analysis**: Compare engagement metrics across brands or campaigns.  

---

## Project Limitations and Future Work  

### Limitations:  
- Dynamic content that requires frequent authentication or CAPTCHA handling may need additional customization.  
- The analysis is limited to visual and frequency-based insights; deeper modeling could be implemented for prediction.  

### Future Work:  
- Automate sentiment analysis based on text and emoji patterns.  
- Integrate machine learning for predictive analytics on engagement data.  
- Expand scraping capabilities to include API integration for larger datasets.  
