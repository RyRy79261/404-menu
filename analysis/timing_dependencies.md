# Timing Dependencies

## Meal Sequence Analysis
{
  "breakfast_patterns": {
    "prep_start": "6:00",
    "serve_by": "8:00",
    "common_constraints": {
      "fresh_fruit_prep": "last_15_minutes",
      "hot_items": "staggered_cooking",
      "cold_items": "prep_ahead"$$
    }
  },
  "dinner_patterns": {
    "prep_start": "16:00",
    "serve_by": "19:00",
    "common_constraints": {
      "rice_cooking": "start_first",
      "vegetable_prep": "parallel_processing",
      "sauce_making": "during_main_cook"
    }
  }
} 