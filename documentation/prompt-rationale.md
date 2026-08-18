# Prompt Design Rationale

## Why these prompts were selected

I selected five common personal finance tasks that can be useful in a finance management platform: budgeting, spending analysis, saving, financial goal planning, and monthly financial insights.

I designed each prompt with a similar structure so that the AI receives the required context before performing the task.

## 1. Budget Analysis

The budget prompt uses income, fixed expenses, variable expenses and savings goals because these details are needed to understand whether a user's budget is balanced.

I also added a clear output format so the result is easier for a user to understand.

## 2. Spending Analysis

The spending prompt focuses on categories and comparison with the previous month. This helps the AI identify changes in spending rather than only listing transactions.

I included a limitation against assuming that a purchase is unnecessary because spending decisions depend on the user's situation.

## 3. Saving Recommendation

The saving prompt considers income, essential expenses, non-essential expenses and the user's target.

I included a target assessment so the AI does not simply give a generic saving suggestion. If the target is unrealistic based on the available information, the prompt asks the AI to explain this and suggest an alternative.

## 4. Financial Goal Planning

This prompt breaks a larger financial goal into a monthly requirement.

The goal amount, current savings and target date are included so the AI can calculate the remaining amount and estimate the monthly requirement.

## 5. Monthly Financial Insights

The final prompt provides an overall monthly view. It compares current and previous data and connects the results to the user's financial goals.

The output is intentionally divided into positive changes, areas to watch and next actions so that the result is practical rather than just descriptive.

## Common Design Choices

Across the five prompts, I used:

- Clear role definition
- Relevant user context
- Specific tasks
- Explicit constraints
- Structured output formats
- Missing-data handling
- Practical recommendations

These choices help reduce ambiguity and make the AI responses more consistent.
