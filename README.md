# SMFFL STATS

This repository is designed to store and manage statistics for SMFFL using a MySQL database. It includes tables for statistics from each bowl game of the 2022-2023 season and 2023-2024 season.

## Table of Contents
- [Games Included](#games-included)
- [Getting Started](#getting-started)
- [Contributors](#contributors)
- [Usage](#usage)

## Games Included

2022-2023 Season
- Thanksgiving
- Christmas Bowl
- Spring Slingfest
- Summer Kickoff
- Endgame

2023-2024 Season
- Thanksgiving
- New Year's Bowl
- Spring Slingfest
- Summer Kickoff
- Endgame

## Getting Started

1. Create a schema for each bowl game in MySQL Workbench, for example, "ThanksgivingBowl_2022_2023".
2. Download the .csv files for each bowl game.
3. In MySQL Workbench, right-click "Tables" under the SCHEMAS tab.
4. Select "Table Data Import Wizard".
5. Browse and select the .csv file.
6. Click next and refresh the SCHEMAS.
   
## Contributors
- Jacob George
- Joel George


## Usage

Provide instructions on how to use your project. Include examples of SQL queries and commands for interacting with the database.

```sql
-- Example SQL query
SELECT * FROM ThanksgivingBowl_2022_2023.QBStats;
