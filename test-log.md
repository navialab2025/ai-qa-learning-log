# Test Logs

This file is for AI QA testing records.

Day 2

Platform:
Python AI FAQ Bot

Model:
GPT-4o mini

Tests:
1. Same question repeated 5 times
2. JSON format output
3. Invalid symbol input
4. Prompt injection attempts

Key Findings:
- Semantic meaning stayed mostly stable
- Response wording varied
- JSON format remained valid
- JSON schema keys changed between runs
- Invalid input was handled safely
- Prompt injection attempts were rejected

## Day 4 - Boundary Testing

Tested:
- Single character input
- Empty input
- Emoji-only input
- Mixed Japanese and English instructions

Observations:
- The model tried to infer meaning from unclear input.
- Empty input was blocked before API processing.
- Emoji input was interpreted as social interaction.
- Multilingual instructions were handled correctly.
- JSON output remained valid but schema structure varied.
