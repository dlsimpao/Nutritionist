# Nutritionist


### Data Sources
---
source | method | rate limits | description
---|---|---|---
[FoodData Central (usda.gov)](https://fdc.nal.usda.gov/api-key-signup) | api, download | 1000 req/hour per IP | "FoodData Central is an integrated data system that provides expanded nutrient profile data and links to related agricultural and experimental research."
[world.openfoodfacts.org/data](https://world.openfoodfacts.org/data) | mongodump*, download | N/A | "Open Food Facts is a food products database made by everyone, for everyone. You can use it to make better food choices, and as it is open data, anyone can re-use it for any purpose."
[Nutritionix API - Home](https://developer.nutritionix.com/) | api | 10 recipe sub/min, 20 text analysis/min | "The Nutritionix API v2 is geared towards making it as easy as possible for a user to track calories they consume while eating, and calories they expend while exercising."  
[Nutrition Analysis API - Edamam](https://developer.edamam.com/edamam-nutrition-api) | api | 400 recipes/month, 4000 texts/month | "This API covers all key use cases related to recipe and food text natural language processing and nutrition analysis. The API employs NLP (Natural Language Processing) which allows for extraction of food entities from unstructured text."
[Food and Grocery Database API - Edamam](https://developer.edamam.com/food-database-api) | api | 100000 calls/month | "Our Food Database API allows you to search for nutrition and diet information within our Food Database."
[Recipe Search API - Edamam](https://developer.edamam.com/edamam-recipe-api) | api | 10000 calls/month | "Our Recipe Search API allows you to search through millions of web recipes and integrate this information into your mobile or web applications."