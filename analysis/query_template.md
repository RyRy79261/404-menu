

# Query Template

## Context Reference
{
  "codebase_files": {
    "required": ["List required files"],
    "optional": ["List supporting files"]
  },
  "operational_constraints": {
    "equipment": ["Reference to equipment list"],
    "time": ["Reference to time constraints"],
    "prep_limitations": ["Reference to prep constraints"]
  }
}

## Query Structure
{
  "primary_request": {
    "type": "specific_request_type",
    "scope": "clear_boundaries",
    "expected_output": "format_specification"
  },
  "context_markers": {
    "previous_decisions": ["Reference relevant decisions"],
    "dependencies": ["List dependencies"],
    "constraints": ["List constraints"]
  }
}

## Response Format
{
  "structure": {
    "format": "markdown",
    "sections": [
      "context_summary",
      "analysis",
      "recommendations",
      "next_steps"
    ]
  },
  "code_references": {
    "style": "startLine/endLine",
    "format": "language:filepath"
  }
}