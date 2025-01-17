# Extended Cheese Behavior Analysis

## Application-Specific Matrices
{
  "pizza_cheese": {
    "stretchy_base": {
      "components": {
        "protein": {
          "primary": "cashews",
          "alternatives": ["blanched_almonds", "sunflower_seeds"],
          "ratio": "2_parts"
        },
        "starch": {
          "primary": "tapioca",
          "alternatives": ["potato_starch", "corn_starch"],
          "ratio": "0.5_parts",
          "activation_temp": "85C"
        },
        "fat": {
          "primary": "refined_coconut_oil",
          "alternatives": ["cacao_butter"],
          "ratio": "0.5_parts"
        },
        "flavor_builders": {
          "umami": ["nutritional_yeast", "miso"],
          "acid": ["lactic_acid", "citric_acid"],
          "salt": "2%_total_weight"
        }
      },
      "technique": "high_speed_blend_heat_activate"
    },
    "browning_layer": {
      "components": {
        "protein": {
          "primary": "soy_milk_powder",
          "alternatives": ["pea_protein"],
          "ratio": "1_part"
        },
        "fat": {
          "primary": "coconut_oil",
          "ratio": "1_part"
        },
        "starch": "minimal_to_none",
        "flavor_builders": {
          "umami": "mushroom_powder",
          "salt": "2.5%_total_weight"
        }
      },
      "technique": "top_layer_application"
    }
  },
  "sauce_bases": {
    "carbonara": {
      "components": {
        "starch": {
          "primary": "potato_starch",
          "ratio": "2_parts",
          "activation": "gradual_heat"
        },
        "fat": {
          "primary": "cashew_cream",
          "ratio": "3_parts"
        },
        "umami": {
          "primary": ["nutritional_yeast", "miso"],
          "ratio": "0.5_parts"
        },
        "water": "variable_for_consistency"
      },
      "technique": "temper_into_hot_pasta",
      "critical_points": {
        "temperature": "65-75C",
        "moisture": "pasta_water_addition",
        "timing": "immediate_serve"
      }
    },
    "bechamel": {
      "components": {
        "starch": {
          "primary": "wheat_flour",
          "ratio": "1_part"
        },
        "fat": {
          "primary": "vegan_butter",
          "ratio": "1_part"
        },
        "liquid": {
          "primary": "soy_milk",
          "ratio": "8_parts"
        },
        "flavor_builders": {
          "nutmeg": "trace",
          "white_pepper": "to_taste",
          "nutritional_yeast": "optional"
        }
      },
      "technique": "roux_based_gradual_build"
    }
  },
  "aged_cheese_profiles": {
    "hard_grating": {
      "base_mix": {
        "protein": {
          "primary": "cashews",
          "ratio": "3_parts"
        },
        "fat": {
          "primary": "refined_coconut_oil",
          "ratio": "1_part"
        },
        "culture": {
          "primary": "rejuvelac",
          "alternatives": ["probiotic_powder"],
          "ratio": "as_needed"
        },
        "aging_aids": {
          "primary": "agar",
          "ratio": "0.5%_total_weight"
        }
      },
      "aging_process": {
        "initial_culture": "24-48hrs",
        "drying": "2-3_weeks",
        "temperature": "13-15C",
        "humidity": "65-75%"
      }
    },
    "blue_style": {
      "base_mix": {
        "protein": {
          "primary": "cashews",
          "secondary": "macadamia",
          "ratio": "2:1"
        },
        "culture": {
          "primary": "penicillium_roqueforti",
          "ratio": "trace"
        },
        "structure": {
          "primary": "agar",
          "secondary": "kappa_carrageenan",
          "ratio": "1:1_0.5%_total"
        }
      },
      "aging_process": {
        "initial_set": "24hrs",
        "piercing": "day_7",
        "total_time": "3-4_weeks",
        "temperature": "10-12C",
        "humidity": "85-95%"
      }
    }
  }
}

## Texture-Function Relationships
{
  "protein_starch_ratios": {
    "high_protein_low_starch": {
      "effects": ["browning", "structure", "aging_potential"],
      "applications": ["hard_cheese", "gratable_cheese"]
    },
    "high_starch_low_protein": {
      "effects": ["sauce_stability", "cling", "melt"],
      "applications": ["sauce_bases", "cream_cheese"]
    },
    "balanced_ratios": {
      "effects": ["stretch", "melt", "set"],
      "applications": ["pizza_cheese", "slicing_cheese"]
    }
  },
  "moisture_control": {
    "low_moisture": {
      "benefits": ["better_browning", "longer_shelf_life"],
      "challenges": ["harder_to_melt", "more_energy_dense"]
    },
    "high_moisture": {
      "benefits": ["better_melt", "smoother_texture"],
      "challenges": ["shorter_shelf_life", "less_browning"]
    }
  }
} 