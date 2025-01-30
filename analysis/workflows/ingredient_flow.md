# Ingredient Flow Analysis

## Shared Prep Opportunities
{
  "morning_vegetable_prep": {
    "candidates": ["onions", "carrots", "peppers"],
    "storage_method": "sealed_container",
    "max_hold_time": "8_hours",
    "benefits": ["reduced_prep_time", "better_station_utilization"]
  },
  "batch_cooking": {
    "candidates": ["rice", "beans", "roasted_vegetables"],
    "storage_method": "hot_hold",
    "max_hold_time": "4_hours",
    "benefits": ["reduced_equipment_conflicts", "better_timing_control"]
  }
}

## Cross-Recipe Dependencies
{
  "shared_bases": {
    "aromatic_base": {
      "components": ["onion", "garlic", "oil"],
      "used_in": ["curry", "stir_fry", "stew"],
      "prep_notes": "can_prepare_in_bulk"
    },
    "grain_base": {
      "components": ["rice", "quinoa"],
      "used_in": ["buddha_bowl", "stir_fry", "curry"],
      "prep_notes": "stagger_cooking_times"
    }
  }
}

## Implementation Notes
1. Color coding system needs to account for:
   - Multiple meals per day
   - Multiple components per meal
   - Clear visual distincti
   - on
   - Temperature states
   - Prep stages

2. Prep categories to consider:
   - Hard frozen (1 week)
   - Soft frozen (3 days)
   - Refrigerated (24 hours)
   - Room temp (day of)
   - Made to order

3. Assembly instruction format:
   - Step number
   - Components needed (by color/ID)
   - Time requirement
   - Critical temperature points
   - Quality check points 