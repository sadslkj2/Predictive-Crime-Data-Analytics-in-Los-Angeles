[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/5GqajVEC)
# MSDS-597 Project

Group: 8

## Project summary

Our project summary can be found:

- as a website:

https://moran-teaching.github.io/project-group/

## Accessing data

Our raw data can be downloaded here:  
https://catalog.data.gov/dataset/crime-data-from-2020-to-present

Our processed data can be downloaded here:  
Our processed dataset is available in three formats—CSV, Excel, and Parquet.  
https://drive.google.com/drive/folders/1om-bKXm8b6cKOUIy6SSwtixhuxgh9OIi?usp=sharing

## Python scripts / notebooks

The following scripts/notebooks were used produce the summary: 

All key files are located in the root directory of the repository:
- `data_cleaning.ipynb`: Handles missing values, filters and standardizes raw crime data.
- `data_enrichment.ipynb`: Merges external data sources for richer feature context.
- `data_analysis.ipynb`: Performs exploratory data analysis.
- `data_analysis_modeling.ipynb`: Builds and evaluates classification models to predict crime severity.
- `index.ipynb`: Quarto homepage notebook. Contains the final narrative, conclusions, and embedded visuals for the published website.
- `test_data_cleaning.py`: Unit test script to validate cleaning functions and data consistency.

## Reproducibility

- `environment.yml`: Defines the project’s Python environment and dependencies.

## Guide

### Summary

Your summary should include the following. 

Note: You do not need code in your summary - instead, reference where in your github repo the code is. The priority should be a concise, readable summary. You should include visualizations and conclusions regarding your data analysis.

1. describe where the data cam from, the format of the data, the nature of the data (e.g., what it contains, how often it is updated, etc).

2. explain how you retrieved the data e.g. API, webscraping

3. explain how you transformed raw data into tidy tabular data, including data cleaning

4. explain any tests you did to check data (e.g. using `pytest` to verify that no missing values are present in the tidied dataframes, verify that the resulting number of rows is reasonable)

5. explain any data enrichment steps

6. describe and explain meaningful summary statistics

7. present around 4-6 visualizations related to the data, explain trends and conclusions

You should have at least one interactive data widget.

You can include figures for example from an external notebook:
- https://quarto.org/docs/blog/posts/2023-03-17-jupyter-cell-embedding/ 
- https://quarto.org/docs/authoring/includes.html

8. at the end, display a graph of the git commit history

For team members of 2: 10 commits. Of 3: 15 commits. Of 4: 20 commits.

Your commits history elsewhere may be more dirty, but these 10-20 commits need to be clean and can be drawn as a graph.

Make sure your git graphs include author names, commit messages, date, git tags if any.

You can generate nice graphs of git commits with many tools. Among others, you could generate git-graphs using the following tools:

- in vscode: https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph
- https://stackoverflow.com/questions/1057564/pretty-git-branch-graphs
- https://www.gitkraken.com/solutions/commit-graph

### Data storage options

Some options for data storage:

- Box link (free with Rutgers account)
- Dropbox
- Google Drive

The following companies have free data storage (up to ~5 GB) for 12 months. Be careful to make sure you're within the free limits!!!

- AWS S3 https://aws.amazon.com/s3/
- Google Cloud https://cloud.google.com/free
- Microsoft Azure https://azure.microsoft.com/en-us/free/students

