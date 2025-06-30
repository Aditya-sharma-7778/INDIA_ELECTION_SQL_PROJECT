# INDIA_ELECTION_SQL_PROJECT



🗳️ India Elections 2024 – SQL Data Analysis Project
This project analyzes the 2024 Indian General Election results using SQL. It provides a detailed breakdown of voting trends, alliances, state-wise performance, and winning margins using cleanly structured SQL queries across normalized tables.

🎯 Project Objectives
Store and query real-world election data in SQL tables

Analyze voting patterns at national, state, constituency, and party levels

Compare performance between NDA, I.N.D.I.A., and other alliances

Extract meaningful political and electoral insights using pure SQL

Gain hands-on experience with multi-table joins, aggregations, and filtering

📁 Files Included

india_election_project_2024.sql	
constituencywise_results.csv	
constituencywise_details.csv	
states.csv	


🧱 Database Schema
constituencywise_details – Candidate-level vote data

constituencywise_results – Final result per constituency

partywise_results – Party-wise wins

statewise_results – State-constituency mapping with leading/trailing candidates

states – State ID and name mapping

📊 Key Results & Insights (Extracted via SQL)

| 🔍 Query Type              | 📌 Insight                                                                |
| -------------------------- | ------------------------------------------------------------------------- |
| 🧾 Total Seats             | Counted total parliamentary seats available                               |
| 📍 State-Wise Seats        | Number of seats available per state                                       |
| 🟠 NDA Performance         | Total seats won by NDA alliance & individual party performance            |
| 🔵 I.N.D.I.A. Performance  | Same analysis for the I.N.D.I.A. alliance                                 |
| ⚖️ Alliance Comparison     | Which alliance won the most seats nationally                              |
| 🏆 Victory Details         | For a given state & constituency, display winner, margin, party, alliance |
| 🧮 Vote Type Analysis      | EVM vs postal vote distribution per candidate in any constituency         |
| 🏛️ State-level Party Wins | Top winning parties in any state (e.g., Andhra Pradesh, Maharashtra)      |
| 📊 Alliance Seat Split     | NDA vs I.N.D.I.A. vs Other seat share across all states                   |
| 🥇 Top Performers          | Candidates with highest EVM votes in each constituency                    |
| 🇮🇳 Maharashtra Overview  | Seats, votes, candidates, parties, EVM/postal totals in Maharashtra       |


🛠 Tools Used
SQL (tested in MySQL / PostgreSQL environments)

Excel (for CSV file preparation)

DB Browser / pgAdmin (for database visualization)

🚀 How to Run
Import the SQL file india_election_project_2024.sql into your DBMS

Load the .csv files into the respective tables (constituencywise_details, states, etc.)

Run analysis queries in sequence as shown in the script

Modify queries to explore more insights (e.g., for your state/constituency)

📚 Learning Outcomes
Advanced use of JOINs, GROUP BY, CASE, and subqueries

Real-world experience with multi-table analysis

Building analytical reports using only SQL (no visualization tool)

Understanding Indian electoral data structures

