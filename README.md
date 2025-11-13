# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
Algorithm for Choosing Prompting Patterns

step 1: Identify Task Type

• If task is simple, fact-based, or well-known → go to Step 2.

• If task is complex reasoning, multi-step, or logical → go to Step 3.

• If task requires specific tone, role, or style → go to Step 4.

Step 2: Simple/Direct Tasks

• If clear instruction can solve → Instructional Prompting.

• If no instruction but model should infer → Zero-Shot Prompting.

• If examples are needed for better accuracy → Few-Shot Prompting.

Step 3: Reasoning Tasks

• If single reasoning chain is sufficient → Chain-of-Thought Prompting.

• If high accuracy is required and resources allow → Self-Consistency Prompting.

Step 4: Contextual/Role-Specific Tasks

• If response must reflect expertise, persona, or simulation → Role-Based
Prompting.

Step 5: Refine

• Evaluate outputs; combine methods if needed (e.g., Role-Based + CoT for an
expert reasoning persona).
## Prompt:

Conduct a detailed comparative analysis of different prompting patterns used in Large
Language Models (LLMs). Cover at least the following types: Zero-Shot Prompting,
Few-Shot Prompting, Chain-of-Thought Prompting, Role-Based Prompting, Instructional
Prompting, and Self-Consistency Prompting. For each prompting pattern: explain the
concept, provide an example test scenario, and analyze the strengths, weaknesses, and
best use cases. Ensure the response is structured, uses clear headings, and highlights
differences across the patterns.

## Output


[Comparative_Analysis_of_Prompting_Patterns.pdf](https://github.com/user-attachments/files/23528290/Comparative_Analysis_of_Prompting_Patterns.pdf)

## Result
Each prompting pattern has unique advantages. Zero-shot and instructional are efficient
for direct tasks, few-shot excels with examples, chain-of-thought and self-consistency
shine in reasoning, while role-based adapts to audience needs. The choice depends on the
task domain.

