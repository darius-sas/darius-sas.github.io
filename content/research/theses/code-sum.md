---
title: "Inferring features using code summarisation"
date: 2023-11-11T18:45:56Z
draft: false
---
by Darius Sas, Arcan SRL | [darius.sas@arcan.tech](mailto:darius.sas@arcan.tech)

# Introduction
In the context of change impact analysis is of paramount importance for our customers to understand the impact of changes at the feature level of the application. Namely, if I update the cart functionality of my ecommerce application it is also likely that I need to update the payment functionality. 
However, we still do not have a way of identifying how certain files constitute a feature of a system.

The goal of this project is to create a machine learning model that classifies source code files based on the functionality they contribute to.
To do so, we will use multiple sources of data, including git, issues, and file contents.

## Details
Tasks:
- Compile a dataset
	- Create issue tracker data collector (via API)
	- Use git history to associate files with issue id (tools that mine this information will be provided by us)
	- Extrapolate keywords and token from the source code files
	- Compile the data into a single dataset
- Access a LLM (or use a local one) that given the metadata associated to a file, assigns a feature label.
## Technology stack 
- Python and Bash for compiling the dataset
- R for building the model