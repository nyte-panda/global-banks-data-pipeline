# Top 10 Largest Banks ETL Pipeline Project

## Project Overview
This project demonstrates an end-to-end ETL (Extract, Transform, Load) pipeline using Python. The goal is to acquire, process, and store data about the world's top 10 largest banks by market capitalization. The extracted data is enhanced with currency conversions (GBP, EUR, INR) and stored both as a CSV file and in a SQL database.

## Technologies Used
- Python
- Pandas
- SQLite
- SQL
- Logging
- CSV Handling

## Data Sources
- Bank Data: [Wikipedia - Largest Banks](https://web.archive.org/web/20230908091635/https://en.wikipedia.org/wiki/List_of_largest_banks)
- Exchange Rates: [Exchange Rate CSV](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-PY0221EN-Coursera/labs/v2/exchange_rate.csv)

## Project Workflow
1. Log Progress: Tracks each stage of execution in `code_log.txt`.
2. Data Extraction: Scrapes bank data from the provided Wikipedia URL.
3. Data Transformation: Converts market capitalization values to GBP, EUR, and INR.
4. Load to CSV: Stores processed data in `Largest_banks_data.csv`.
5. Load to Database: Saves data in a SQLite database (`Banks.db`) under the table `Largest_banks`.
6. Query Database: Validates the database with specific SQL queries.

## Output Files
- `Largest_banks_data.csv` — Final processed dataset.
- `Banks.db` — SQL database storing bank information.
- `code_log.txt` — Log file tracking pipeline execution.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/largest-banks-etl.git
   cd largest-banks-etl
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the pipeline:
   ```bash
   python banks_project.py
   ```

## Project Tasks
- Task 1: Logging pipeline progress.
- Task 2: Extract tabular data.
- Task 3: Transform data with currency conversion.
- Task 4: Save data to CSV.
- Task 5: Load data into SQL database.
- Task 6: Query database.
- Task 7: Validate logs.

## Contributing
Contributions are welcome! Feel free to fork, submit pull requests, or suggest improvements.

Happy Coding!
