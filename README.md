# LITE Trainer Food Database (JSON)

A curated JSON food database used by LITE Trainer Coaching.  
Our database is bilingual and contains macronutrients based on 100g of each food.
**Use:** free to use (CC0) — see LICENSE.

## What’s inside
- `ingredients.json` — array of food objects. Example item:
```json
{
  "id": "local-35",
  "es_product_name": "Leche Entera",
  "en_product_name": "Whole Milk",
  "category": { "en": "Cheese & Dairy", "es": "Quesos y Lácteos" },
  "nutriments": {
    "energy-kcal_100g": 61,
    "proteins_100g": 3.2,
    "carbohydrates_100g": 4.8,
    "fat_100g": 3.3
  },
  "foodMeasures": [
      {"es_disseminationText": "Vaso", "en_disseminationText": "Cup", "gramWeight": 250, "measureId": 1062}
  ]
},

### Attribution Example
If you use this database, please credit it as:

> "Food Database by LITE Trainer, available at www.litetrainer.com/resources/food-db"


## License
This food database is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to use, share, and adapt this database, but **you must provide attribution** by linking back to LITE Trainer at www.litetrainer.com.


