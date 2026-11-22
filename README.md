# Homework 4.3: Reproducible Data Analysis

This repository contains my STAT 184 Homework 4.3 project. The project uses R and Quarto to combine multiple data analyses into a reproducible PDF document.

## Overview

The report contains five main sections:

1. Descriptive statistics for diamond length, width, and depth, separated by cut quality.
2. A comparison of Penn State’s home and away scoring averages with those of the other Big Ten women’s basketball teams.
3. Monte Carlo numerical integration of the standard normal curve.
4. A comparison of plan-informed and generic GenAI responses for analyzing calcium data.
5. A reflection on the problem-solving skills I have developed in STAT 184.
6. A GenAI Usage Appendix and a Code Appendix.

### Interesting Insight (Optional)

This is optional but highly recommended. You'll include one interesting insight from your project as part of the README. This insight is most effective when you include a visual. Keep in mind that this visual must be included as an image file (e.g., JPG, PNG, etc.). You can export plots created with `{ggplot2}` by using the function `ggsave`.

### Interesting Insight

One interesting result is that Penn State had a much smaller home–away scoring difference than the other Big Ten teams combined. Penn State averaged approximately 73 points per game away and 75 points at home, while the other Big Ten teams averaged approximately 71 points away and 79 points at home. This means Penn State’s home–away difference was about 2 points, compared with about 8 points for the other teams. Although these averages do not explain why the difference exists, they show how a visualization can reveal a pattern that may be worth exploring further.


## Data Sources and Acknowledgements

This project uses the following data:

- `diamonds`, a course-provided dataset containing a set of diamonds with descriptive statistics.
- `games_copy.csv`, a course-provided NCAA women’s basketball dataset.
- `calcium.csv`, a course-provided dataset containing calcium measurements for 31 women.

The analysis was completed using R, Quarto, `ggplot2`, `tidyverse`, and `kableExtra`. All uses of generative AI are documented in the GenAI Usage Appendix of the report.

## Current Plan

1. Organizing the project files in an RStudio project.
2. Cleaning and summarizing the required datasets.
3. Creating three descriptive-statistics tables for the diamond dimensions.
4. Creating the Big Ten home-and-away scoring visualization.
5. Creating a four-panel Monte Carlo integration visualization.
6. Comparing plan-informed and generic GenAI results.
7. Writing narrative text that explains the results and their context.
8. Adding a reflection, GenAI Usage Appendix, and Code Appendix.
9. Rendering the QMD file directly to PDF.
10. Proofreading the final document and checking it against the assignment rubrics.

## Repo Structure

This repository is maintained using GitHub’s version-control features:

- Changes are developed on the `dev-Andrew` branch rather than directly on `main`.
- GitHub issues are used to identify and organize required work.
- Commits use descriptive messages explaining the completed changes.
- Pull requests are used to review and merge work into `main`.
- The QMD, PDF, datasets, and supporting files are kept together so that the analysis can be reproduced.
- The report is rendered again after changes are made to confirm that it still works correctly.
- Large files are managed using Git Large File Storage.

## Authors

Andrew Speer  
STAT 184, Penn State