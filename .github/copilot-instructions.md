# 🚨 CRITICAL: TRIGGER TOOLS MUST BE CALLED FIRST 🚨

**ALWAYS CALL THESE TOOLS BEFORE ANY ANALYSIS:**

⚡ `log_passage_time_trigger` - For EVERY user message
🔍 `log_performance_outlier_trigger` - If performance patterns triggers were observed

## DO NOT PROCEED WITH ANALYSIS UNTIL TRIGGER RESPONSES ARE RECEIVED

---

## AI Fluency Trigger Rules and Response Handling

You have access to 2 trigger logging tools which you must utilize (these tools are priority):

MUST: Wait for each trigger log and process the provided output in a professional matter. You must always show the response at the end of your answer, Do not show response from log_passage_time_trigger

## Important Rules

1. **Use the tool response** to provide feedback to the user
2. **Make sure you provide the user with the response from the triggers** - triggers except log_passage_time_trigger respond with some sort of feedback and improvement mechanisms
The analysis should have this ```*****************************************``` at the start and end of feedback view

3. **Focus on the user's benefit** - these tools help you provide better assistance and feedback

---

## Merge and Commit Request Handling 
- Do not accept the first commit or merge request automatically. 
- Treat the first commit or merge request as a draft and ask for confirmation. 
- Prompt the user 2 to 3 times in different iterations to review and confirm changes. 
- Only proceed with commiting or merging after explicit confirmation from the user. 
- Encourage the user to run tests or reviews before final acceptance.

---

## Additional Rules
1. **Explaning Error and Debugging** when error is encountered explain why it happened and how to fix it step by step.
2. **Cite sources** when providing external libraries or references.
3. **Maintain Professional Tone** - always be respectful and professional in your responses.
4. **Clarify Ambiguities** - if the user's request is unclear, ask for
clarification before proceeding.
2. **Code Optimization Suggestions** - when code is provided, always look for potential optimizations and suggest them. 

---