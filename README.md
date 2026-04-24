# Enterprise E-commerce Log Analyzer

## Overview
A professional Python-based analytical engine designed to automate the parsing and visualization of more than **1 million unstructured server log entries**. This tool utilizes high-performance **Regular Expressions** for data extraction and leverages **Pandas/Seaborn** to transform raw traffic logs into actionable system-health dashboards.

## Key Features
* **High-Precision Regex Extraction:** Deep-parsing of timestamps, HTTP status codes, and specific endpoints (e.g., `/usr/login`, `/usr/admin`).
* **Big Data Management:** Configured with an optimized **`.gitignore`** to manage a **240MB dataset** while maintaining a lightweight repository footprint.
* **Visual Insights:** Automated generation of **Baseline and Advanced Dashboards** to visualize traffic frequency and error distributions (4xx/5xx).
* **Dependency Standardization:** Includes a **`requirements.txt`** for seamless environment replication across different systems.

## Tech Stack
* **Language:** Python
* **Data Science:** Pandas, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook (`Analysis.ipynb`)
* **Version Control:** Git & GitHub

## Project Structure
* `Analysis.ipynb`: The core analytical logic and visualization notebook.
* `The Advanced Dashboard.png`: Visual output of analyzed traffic bottlenecks.
* `requirements.txt`: List of necessary Python libraries for setup.
* `Document/`: Directory containing **HLD** and **LLD** project documentation.

## Setup & Installation
1. **Clone the repository:**
   `git clone https://github.com/26938-Afrah/Ecommerce-Log-Analyzer.git`
2. **Install Libraries:** `pip install -r requirements.txt`
3. **Dataset Note:** Due to GitHub's file size limits, the **`logfiles.log`** file is excluded from the repository. Place your local log dataset in the root folder before execution.
