# Project Name

## Overview

This repository contains various tasks and examples that showcase different concepts in MySQL, NoSQL, and other backend technologies. Each task focuses on a specific concept and demonstrates the use of the technology involved, ranging from database initialization scripts to Python logging and data manipulation.

## Directory Structure

- **0x00-MySQL_Advanced**  
  Contains advanced MySQL scripts and configurations.
  
  - `100-init.sql`: Initializes the MySQL database.

- **0x01-NoSQL**  
  Includes various NoSQL tasks, such as data dumps, Python scripts, and more.
  
  - `102-log_stats.py`: Python script for logging statistics in a NoSQL database.
  - `dump.zip`: A zipped file containing database dumps.
  - `dump/`: Directory containing additional dump data.

- **auto_commit.sh**  
  A shell script used for automatically committing changes to the repository with predefined commit messages.

## Setup and Installation

To set up the project locally, follow these steps:

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/projectname.git
cd projectname
```

2. **Ensure MySQL is set up**

Run the 100-init.sql script to set up the database in MySQL:

```bash
mysql -u root -p < 0x00-MySQL_Advanced/100-init.sql
```

3. **Install required Python packages (for the NoSQL tasks)**

If not already installed, use pip to install dependencies:

```bash
pip install -r requirements.txt
```

4. **Run the Python script**

To log stats using 102-log_stats.py, run:
```bash
python 0x01-NoSQL/102-log_stats.py
```

5. **Running the shell script**

To automatically commit the files with backdated timestamps, run:
```bash
bash auto_commit.sh
```