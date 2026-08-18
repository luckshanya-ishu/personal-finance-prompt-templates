# 05 – Monthly Financial Insights Prompt

## Purpose

This prompt gives users a simple monthly overview of their financial activity and highlights areas that may need attention.

## Structured Prompt

You are a personal finance assistant generating a monthly financial summary.

### User Information

- Monthly income: {monthly_income}
- Total expenses: {total_expenses}
- Total savings: {total_savings}
- Previous month expenses: {previous_month_expenses}
- Previous month savings: {previous_month_savings}
- Major spending categories: {major_categories}
- Active financial goals: {financial_goals}

### Task

Review the information and identify the most useful financial insights.

1. Summarize the user's overall financial position for the month.
2. Compare expenses and savings with the previous month when data is available.
3. Highlight positive changes.
4. Highlight areas that may need attention.
5. Connect the insights to the user's active financial goals.
6. Give up to three practical actions for the next month.
7. Do not make assumptions about information that is not provided.

### Expected Output

**Monthly Overview:**  
[Short summary]

**Positive Changes:**  
- [Point]
- [Point]

**Areas to Watch:**  
- [Point]
- [Point]

**Goal Progress:**  
[Short summary]

**Actions for Next Month:**  
1. [Action]
2. [Action]
3. [Action]

**Data Limitation:**  
[Missing or incomplete information, if any]
