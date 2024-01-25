# FootballEventData
## Overview
This repository contains a suite of Jupyter Notebooks designed for extracting, transforming, and merging sports data from whoscored.com. It provides tools to process data from JSON to CSV, convert it into SPADL (Soccer Player Action Description Language) format, and aggregate data for comprehensive season analysis.

## Contents
1. **JSONGenerator.ipynb**: Extracts game data in JSON format from whoscored.com for each game of a league season.
2. **CSVGenerator.ipynb**: Converts the JSON files into regular CSV format for easier manipulation and analysis.
3. **CSVGeneratorSpadl.ipynb**: Transforms the CSV files into the SPADL format, tailored for soccer analytics.
4. **MergeCSV.ipynb**: Merges all individual game CSVs into a single file for a season, enabling holistic data analysis.

## Installation
Clone this repository using:


Ensure you have Jupyter Notebook installed to run these notebooks. You can install it via Anaconda or with pip:

## Usage
- Start by running `JSONGenerator.ipynb` to fetch and store the data in JSON format.
- Use `CSVGenerator.ipynb` to convert the JSON files to standard CSV format.
- For SPADL formatted data, run `CSVGeneratorSpadl.ipynb`.
- Finally, aggregate all CSVs with `MergeCSV.ipynb`.

## Requirements
- Python 3
- Jupyter Notebook
- Libraries: `soccerdata`, `pandas`, `os`, `glob` (Install these using pip or conda)

