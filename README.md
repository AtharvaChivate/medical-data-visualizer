
# Medical Data Visualizer

In this project, we will use matplotlib, seaborn, and pandas to visualize and calculate data from medical examinations. Values from the dataset were gathered while performing medical exams.

## Dataset Description
The rows in the dataset represent patients and the columns represent information like body measurements, results from various blood tests, and lifestyle choices. We will use the dataset to explore the relationship between cardiac disease, body measurements, blood markers, and lifestyle choices.

# Project Summary

### Data Loading and Preparation

- Loaded medical examination data from `medical_examination.csv`.
- Added `BMI` and `Overweight` columns based on height and weight calculations.
- Normalized cholesterol and glucose data to binary values.

### Data Cleaning

 Filtered out incorrect data segments:
  - Diastolic pressure higher than systolic pressure.
  - Extreme values for height and weight.

### Data Visualization

- **Categorical Plot:**
    Created a categorical plot using Seaborn's `catplot()` to visualize counts of categorical features (`cholesterol`, `gluc`, `smoke`, `alco`, `active`, `Overweight`) by `cardio` status.
  
- **Heatmap:**
   Generated a correlation matrix heatmap using Seaborn's `heatmap()` to visualize feature correlations, masking the upper triangle.


