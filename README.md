# Sephora Product Analysis Report

## Overview
This project analyzes Sephora's product dataset, focusing on understanding product ratings, price distribution, and consumer engagement (as measured by favourites/loves). The analysis also explores high-priced skincare products with positive reviews, top-rated products and brands, and category-wise average ratings to identify key trends.

## Data Overview
The dataset includes various attributes like product IDs, names, brands, prices, ratings, favourites, reviews, and categories. Below are the key attributes used in the analysis:
- **Product ID**: Unique identifier for each product.
- **Product Name**: Name of the product.
- **Brand Name**: Name of the brand associated with the product.
- **Price (USD)**: Product price in US dollars.
- **Rating**: Customer rating (0 to 5).
- **Favourites (Loves)**: Number of times the product was marked as a favourite.
- **Reviews**: Total number of customer reviews.
- **Primary/Secondary/Tertiary Category**: Categories and subcategories to which the product belongs.

## Key Statistics
- **Average Rating**: 4.2 (range: 1.0 to 5.0)
- **Average Price**: $51.66 (range: $3.00 to $1900.00)

Most products are rated between 3.9 and 4.5, with prices predominantly ranging from $25.00 to $58.00.

## Data Cleaning and Transformation
- **Missing Values**: Rows with missing ratings or reviews were removed.
- **Duplicate Records**: No significant duplication was found.
- **Data Formatting**: Uniform formatting applied to product and brand names.
- **Data Subsetting**: Specific subsets were created for in-depth analysis (e.g., skincare products).

## Analysis Summary

### 1. Distribution of Product Ratings
- Most products are rated between 4.0 and 4.5, indicating generally favorable customer feedback.

### 2. Price vs. Rating
- A scatter plot showed no strong correlation between higher prices and higher ratings, suggesting price alone does not dictate product satisfaction.

### 3. Top 10 Highest-Rated Products
- Highest-rated products include the **Delikate Try Me Kit** by Kate Somerville and the **Good Girl Gone Bad Eau Fraîche** by Kilian Paris, all rated 5.0.

### 4. Top 10 Brands by Average Rating
- **Erno Laszlo**, **Aquis**, and **Macrene Actives** are the top brands, each averaging a rating above 4.8.

### 5. High-Priced Products with Positive Reviews
- High-end products like **Crème de la Mer Moisturizer** (La Mer) and **Ultimate Revival Cream** (SK-II) received positive ratings despite their high prices.

### 6. Average Ratings by Product Category
- The highest-rated category is **Gifts** (4.56), while the lowest is **Mini Size** (4.00).

## Business Recommendations
1. **Focus on High-Performing Categories**: Emphasize marketing efforts on the Gifts category, which has the highest average ratings.
2. **Improve Low-Rated Products**: Investigate and improve products in the Mini Size category, which has the lowest average rating.
3. **Gather Customer Feedback**: Conduct surveys for lower-rated products (e.g., Mini Size) to understand customer pain points.
4. **Launch New Products and Bundles**: Consider releasing new products in high-performing categories or offer cross-category bundles.

## Conclusion
The analysis shows that Sephora’s product ratings are generally high, and pricing doesn’t strongly influence customer satisfaction. These insights can guide Sephora in product development, marketing strategies, and improving customer experience.
## Acknowledgments

Dataset sourced from [Sephora](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews).
