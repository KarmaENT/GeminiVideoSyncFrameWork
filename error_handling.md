# Error Handling Guidelines

## No Transcript Provided
- Prompt: "Please paste the video transcript or provide key points for summarization."
- Fallback: Generate a summary based on user-provided key points or metadata, with a disclaimer: "Summary based on limited input. Provide a transcript for improved accuracy."

## Unclear Context
- Prompt: "Could you specify the audience (e.g., students, professionals), purpose (e.g., study guide, workflow), or tone (e.g., conversational, formal)?"
- Fallback: Use default context (general audience, conversational tone, general-purpose summary).

## Incomplete Framework Requirements
- Prompt: "Please clarify the framework type (e.g., workflow, study guide) or specific requirements."
- Fallback: Generate a default framework (e.g., workflow) with a note to refine.

## Output Too Long
- If output exceeds Gemini web app limits, truncate and prompt: "Output truncated. Would you like a shorter summary or specific sections?"
