# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
1. Initialize Experiment
   1.1 Select LLM model(s) and fix hyperparameters (temperature, max tokens, top\_p).
   1.2 Define evaluation metrics (0–5 scale for accuracy, clarity, depth, etc.).
   1.3 Prepare a storage structure (table/CSV) to log results.

2. Prepare Test Scenarios
   2.1 Choose at least 5–6 scenarios covering factual recall, math, summarization, creativity, reasoning.
   2.2 For each scenario, create both:

   * Broad prompt (unstructured).
   * Refined prompt (clear instructions, constraints).

3. Generate Prompt Variants
   3.1 For each scenario, design prompt versions for:

   * Zero-shot
   * Few-shot (with examples)
   * Chain-of-thought
   * Role-based
   * Instruction-based
     3.2 Store all prompt texts systematically.

4. Run Experiment
   For each **(scenario × prompting pattern × prompt type)**:
   4.1 Input prompt into model.
   4.2 Collect generated response.
   4.3 Record response along with prompt, pattern type, and model settings.
   4.4 Repeat multiple times (N = 10–20) for reliability.

5. Evaluate Responses
   5.1 Assign each response to evaluators (blind to prompt type).
   5.2 Score responses using rubric (accuracy, clarity, depth, relevance, adherence).
   5.3 Store numerical scores and qualitative feedback.

6. Analyze Data
   6.1 Compute average scores for each prompting pattern per scenario.
   6.2 Perform statistical comparison (e.g., paired t-test or ANOVA) between broad vs. refined prompts.
   6.3 Identify best-performing prompting pattern for each task type.
   6.4 Categorize common errors (hallucination, wrong format, shallow answer).

7. Report Findings
   7.1 Summarize results in tables and graphs (bar charts of mean scores).
   7.2 Include representative examples (good vs. bad outputs).
   7.3 Write conclusions:

   * Which prompting pattern works best in which scenario.
   * Overall impact of refined prompts vs. broad prompts.
   * Observed limitations.


## Output
[Comparative_Analysis_of_Prompting_Patterns.pdf](https://github.com/user-attachments/files/22019304/Comparative_Analysis_of_Prompting_Patterns.pdf)


## Result
The result will be a comparative report with examples, response analyses, and clear insights on how prompting patterns affect quality, accuracy, and usefulness of AI responses.
