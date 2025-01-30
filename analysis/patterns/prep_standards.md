# Prep Time Standards

## Base Operations
{
  "vegetable_processing": {
    "dicing": {
      "onions": "10 minutes per kg",
      "carrots": "15 minutes per kg",
      "potatoes": "12 minutes per kg",
      "bell_peppers": "8 minutes per kg"
    },
    "fine_chopping": {
      "herbs": "5 minutes per 100g",
      "garlic": "8 minutes per 100g",
      "ginger": "6 minutes per 100g"
    },
    "julienne": {
      "carrots": "20 minutes per kg",
      "zucchini": "15 minutes per kg",
      "cabbage": "12 minutes per kg"
    }
  },
  "batch_processing": {
    "rice_cooking": "30 minutes per 2kg",
    "bean_soaking": "overnight_required",
    "vegetable_roasting": "45 minutes per full oven"
  },
  "sauce_preparation": {
    "basic_dressing": "5 minutes per liter",
    "complex_sauce": "20 minutes per liter",
    "spice_paste": "15 minutes per kg"
  },
  "assembly_times": {
    "bowls": "2 minutes per serving",
    "wraps": "1.5 minutes per serving",
    "plated_meals": "3 minutes per serving"
  }
}

## Adjustment Factors
{
  "staff_experience": {
    "novice": "multiply_by_2",
    "intermediate": "standard_time",
    "experienced": "multiply_by_0.75"
  },
  "equipment_quality": {
    "sharp_knives": "standard_time",
    "dull_knives": "multiply_by_1.5"
  },
  "batch_size": {
    "small": "standard_time",
    "medium": "multiply_by_0.9",
    "large": "multiply_by_0.8"
  },
  "intoxication_factor": {
    "sober": "standard_time",
    "tipsy": "multiply_by_1.5",
    "drunk": "buddy_system_required"
  }
} 