# Task Optimizer

This repository contains a collection of small Python scripts designed to enhance productivity and optimize workflow efficiency. Each script automates repetitive tasks, reduces manual effort, and speeds up various work processes.

## Excel Files Merger

### Overview
This script processes multiple Excel files from a specified folder, extracts specific columns, and merges them into a single output file. It is designed to handle `.xlsx` and `.xls` files using `pandas` and `openpyxl`.

### Features
- Reads all Excel files from a given folder.
- Filters and retains only relevant columns.
- Combines data into a single `DataFrame`.
- Saves the merged data to a new Excel file.
- Handles errors gracefully while processing files.

## Excel Sheet Copier

### Overview
This script copies all sheets from multiple Excel files within a specified folder and consolidates them into a single destination Excel file. It also provides a function to count the number of sheets in the final file.

### Features
- Reads all Excel files from a specified folder.
- Copies all sheets from each source file into a destination Excel file.
- Appends sheets without overwriting existing data.
- Counts the total number of sheets in the destination file.
