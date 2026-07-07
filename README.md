# Task 5: Auto Tagging with LLM

## 1. Objective of the Task
The objective of this task is to automatically categorize customer support tickets using a Large Language Model (LLM). This helps in routing tickets to the correct department and reduces manual effort.

## 2. Methodology / Approach
1. **Data Loading**: Loaded customer ticket dataset in CSV format.
2. **Prompt Engineering**: Designed prompts to instruct the LLM to classify tickets into predefined categories like Billing, Technical, Account, etc.
3. **LLM Inference**: Used LLM API to process each ticket and generate tags.
4. **Result Saving**: Saved the tagged output to `llm_tagging_results.csv` for analysis.

## 3. Key Results / Observations
- The LLM was able to accurately tag majority of the tickets based on the prompt.
- Most common categories found were: Technical and Billing.
- Using LLM reduced manual tagging time significantly.
- Some ambiguous tickets needed better prompt refinement for 100% accuracy.

