## Sleep Health and Lifestyle ANOVA Analysis

## Overview
This repository contains statistical analysis of the Sleep Health and Lifestyle dataset using Analysis of Variance (ANOVA) methods. The analysis explores relationships between sleep duration and various factors including occupation, gender, and physical activity levels.

## Dataset
The analysis uses a synthetic dataset created for illustrative purposes, containing information on 374 individuals' sleep patterns and lifestyle factors. Key variables analyzed include:

- **Gender**: Categorical variable (Male/Female)
- **Physical Activity Level**: Categorized into Low and High groups
- **Occupation**: Categorized into four groups (Business/Finance, Education/Social Science, STEM, Healthcare)
- **Sleep Duration**: Continuous variable measured in hours

## Research Questions
1. Is there a significant difference in mean sleep duration among the four occupation categories?
2. Is there a significant difference in mean sleep duration between genders and physical activity groups, and is there a significant interaction between gender and physical activity?

## Methodology
The analysis employs:
- **One-way ANOVA**: To assess the effect of occupation on sleep duration
- **Two-way ANOVA**: To examine the effects of gender and physical activity level on sleep duration, as well as their interaction

## Key Findings

### One-way ANOVA Results
- Significant differences in sleep duration exist among occupation categories (F = 28.45, p < 0.001)
- Post-hoc Tukey test revealed significant differences between:
  - STEM and Business/Finance
  - STEM and Education/Social Science
  - STEM and Healthcare
- Surprisingly, STEM workers reported more sleep than other occupational groups

### Two-way ANOVA Results
- Gender has a significant effect on sleep duration (F = 8.055, p = 0.00479)
- Physical activity level has a significant effect on sleep duration (F = 64.430, p < 0.001)
- There is a significant interaction between gender and physical activity (F = 102.485, p < 0.001)
- For males, there is a significant difference in sleep duration between physical activity groups
- For females, there is no significant difference in sleep duration between physical activity groups

## Visualization
The repository includes visualizations of:
- Mean sleep duration across occupation categories
- Interaction effects between gender and physical activity level on sleep duration

## Contributors
- Wendy Mendoza Gutierrez, Metropolitan State University
- Amina Hakim Mohamud, Metropolitan State University

