# A/B Testing Analysis

## Author
Tejananda

## Objective
Perform A/B testing to evaluate the impact of a new feature (or change) on user conversion rates.

## Dataset
- Dataset file: `ab data_testing.csv`
- Columns:
  - `user_id` : Unique identifier for users
  - `group` : Group assigned (`control` or `variant`)
  - `converted` : Conversion status (0 = no, 1 = yes)

## Methodology
1. Load and inspect dataset
2. Calculate conversion rates for each group
3. Visualize data with charts
4. Perform statistical tests (Chi-square)
5. Compute confidence intervals for difference in conversion rates
6. Make data-driven decision

## Analysis Steps
- Step 1: Load dataset
- Step 2: Explore dataset
- Step 3: Calculate conversion rates
- Step 4: Visualize conversion rates
- Step 5: Perform Chi-square test
- Step 6: Confidence interval for difference
- Step 7: Decision-making
- Step 8: Additional charts (pie chart, stacked bar chart, etc.)

## Results
- Conversion rates by group: `conversion_rates`
- Chi-square p-value: `p`
- 95% confidence interval for difference: `[ci_lower, ci_upper]`
- Visualizations included:
  - Conversion rate bar chart
  - Users per group
  - Pie chart for overall conversion
  - Stacked bar chart by group

## Conclusion
Based on statistical analysis:
- If variant conversion is significantly higher → implement the new feature
- Otherwise → keep control group
