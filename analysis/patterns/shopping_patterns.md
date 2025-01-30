# Shopping and Storage Patterns

## Ingredient Groupings
{
  "fresh_critical": {
    "shelf_life": "1-3_days",
    "items": ["herbs", "leafy_greens", "ripe_fruits"],
    "storage": "refrigerated",
    "backup_plan": "frozen_alternatives"
  },
  "fresh_stable": {
    "shelf_life": "5-7_days",
    "items": ["root_vegetables", "cabbage", "citrus"],
    "storage": "cool_dry",
    "backup_plan": "adjust_menu"
  },
  "dry_goods": {
    "shelf_life": "months",
    "items": ["grains", "legumes", "spices"],
    "storage": "sealed_containers",
    "backup_plan": "alternative_grain"
  }
}

## Order Timing
{
  "fresh_produce": {
    "order_lead": "2_days",
    "frequency": "2x_week",
    "typical_vendors": ["food_lovers", "woolies"],
    "backup_vendors": ["macro"]
  }
} 