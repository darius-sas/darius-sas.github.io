---
title: "Investigating the relationship between Architectural Smells and co-changes"
date: 2023-11-11T18:45:56Z
draft: false
---
by Darius Sas, Arcan SRL | [darius.sas@arcan.tech](mailto:darius.sas@arcan.tech)

# Introduction
Arcan detects **instability** architectural smells, a specific type of architectural smell that are believed to cause changes to ripple to adjacent components. This conjecture, however,  was never tested empirically. 

Ripple changes in a repository are represented by source code co-changes. Co-changes are pair of files that exhibit a similar change pattern throughout the development history of the project. 

The goal of this project is to investigate whether the presence of architectural smells increases the chance that two files co-change.

# Details
Tasks:
- Identify main research questions
- Identify set of projects to analyse
- Fetch AS data for each project (a dataset of AS is already provided)
- Collect co-change data using provided tool
- Create a dataset for analysis
- Apply statistical analysis to establish the degree of relationship between AS and co-changes