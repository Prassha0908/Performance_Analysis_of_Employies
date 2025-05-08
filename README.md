<div align="center">

# PERFORMANCE ANALYSIS OF EMPLOYIES

"Turning raw call logs into actionable insights – seamlessly and smartly."

</div>


## Table of Contents 📜

- [About the Project](#about-the-project-)
- [Features](#features-)
- [Quick Start](#quick-start-)
- [How to Use](#how-to-use-)
- [Acknowledgments](#acknowledgments-)
- [Conclusion](#conclusion-)

## About the Project 📖

The "Performance Analysis of Employies" is a structured Jupyter Notebook project designed to simulate a real-world DataOps workflow for analyzing daily call center activity. The code processes three raw CSV datasets — call logs, agent roster, and disposition summary — to produce a clean, merged output for performance reporting.

🔧 What this code does:

1. Loads required libraries for data handling and logging.

2. Reads raw CSV files into dataframes and parses datetime fields.

3. Cleans and standardizes data (e.g., handling missing values, renaming columns).

4. Performs joins across multiple datasets using agent IDs and timestamps.

5. Creates a structured output with key metrics like call durations, agent mapping, and call dispositions.

6. Exports the final dataset as a CSV or displays it for further analysis.

This notebook was developed as part of a data engineering evaluation task and can be extended into a scheduled pipeline for real-time call monitoring.



## Features 🔍

* **End-to-End Data Pipeline** : From loading raw files to generating clean, ready-to-analyze datasets.
* **Automated Date Parsing** : Seamlessly converts and handles various datetime formats.
* **Robust Logging System** : Monitor the pipeline with logs instead of prints.
* **Error Handling** : Catches and logs exceptions for smooth execution.


## Quick Start

```bash
# Clone the repository
git clone https://github.com/Prassha0908/Performance-Analysis-of-Employies.git

# Navigate to the project directory
cd Performance-Analsis-of-Employies

# (Optional) Set up virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

> Make sure to upload or place the following files in your working directory:
>
> * `call_logs.csv`
> * `agent_roster.csv`
> * `disposition_summary.csv`

## How to Use

Run the notebook using **Google Colab** or **Jupyter Notebook**. Each section is clearly marked:

1. Load necessary libraries and logger setup
2. Load and parse the input datasets
3. Perform cleaning and joins
4. Generate summary or export results

📘 Detailed steps and logic are commented within the code.


## Acknowledgments

This project reflects real-world DataOps practices and was executed for technical evaluation and professional development.


## Created by:

 **PRASSHANTHINI R**
  📧 [For Details](mailto:prasshanthinir.21aid@kongu.edu)

#### With guidance and support from the community 💡



## Get Involved!

I welcome your contributions and feedback:

* **Raise Issues**: Find a bug? [Report it](https://github.com/Prassha0908/Performance-Anaysis-of-Employies/issues/new)
* **Fork & PR**: Add new enhancements or scripts and submit a pull request
* **Spread the Knowledge**: Star 🌟 the repo and share it with fellow data enthusiasts!


## Acknowledgments

* Inspired by daily DataOps challenges in call center reporting.
* Thanks to the **open-source** and **Python** communities for libraries and learning.



## License

This project is licensed under the **MIT License** – use it freely and responsibly.



## Conclusion

The **Performance Analysis of Employies** turns complex raw datasets into clean, usable insights with minimal effort. Whether for operational monitoring, reporting, or decision-making, this pipeline is a reliable starting point for scalable data processing workflows in customer service environments.


