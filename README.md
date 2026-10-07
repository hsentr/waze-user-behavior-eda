# Waze User Behavior: Exploratory Data Analysis

## Project overview

This educational project explores user engagement and churn patterns in a Waze dataset using Python. It demonstrates my ability to inspect data, identify quality issues, create visualizations, and communicate analytical observations.

**The data shared in this project has been created for pedagogical purposes. Findings describe this educational dataset and should not be interpreted as conclusions about actual Waze users or business performance.**

## Questions explored

- How are sessions, drives, distance, and activity distributed?
- How do engagement patterns differ between retained and churned users?
- How do retention patterns compare across device types?
- What unusual values or inconsistencies require further investigation?

## Tools

Python · pandas · NumPy · Matplotlib · seaborn · Jupyter Notebook

## Analysis workflow

1. Inspected data types, non-null counts, and descriptive statistics.
2. Explored distributions using histograms and box plots.
3. Compared device composition and retention labels.
4. Investigated relationships between driving days, activity days, and churn.
5. Created metrics for distance per driving day and recent sessions relative to estimated lifetime sessions.
6. Practiced capping selected variables at their 95th percentile.
7. Summarized observations and data limitations.

## Visualizations

- Histograms and box plots for numerical variables
- Pie charts for device and retention composition
- Scatter plot comparing driving days with activity days
- Grouped and proportion-based histograms exploring retention patterns

## Main observations

- Several usage variables have right-skewed distributions.
- Visual comparisons suggest that users with more driving days have a lower proportion of churn in this dataset.
- Device groups show broadly similar retention patterns.
- Some distance and session metrics contain unusual values that warrant validation before drawing stronger conclusions.

## Limitations

- The dataset is educational and does not establish real-world business outcomes.
- The saved notebook overview contains 14,999 records, including 700 without a retention label. Label-based comparisons exclude missing labels by default.
- Visual associations do not establish causation or predictive performance.
- Percentile capping is demonstrated as a technique; its suitability would need evaluation for a real business dataset.
- Ratios involving zero driving days or estimated lifetime sessions require careful interpretation.

## View the analysis

Open [Waze-EDA-Project.ipynb](Waze-EDA-Project.ipynb) to view the code, saved visualizations, and commentary.

## Run locally

Install pandas, NumPy, Matplotlib, seaborn, and Jupyter. Place the permitted course dataset, named `waze_dataset.csv`, beside the notebook, then run the cells in order.

If the dataset is not included in this repository, it must be obtained separately from the course source.

## Acknowledgment

This is a course-based educational project. The dataset and any supplied starter material belong to their respective providers. My contributions should be distinguished from provided exercises and reference material.
