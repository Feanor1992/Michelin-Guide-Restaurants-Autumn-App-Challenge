# Michelin-Guide-Restaurants-Autumn-App-Challenge
This project delves into the [**Michelin Star Restaurant Guide dataset**](https://www.kaggle.com/datasets/ngshiheng/michelin-guide-restaurants-2021/data) to uncover insightful patterns related to restaurant distribution, pricing, and culinary offerings worldwide. By leveraging data preprocessing techniques and exploratory data analysis (EDA), Ш aim to provide a comprehensive understanding of how Michelin-starred restaurants vary across different regions and cuisines. The culmination of this project is an interactive Dash application that visualizes restaurant data on a map, utilizing Plotly’s transition to MapLibre for an enhanced visual experience.

Key Steps:
1. Data Preprocessing:
    - Null Value Handling: Rows with missing values are removed to ensure data integrity.
    - Column Transformations: Various columns are converted to string types for better interpretability and analysis. Notably, the 'Award' column values are recoded for consistency, simplifying further analysis.
2. Exploratory Data Analysis (EDA):
    - Patterns in Restaurant Names: We analyze the length and word count of restaurant names to identify naming trends and their implications.
    - Average Price Levels by Cuisine: By filtering cuisines with at least 50 restaurants, we compute and visualize the average price levels associated with different types of cuisine.
    - Regional Analysis: The project also includes an assessment of Michelin-starred restaurants by country, highlighting the top countries with the most Michelin-rated establishments.

Tools and Libraries Used:
- Pandas: For efficient data manipulation and cleaning.
- Plotly: To create engaging and interactive visualizations.
- Dash: To develop the web application interface for user interaction.
- MapLibre: For dynamic map visualizations that enhance the user experience.

Interactive Dashboard:
The final application features an interactive layout allowing users to filter restaurant data by cuisine type and visualize:
- Restaurant Locations: A map displaying Michelin-starred restaurant locations.
- EDA Results: Visualizations showing patterns in restaurant names, average price levels by cuisine, and distribution of restaurant names.
