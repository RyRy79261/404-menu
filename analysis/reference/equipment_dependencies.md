# Equipment Dependencies Analysis

## Critical Equipment Paths
{
  "high_heat_cooking": {
    "stove_tops": {
      "concurrent_usage_max": 4,
      "recipes_requiring": ["stir_fry", "curry", "risotto"],
      "typical_duration": "15-30min",
      "bottleneck_risk": "high"
    },
    "ovens": {
      "concurrent_usage_max": 2,
      "recipes_$$requiring": ["fritters", "roasted_vegetables"],
      "typical_duration": "20-45min",
      "bottleneck_risk": "medium"
    }
  },
  "prep_stations": {
    "cutting_boards": {
      "concurrent_usage_max": 6,
      "cleaning_frequency": "between_ingredients",
      "cross_contamination_risk": "medium"
    }
  }
} 