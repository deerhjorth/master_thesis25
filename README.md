# Master Thesis 2025 – Copenhagen Business School

## Overview

This repository contains the codebase for our Master's thesis at Copenhagen Business School (CBS), submitted as part of the MSc in Business Administration and Data Science program.

**Authors:**
- Christian Hjorth (Student ID: S167327)
- Kristian Emil Nordby Madslangrud (Student ID: S157528)

## Project Description

This project explores how lobbying activities influence political sentiment in U.S. Congress. It involves extensive collection, processing, and integration of large-scale lobbying records and congressional tweets, followed by natural language processing to identify sentiment patterns and their alignment with lobbying efforts.

## Repository Structure

- `main.ipynb`: Primary notebook. Can be executed directly and handles all setup and execution steps.
- `requirements.txt`: Lists all required Python packages.
- Supporting notebooks:
  - `congress_api.ipynb`
  - `data_load_tocsv.ipynb`
  - `network_analysis.ipynb`
  - `twitter_data.ipynb`
  - `txt_to_csv.ipynb`

## How to Run

1. Clone the repository:

   git clone https://github.com/deerhjorth/master_thesis25.git
   
   cd master_thesis25

2. Install dependencies:

   pip install -r requirements.txt

3. Open and run `main.ipynb` in Jupyter or any other compatible notebook environment.

The notebook will:
- Ensure all required packages are installed.
- Automatically download data files from a public Google Drive folder (due to GitHub's file size limitations).

## Data

The dataset used in this thesis is not stored in this repository due to size constraints. Instead, it is hosted in a public Google Drive folder. All necessary data will be automatically downloaded by the notebook.

## Contact

For questions or feedback:

- Christian Hjorth – chhj23ab@student.cbs.dk
- Kristian Emil Nordby Madslangrud – krma22ac@student.cbs.dk