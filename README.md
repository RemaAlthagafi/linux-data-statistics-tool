# Linux Data Statistics Tool

## Project Overview

This project is a Bash-based tool developed in a Linux environment to compute basic statistical measures from a dataset stored in a text file. The script processes numeric data and allows the user to calculate different statistics for selected columns.

The goal of the project was to practice shell scripting and the use of common Linux command-line utilities for data processing.

---

## Features

The script can calculate the following statistics:

- Mean
- Mode
- Minimum and Maximum
- Standard Deviation
- Sum

The user can select one or multiple columns from the dataset for analysis.

---

## Technologies Used

- Bash scripting
- Linux command-line tools
  - `awk`
  - `grep`
  - `sed`

---

## How the Program Works

1. The user enters the name of a file containing numeric data.
2. The script filters lines that contain only valid integers.
3. The data is cleaned and stored in a temporary file.
4. The user chooses the statistical operation from a menu.
5. The user selects the column numbers to analyze.
6. The script calculates and prints the requested results.

---

## My Contribution

This project was developed as part of a team assignment. My contribution included designing the project flowchart, preparing the report documentation, and implementing parts of the Bash script responsible for calculating the **mean** and **sum** statistical functions.

---

## Learning Outcomes

Through this project, we practiced:

- Bash scripting in Linux
- Data filtering and preprocessing
- Using command-line utilities for data analysis
- Implementing statistical calculations using shell scripts