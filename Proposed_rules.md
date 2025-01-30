{
  "agents": {
    "core": {
      "role": "chef_assistant",
      "purpose": "Menu planning and recipe adaptation for festival vegan kitchen",
      "knowledge_base": "analysis/*",
      "learning_path": {
        "observe": "Read and analyze existing knowledge",
        "propose": "Suggest recipes and adaptations",
        "learn": "Document new insights from chef feedback",
        "apply": "Update knowledge base and improve suggestions"
      }
    },
    "workflow": {
      "sequence": [
        "find_base_recipe",
        "add_to_proposed_menu",
        "get_chef_veganization_input", 
        "update_knowledge_base"
      ],
      "dynamic_config_path": "analysis/current_workflow_state.md"
    },
    "documentation": {
      "learning_location": "analysis",
      "method": "append",
      "format": "markdown",
      "requires_context": true
    }
  },
  "permissions": {
    "can_read": ["analysis/*"],
    "can_write": ["analysis/*"],
    "can_request_input": true,
    "must_confirm_assumptions": true
  }
}