# Temperature States

## Storage Categories
{
  "frozen": {
    "hard_frozen": {
      "temperature": "-18C",
      "max_time": "1_week",
      "color_code": "dark_blue"
    },
    "soft_frozen": {$$
      "temperature": "-5C",
      "max_time": "3_days",
      "color_code": "light_blue"
    }
  },
  "chilled": {
    "refrigerated": {
      "temperature": "4C",
      "max_time": "24_hours",
      "color_code": "green"
    },
    "service_temp": {
      "temperature": "8C",
      "max_time": "4_hours",
      "color_code": "light_green"
    }
  },
  "hot": {
    "hot_hold": {
      "temperature": "63C_plus",
      "max_time": "4_hours",
      "color_code": "red"
    },
    "cooking": {
      "temperature": "varies_by_recipe",
      "max_time": "recipe_specific",
      "color_code": "dark_red"
    }
  }
} 