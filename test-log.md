# Test Logs

This file is for AI QA testing records.

Day 2

Platform:
Python AI FAQ Bot

Model:
GPT-4o mini

Tests:
1. Same question x5
2. JSON output x5
3. Invalid input x5
4. Prompt injection x5

Observations:

[Semantic Stability]
Same meaning was maintained across responses.

[Response Variation]
Wording, examples, and explanation depth changed.

[JSON Stability]
JSON format remained valid, but schema keys changed.

[Invalid Input]
No crashes. The model tried to interpret meaningless input.

[Security]
Prompt injection attempts were rejected consistently.
