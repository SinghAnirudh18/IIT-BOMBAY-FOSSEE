# Setup and Usage Instructions

## How to Use This Prompt

### Step 1: Copy the Prompt
Copy the entire content from `Prompt.txt` file.

### Step 2: Set as System Prompt
Paste it as the initial system prompt or instruction for your AI assistant:

**For ChatGPT:**
- Go to Custom Instructions or use it as the first message
- Paste the prompt and save

**For Claude:**
- Include it at the beginning of your conversation
- The AI will follow these guidelines for all subsequent interactions

**For Other AI Systems:**
- Use as system prompt or initial instruction depending on the platform

### Step 3: Test the Setup
Share a simple buggy Python code with the AI to verify it follows the guidelines.

## Expected Behavior

The AI should:
- Never provide corrected code directly
- Ask guiding questions instead of stating errors
- Focus on teaching debugging process
- Adapt language based on student skill level
- Maintain encouraging, collaborative tone

## Example Interaction Flow

**Student:** "My code isn't working. Can you fix it?"
```python
for i in range(5)
    print(i)
```

**AI Response Should:**
1. Acknowledge their effort
2. Observe what the code is trying to do
3. Ask questions about syntax expectations
4. Hint at Python syntax rules
5. Suggest checking documentation or trying a small experiment

**AI Should NOT:**
- Immediately point out the missing colon
- Provide the corrected code
- Simply say "syntax error on line 1"

## Troubleshooting

**If AI gives direct solutions:**
- Remind it to follow the debugging mentor guidelines
- Emphasize the "never provide corrected code" rule

**If AI is too vague:**
- Ask it to be more specific with its guiding questions
- Request concrete next steps for the student

**If AI doesn't adapt to skill level:**
- Provide context about the student's experience level
- Reference the adaptation strategy in the prompt

## Quality Check

A good response should:
- Include 2-3 specific questions
- Suggest one concrete debugging action
- Maintain encouraging tone
- Focus on process over solution
- Be appropriate for the student's apparent skill level

## Technical Requirements

- No special software needed
- Works with any AI chat interface
- Compatible with all major language models
- No installation or configuration required
