# Data-Analysis-of-Real-world-Mobiles-under-20K-
This repository contains a data analysis project focused on mobile phones available on Flipkart for under ₹20,000. The primary objective was to collect real-world data, perform a comprehensive analysis, and derive actionable insights to help consumers make informed purchasing decisions.
Data Collection
The dataset was gathered by applying web scraping techniques to the Flipkart website. The process specifically targeted mobile phones within the specified price range, extracting key information such as:

Model and Brand

Price and Discount

User Ratings

Battery Capacity

Network Type (e.g., 2G, 4G, 5G)

Operating System Interface (OSI)

Analysis & Methodology
The analysis follows a standard data science workflow:

Data Cleaning: The raw scraped data was cleaned by handling missing values (e.g., in the 'Rating' and 'OSI' columns) and standardizing data types.

Feature Engineering: New features like Status (to identify "Suggested" phones based on battery and network type) and Type (to differentiate between "Smart Mobiles" and "Keypad Mobiles") were created to enhance the analysis.

Exploratory Data Analysis (EDA): Visualizations were created to explore trends in brand popularity, price distribution, and the performance of phones in different categories.

Key Findings
The analysis produced several clear recommendations for consumers:

POCO is a top-performing brand in the smartphone category, offering an excellent combination of battery life and network compatibility.

REDMI stands out as the leading brand for users seeking a balance of good quality, high user ratings, and frequent discounts, making it a highly "affordable" choice.

ITEL is a strong contender in the keypad phone segment, catering to users who prioritize simplicity and essential features.

Technologies Used
Python: The core programming language for the analysis.

Pandas: Used for data manipulation, cleaning, and preparation.

Numpy: Employed for numerical operations.

Matplotlib: Utilized for creating various data visualizations.

Seaborn: Used for generating informative and aesthetically pleasing statistical graphics.
