# Microsoft Movie Studio Analysis

## Problem Statement
Microsoft plans to launch a new movie studio to compete in the original video content market. However, they lack expertise in film production and need data-driven insights to make informed decisions. This project aims to analyze box office performance and identify key factors contributing to movie success. By leveraging datasets from Box Office Mojo and TMDb, the goal is to determine which genres, budget allocations, and marketing strategies are most effective. These insights will guide Microsoft's content creation strategy, ensuring the new studio produces commercially successful films.

## Main objectives 
The main objective of this project  is to identify prevalent box office trends and audience preferences across genres, providing strategic direction for Microsoft's new movie studio to create compelling, commercially successful films that resonate with audiences and differentiate the brand in the market.

## Specific objectives 
Certainly! Here are the specific objectives;

1. Identifying  the top-performing genres based on domestic and international gross revenues.
2. Determining  the correlation between budget, popularity, and total gross revenue.
3. Analyzing  audience engagement metrics such as vote count and popularity to understand their impact on box office performance.
4. Create visualizations to effectively communicate key findings and insights to stakeholders.
5. Use these visualizations to support strategic decision-making for the new movie studio.
6. Generating  actionable insights on which genres and types of films to prioritize.
7. To Offer recommendations on optimal budget allocation, marketing strategies, and audience engagement techniques.
8. Suggesting  strategies for Microsoft’s new movie studio to enable them to maximize revenue and market share.

## Datasets
The datasets that have been used in this project include ;
- **Box Office Mojo**
- **TMDb**
You might as why this two datasets and here is why;
1. The datasets provide comprehensive Insights:
For Box Office Mojo: It provides a detailed financial performance data (domestic and foreign gross).
The TMDb: It adds rich movie metadata (budget, popularity, vote average, vote count, genres).

2. Combining financial and descriptive data enables a more accurate and holistic analysis of factors driving movie success.

3.Integration allows analysis of both quantitative metrics (gross revenue, budget) and qualitative metrics (popularity, audience ratings).

4. Lastly the two  provide a multi-faceted view, leading to comprehensive strategic insights for Microsoft’s new movie studio.

By leveraging both datasets, the analysis gains depth and breadth, ensuring well-rounded and data-driven recommendations for Microsoft’s movie studio.

### Data Preparation/Cleaning
In preparing the data for analysis , several steps were taken to ensure the data's quality, relevance, and reliability. Here's an overview of the data preparation process and the reasoning behind the decisions made:

1.Handling Missing Values
In Box Office Mojo-  rows with missing 'studio' values were dropped to ensure completeness.
In TMDb: rows with missing values in critical columns like 'vote_average', 'vote_count', and 'genres' were dropped. 

2. Converting Data Types
financial columns such as 'domestic_gross' and 'foreign_gross' were converted from strings to numeric data types for accurate calculations and analysis.

3. Handling Non-Numeric Data
Ensured that only numeric columns were used for correlation and regression analysis to avoid errors and improve model performance.

4. Merging the Datasets 
 merging was done  on the 'title' column to combine financial performanace data with the movie metadata.

## Data Analysis and Visualizations
### Correlation Analysis
- High correlation between domestic, foreign, and total gross.
- Insights: Focus on both domestic and international markets for broad appeal.



### Visualizations
- **Correlation Matrix**: Shows relationships between key variables.
- **Scatter Plots**: Visualize relationships between budget, popularity, vote average, and total gross.
- **Bar Plots**: Display average gross by genre and top 10 performing movies.

## Insights and Recommendations
- **Top Genres**: Action, Adventure, Animation, Family.
- **High Production Value**: Invest in quality production, renowned directors, and star-studded casts.
- **Franchise Potential**: Develop or acquire intellectual properties with potential for sequels.
- **Audience Engagement**: Focus on compelling storytelling and engaging characters.
- **Genre Blending**: Experiment with genre combinations for broader appeal.
- **Global Appeal**: Create films that resonate with international audiences to maximize revenue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [Box Office Mojo](https://www.boxofficemojo.com/)
- [TMDb](https://www.themoviedb.org/)

## Questions
If you have any questions or would like to discuss further, please open an issue or contact me directly.
