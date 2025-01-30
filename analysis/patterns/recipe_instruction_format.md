# Recipe Instruction Format

## Component Structure
{
  "header": {
    "recipe_name": "string",
    "cultural_origin": "string",
    "service_style": "string",
    "yield": "number",
    "prep_time": "duration",
    "cook_time": "duration"
  },
  "components": [
    {
      "id": "color_code",
      "name": "string",
      "quantity": "measure",
      "prep_state": "string",
      "storage_method": "string"
    }
  ],
  "assembly_steps": [
    {
      "step_number": "integer",
      "components_needed": ["color_codes"],
      "action": "string",
      "quality_checks": ["criteria"],
      "time_required": "duration",
      "critical_points": ["temperature", "texture", "visual"]
    }
  ]
}

## Visual Guide Requirements
{
  "step_photos": {
    "angle": "overhead",
    "lighting": "natural",
    "focus_points": ["technique", "doneness", "assembly"]
  },
  "color_coding": {
    "component_markers": "colored_dots",
    "quantity_indicators": "numbered_dots",
    "temperature_states": "colored_borders"
  }
} 