# Aprendizagem Automática 2023/2024 - Second Home Assignment

## Task Details

**Task:** Motion Capture Hand Postures - Classification Models  
**Allowed Models for Testing:**
- Linear Models
- Tree-Based Models
- Naive Bayes
- K-Nearest Neighbours

## Data Processing Notes

- **Target Variable:** Class
- **Attention:** Consider the User variable as categorical (even though it is numeric).
- **Data Cleaning:**
  - Eliminate the first row of the dataset as it contains only zeros.
  - Handle missing values represented by '?' appropriately.

## Model Evaluation

- Use Simple Cross-Validation (testing=25% of all data) for model evaluation.
- Ensure the same data partition is used for all models; do not use KFOLD CV.
- Examine different hyperparameters and select the best ones.
- Prefer simpler models when hyperparameters and performance are similar.

## Submission Details

### Documents

Submit a ZIP file containing:

1. **PDF Report (Max 5 Pages):**
   - Header with group number, student names, IDs, and hours contributed.
   - Report text covering:
     - Data processing steps.
     - Model results, including a table with statistics for the best models tested.
     - Discussion and Conclusions.
   - Support all sections with graphics.

2. **Notebook (or Similar):**
   - Source code with attached results that led to the report.
   - The Notebook should not exceed 12 pages (penalties will be applied).

### Submission Deadline

- Submit on the Course Moodle with one submission per group.
- **Deadline:** Sunday, November 19 at 23:59.

## Group Information

- **Group Number:**
- **Students:**
  - João Vieira nº 45677
  - Bruno Lima nº 54466
  - Ricardo Ramos nº 56656
  - António Casimiro nº 56685
  

## Contribution

- Briefly outline how many hours each student contributed to the project.

