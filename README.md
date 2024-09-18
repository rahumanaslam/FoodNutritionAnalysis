# Food Nutrition Analysis

This repository contains an analysis of food nutrition data using the Open Food Facts dataset. The analysis focuses on various aspects such as additives, brands, products, proteins, fats, sugars, and fibers. The project uses Python with packages like Pandas, PySpark, and Plotly for data processing and visualization.

## Dataset

The data is sourced from the [Open Food Facts dataset on Kaggle](https://www.kaggle.com/datasets/openfoodfacts/world-food-facts). The dataset includes information on:

- Additives
- Brands
- Products
- Proteins
- Fats
- Sugars
- Fibers

  The data can be downloaded and placed in the "data" folder. The final analysis plots are present in the "plots" folder.

## Requirements

To run the analysis, you'll need the following packages:

- pandas
- pyspark
- plotly

## Analysis

![Number of Products by Brands](https://github.com/rahumanaslam/FoodNutritionAnalysis/blob/main/plots/number_of_products_by_brands.png)
The chart shows that **Carrefour** has the most products, followed by **Meijer** and **Auchan**, while **Weis Quality** and **Picard** offer the least. There's a noticeable gap between the top and bottom performers, and most brands fall within a specific product range. Overall, the chart provides a clear picture of product diversity among the brands, helping to identify market leaders, niche players, and growth opportunities.

![Total Additives Added by the Brands](https://github.com/rahumanaslam/FoodNutritionAnalysis/blob/main/plots/total_additives_by_brands.png)

![Number of Additives by name](https://github.com/rahumanaslam/FoodNutritionAnalysis/blob/main/plots/number_of_additives_by_name.png)


![Total Fibers and Proteins by Brands](https://github.com/rahumanaslam/FoodNutritionAnalysis/blob/main/plots/comparison_of_brands_by_total_proteins_and_total_fibers.png)


![Total Sugars and Fats by Brands](https://github.com/rahumanaslam/FoodNutritionAnalysis/blob/main/plots/comparison_of_brands_by_total_sugars_and_total_fats.png)

![](https://github.com/rahumanaslam/FoodNutritionAnalysis/blob/main/plots/ingredient_usage_distribution.png)

