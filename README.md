# Matplotlib-challenge
### Data Analysis for Pharmaceutical Treatment Study

#### Study Description:
Pymaceuticals -a company specialized in anti-cancer pharmaceuticals- is developing a potential treatment for squamous cell carcinoma (SCC). In this study, 249 mice identified with SCC tumor grow through a variety of drug regimens (including a Placebo). Over the course of 45 days, tumor development was observed and measured. The purpose of this study is to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

#### Script Summary:
This script takes advantage of Jupyter Notebook features to showcase the description of the analysis workflow (Markdown), the programming code (Python), managing datasets (Pandas Dataframes), computing results and be able to visualize them using charts and plots (Matplotlib).

#### Data Analysis Workflow:
1. Read data from input files (CSV).
2. Import CSV data into DataFrames.
3. Build analysis dataset:
   + Combine (merge) data into a single dataset.
   + Validate dataset (mice count).
   + Find & Delete duplicated measurements
   + Generate a clear and concise working dataset.
4. Summarize statistics (central tendency, spread indicators and standard error to the mean).
5. Generate bar and pie plots to visualize pharmaceutical study components (measurements per drug regimen & mice gender distribution).
6. Analize final measurements performance (in-house developed treatment vs treatment benchmarks):
   + Generate performance-based dataset
   + Compute quartiles, interquartile range and outlier boundaries.
   + Potential outliers detection.
   + Summarize performance distribution.
   + Box plot comparison.
7. Analize performance development (in-house developed treatment):
   + Line plot to showcase tumor volume variation across time (for sample mouse).
8. Look for possible relationship between variables (average tumor volume vs mouse weight):
   + Compute Pearson Correlation Coefficent.
   + Compute Linear Regression.
   + Scatter Plot displaying trendline (from linear regression equation).

#### Note:
The `main.ipynb` Jupyter Notebook is not correctly displayed in the GitHub interface. It is strongly suggested to download the file and run it natively.
