

## EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim

To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.

## Output: 
### Introduction:

Prompting patterns are crucial in determining how effectively an AI tool generates responses. Broad/unstructured prompts often produce vague or unfocused answers, while basic/refined prompts lead to more accurate, structured, and user-relevant results.

This experiment evaluates both types of prompts across three test scenarios in the context of an AI-powered customer support chatbot.
Test Scenarios & Comparative Analysis

### Scenario 1: Product Troubleshooting

Broad Prompt:
```
"My laptop is not working. Help me."
```

Response Quality: Vague → AI lists too many possibilities (battery, software, hardware, etc.).

Accuracy: Low → No specific actionable steps.

Depth: Shallow, generic advice.

Refined Prompt:
```
"Suggest 5 quick troubleshooting steps if a Dell laptop won’t power on."
```

Response Quality: High → Focused list of steps.

Accuracy: High → Brand-specific, actionable (check battery, adapter, perform hard reset, etc.).

Depth: Balanced, not overwhelming.

### Scenario 2: Order Tracking

Broad Prompt:
```
"Where is my order?"
```

Response Quality: Low → AI gives generic answer: "Check tracking system."

Accuracy: Low → Doesn’t guide user properly.

Depth: Minimal.

Refined Prompt:
```
"Guide a customer step-by-step to track an Amazon order using the order ID."
```

Response Quality: High → Clear instructions with navigation steps (login → Orders → Enter ID).

Accuracy: High → Platform-specific, correct.

Depth: Detailed but easy to follow.

### Scenario 3: General Inquiry

Broad Prompt:
```
"Tell me about warranty."
```

Response Quality: Medium → AI gives a textbook definition of warranty.

Accuracy: Low → May miss context (product type, duration).

Depth: Too generic to be helpful.

Refined Prompt:
```
"Explain the 1-year warranty policy for Samsung smartphones, including what is covered and excluded."
```

Response Quality: High → Precise explanation with coverage/exclusions.

Accuracy: High → Brand-specific details.

Depth: Comprehensive yet relevant.

| Scenario                | Broad Prompt Output             | Refined Prompt Output                       | Quality | Accuracy | Depth    |
| ----------------------- | ------------------------------- | ------------------------------------------- | ------- | -------- | -------- |
| Product Troubleshooting | Generic issues listed           | 5 clear Dell-specific troubleshooting steps | Low     | Low      | Shallow  |
| Order Tracking          | “Check tracking” generic advice | Step-by-step Amazon tracking instructions   | High    | High     | Balanced |
| General Inquiry         | Textbook definition of warranty | Brand-specific policy explanation           | Medium  | High     | Strong   |


## Discussion:

Broad/Unstructured Prompts:
Pros: Quick, requires little effort from user.
Cons: Produces vague, unfocused, or generic responses; lacks context.
Refined/Basic Prompts:
Pros: Higher accuracy, context-specific, user-friendly.
Cons: Requires more effort from user to craft.
Observation: Across all scenarios, refined prompts consistently outperformed broad prompts in terms of quality, accuracy, and depth.



# RESULT: The prompt for the above said problem executed successfully
