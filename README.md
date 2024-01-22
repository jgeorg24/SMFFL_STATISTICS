#SMFFL STATS

This project is designed to store and manage statistics for a flag football league using a MySQL database. It includes tables for QB (Quarterback) Stats and WR/RB (Wide Receiver/Running Back) Stats for the Thanksgiving Bowl 2022-2023 season.

## Table of Contents
- [Introduction](#introduction)
- [Database Structure](#database-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Describe the purpose and goals of your project. Include any relevant background information.

## Database Structure

### QBStats Table

- PlayerID
- Name
- PassTD
- RushTD
- PassPAT
- RushPAT
- INTQB
- FumbleQB
- TotalTDSQB
- PassAttempts
- PassCompletions
- CompletionPercentage
- QBR
- QBRuns
- RushingYards
- PassingYards

### WRRBStats Table

- PlayerID
- Name
- Handoffs
- Targets
- Receptions
- ReceivingTD
- ReceivingYards
- RushingYards
- RushTD
- ReceivingPAT
- RushPAT
- FumbleWR

## Getting Started

1. Clone the repository.
2. Create the necessary database and tables using the provided SQL scripts.
3. Insert sample data into the tables.

## Usage

Provide instructions on how to use your project. Include examples of SQL queries and commands for interacting with the database.

```sql
-- Example SQL query
SELECT * FROM ThanksgivingBowl_2022_2023.QBStats;
