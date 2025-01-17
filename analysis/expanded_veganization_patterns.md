# Extended Veganization Matrix

## Egg Replacements
{
  "binding": {
    "options": [
      {
        "name": "ground_flax",
        "ratio": "1tbsp:3tbsp_water",
        "notes": "common_in_codebase",
        "best_for": ["cookies", "breads", "pancakes"]
      },
      {
        "name": "chia_seeds",
        "ratio": "1tbsp:3tbsp_water",
        "notes": "higher_omega3",
        "best_for": ["muffins", "quick_breads"]
      },
      {
        "name": "potato_starch",
        "ratio": "2tbsp:3tbsp_water",
        "notes": "neutral_flavor",
        "best_for": ["light_baked_goods"]
      },
      {
        "name": "cornstarch",
        "ratio": "2tbsp:3tbsp_water",$$
        "found_in_codebase": true,
        "best_for": ["custards", "sauces"]
      }
    ]
  },
  "leavening": {
    "options": [
      {
        "name": "aquafaba",
        "source": "chickpea_liquid",
        "ratio": "3tbsp_per_egg",
        "found_in_codebase": true,
        "notes": "chickpeas_common_ingredient"
      },
      {
        "name": "carbonated_water",
        "ratio": "60ml_per_egg",
        "best_for": ["light_batters", "waffles"]
      },
      {
        "name": "baking_soda_vinegar",
        "ratio": "1tsp:1tbsp",
        "found_in_codebase": true,
        "best_for": ["quick_breads", "cakes"]
      }
    ]
  }
}

## Dairy Alternatives
{
  "milk": {
    "options": [
      {
        "name": "oat_milk",
        "found_in_codebase": true,
        "best_for": ["baking", "sauces", "drinks"],
        "notes": "most_sustainable"
      },
      {
        "name": "soy_milk",
        "best_for": ["high_protein_needs", "baking"],
        "notes": "protein_content_similar_to_dairy"
      },
      {
        "name": "cashew_milk",
        "best_for": ["creamy_sauces", "soups"],
        "notes": "no_straining_required"
      }
    ]
  },
  "cream": {
    "options": [
      {
        "name": "coconut_cream",
        "found_in_codebase": true,
        "best_for": ["curries", "desserts"]
      },
      {
        "name": "cashew_cream",
        "ratio": "1cup_cashews:3cups_water",
        "best_for": ["savory_sauces", "soups"]
      },
      {
        "name": "silken_tofu_cream",
        "ratio": "1cup_tofu:1/4cup_liquid",
        "found_in_codebase": true,
        "best_for": ["dressings", "dips"]
      }
    ]
  }
}

## Texture Enhancers
{
  "umami_builders": {
    "options": [
      {
        "name": "nutritional_yeast",
        "found_in_codebase": true,
        "applications": ["cheese_flavor", "sauces"]
      },
      {
        "name": "miso_paste",
        "applications": ["broths", "marinades"]
      },
      {
        "name": "mushroom_powder",
        "applications": ["stocks", "gravies"]
      },
      {
        "name": "seaweed",
        "types": ["nori", "kombu", "wakame"],
        "applications": ["broths", "fish_flavor"]
      }
    ]
  },
  "protein_textures": {
    "options": [
      {
        "name": "tvp",
        "found_in_codebase": true,
        "best_for": ["ground_meat_replacement"]
      },
      {
        "name": "seitan",
        "base": "vital_wheat_gluten",
        "best_for": ["sliced_meat_replacement"]
      },
      {
        "name": "jackfruit",
        "best_for": ["pulled_meat_texture"]
      },
      {
        "name": "tempeh",
        "best_for": ["firm_protein_needs"]
      }
    ]
  }
} 