# LITE Trainer Food Database (JSON)

A curated JSON food database used by LITE Trainer Coaching.  
Our database is bilingual and contains macronutrients based on 100g of each food.
**Use:** free to use (CC0) — see LICENSE.

## What’s inside
- `food.json` — array of food objects. Example item:
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
