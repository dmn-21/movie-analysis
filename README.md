# Movie Recommendation Analysis using Apriori and ECLAT

## Live Project

[View the MBA Movie Analysis Report](https://dmn-21.github.io/movie-analysis/)

## Overview

This project presents an association rule mining analysis of movie recommendation patterns using the Apriori and ECLAT algorithms in R. The analysis explores viewer behavior and discovers relationships between movies frequently watched together.

The project was developed in RStudio and Quarto and includes interactive visualizations, association rule analysis, and business-oriented insights related to movie selection patterns.

---

# Objectives

* Perform exploratory data analysis on the movie dataset
* Transform movie ratings into transaction format
* Apply the Apriori algorithm using the `arules` package
* Apply the ECLAT algorithm for frequent itemset mining
* Analyze support, confidence, and lift metrics
* Visualize association rules using `arulesViz`
* Build interactive tables and graphs
* Analyze factors influencing the popularity of *Pulp Fiction*
* Identify which movies are influenced by viewers watching *Pulp Fiction*

---

# Technologies Used

* R
* RStudio
* Quarto
* arules
* arulesViz
* DT
* plotly

---

# Key Analysis

The analysis identified strong associations between several popular movies.
For example:

* Viewers of *Trainspotting* were highly likely to watch *Pulp Fiction*
* Strong relationships were identified between *The Lord of the Rings* trilogy movies
* Movies such as *Goodfellas*, *Reservoir Dogs*, and *The Big Lebowski* showed high association with *Pulp Fiction*

---

# Metrics Used

* **Support** – frequency of a rule in the dataset
* **Confidence** – probability of selecting a movie based on another movie
* **Lift** – strength of the relationship between movies

---

# Output

The project includes:

* Interactive tables
* Network graphs
* Scatter plots
* Matrix visualizations
* Frequent itemset analysis
* Association rule mining results

---

# Repository Structure

```text
index.html
index_files/
project.qmd
README.md
```

---

# Author

Daniel Nikolov
