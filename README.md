# greenfuture-data
Green Future Data 

This repository contains the dataset used for Section 1 of my Data Analytics coursework (CP60056E/CP6CS56E/CP6HA50E/CP6SA56E).

## Dataset

- **File:** `greenfuture_ideas_dataset.csv`
- **Description:** Contains 3,000 idea submissions collected via IMS-Connect at GreenFuture, an environmental consulting firm.
- **Features include:** Employee ID, office location, department, votes, collaboration status, and more.

## Purpose

The dataset is used to perform:
- SQL queries in R
- Data manipulation and transformation using R packages
- Data visualization and insight generation

## Access in R (Google Colab)

To read the file directly into R:

```r
data <- readr::read_csv("https://raw.githubusercontent.com/yourusername/greenfuture-data/main/greenfuture_ideas_dataset.csv")
